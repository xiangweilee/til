To iterate over dictionary data in Jinja template, `use iteritems()`

```jinja
{% for config, value in configs.iteritems() -%}
{{ config }} = {{ value }}
{% endfor -%}
```
