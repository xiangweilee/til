To iterate over dictionary data in Jinja template, `use iteritems()`

```jinja
{% for config, value in configs.iteritems() -%}
{{ config }} = {{ value }}
{% endfor -%}
```

http://blog.mattcrampton.com/post/31254835293/iterating-over-a-dict-in-a-jinja-template
