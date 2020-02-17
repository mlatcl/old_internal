---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


## People

{% for person in site.people %}
{% include listperson.html %}
{% endfor %}

## Ad Hoc Seminars

{% for seminar in site.ad-hoc-seminars %}
{% include listseminar.html %}
{% endfor %}

## Projects

{% for project in site.projects %}
{% include listproject.html %}
{% endfor %}

