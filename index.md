---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


## People

{% assign lastone = site.people | last %}
{% for person in site.people %}
{% include listperson.html %}
{% endfor %}

## Projects

{% assign lastone = site.projects | last %}
{% for project in site.projects %}
{% include listproject.html %}
{% endfor %}

