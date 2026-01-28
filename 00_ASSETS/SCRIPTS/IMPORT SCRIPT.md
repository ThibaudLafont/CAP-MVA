```
import re
import requests
# import sys
from pathlib import Path

def call_api(url, payload):
    return requests.get(url, json=payload);

def build_add_payload(deckName, modelName, recto, verso):
    return {
        "action": "addNote",
        "version": 5,
        "params": {
            "note": {
                "deckName": deckName,
                "modelName": modelName,
                "fields": {
                    "Recto": recto,
                    "Verso": verso
                }
            }
        }
    };

def parse_md(path: Path):
    text = path.read_text(encoding="utf-8")
    pairs = re.findall(r"Q:\s*(.+?)\nR:\s*(.+?)(?:\n\n|$)", text, re.S)
    return [(q.strip(), r.strip()) for q, r in pairs]



url = "http://localhost:8765";
deckName = "Mécanique";
modelName = "Basique";
md_path = "txt.txt"

to_add = parse_md(Path(md_path));
for q, r in to_add:
    payload = build_add_payload(deckName, modelName, q, r);
    response = call_api(url, payload);
    print(response.json())





# Latin: 1768058514396, Mécanique: 1768722108576, Philo: 1768298907521
# Basique: 1768058414867 ; [Recto, Verso]
```
