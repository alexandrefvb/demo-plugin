{{ inputs.any_number }}

{% for value in inputs.any_list %}
- {{value}}
{% endfor %}