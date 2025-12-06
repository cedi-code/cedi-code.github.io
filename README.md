# cedi-code
List of projects I made.

{% for project in site.projects reversed %}
  
  {% include project_list_card.html project=project %}

{% endfor %}