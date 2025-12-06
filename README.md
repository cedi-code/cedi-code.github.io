# cedi-code
List of projects I made.

{% for project in site.projects %}
  
  {% include project_list_card.html project=project %}

{% endfor %}