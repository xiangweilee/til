To strip whitespace in Jinja's template, add minus sign to the end of block

```jinja
{% for item in seq -%}
    {{ item }}
{%- endfor %}
```

http://jinja.pocoo.org/docs/dev/templates/#whitespace-control
