---
title: Projects
layout: default
---

<style>
ul {
  columns: 3;
  -webkit-columns: 3;
  -moz-columns: 3;
}
</style>


## Projects

{% for project in site.projects %}
{% unless project.finished %}{% include listproject.html %}{% endunless %}
{% endfor %}


## Former Projects

{% for project in site.projects %}
{% if project.finished %}{% include listproject.html %}{% endif %}
{% endfor %}
