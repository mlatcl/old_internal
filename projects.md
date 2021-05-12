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
* [Data Sharing in Africa: lessons from COVID-19](https://mamutorine.github.io/about/)
* [European Network of AI Excellence Centres, ELISE](https://www.elise-ai.eu/work/agenda-and-programs) 


## Former Projects

{% for project in site.projects %}
  {%-if project.finished-%}
    {%- include listproject.html prefix="* " postfix="" separator="" -%}
  {%- endif -%}
{% endfor %}
* [DELVE: Data Evaluation and Learning for Viral Epidemics](https://rs-delve.github.io/about.html)
