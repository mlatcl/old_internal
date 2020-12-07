---
title: Projects
layout: default
---

<style>
ul {
  columns: 2;
  -webkit-columns: 2;
  -moz-columns: 2;
}
</style>


## Projects

{% for project in site.projects %}
  {%- unless project.finished -%}
    {%-include listproject.html prefix="* " postfix="" separator="" -%}
  {%- endunless -%}
{% endfor %}
* [Data Trusts Initiative](https://datatrusts.uk)
* [Accelerate Programme for Scientific Discovery](https://www.cst.cam.ac.uk/accelerate)


## Former Projects

{% for project in site.projects %}
  {%-if project.finished-%}
    {%- include listproject.html prefix="* " postfix="" separator="" -%}
  {%- endif -%}
{% endfor %}
* [Data Evaluation and Learning for Viral Epidemics, DELVE](https://rs-delve.github.io/about.html)
