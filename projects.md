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

[Data Trusts Initiative](https://datatrusts.uk)

[Accelerate Programme for Scientific Discovery](https://www.cst.cam.ac.uk/accelerate)


## Former Projects

{% for project in site.projects %}
{% if project.finished %}{% include listproject.html %}{% endif %}
{% endfor %}

[Data Evaluation and Learning for Viral Epidemics, DELVE](https://rs-delve.github.io/about.html)
