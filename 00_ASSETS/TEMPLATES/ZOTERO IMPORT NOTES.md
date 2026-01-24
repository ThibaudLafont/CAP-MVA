{{pdfZoteroLink}}

{% for annotation in annotations -%}
    {%- if annotation.imageRelativePath -%}
    ![[{{annotation.imageRelativePath}}]]^{{annotation.id}} {%- endif %}
{% endfor -%}