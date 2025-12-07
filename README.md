# cedi-code
List of projects I made.

{% assign sorted_projects = site.projects | sort: "order" | reverse %}

{% for project in sorted_projects %}
  
  {% include project_list_card.html project=project %}

{% endfor %}