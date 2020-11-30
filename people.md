---
title: People
layout: default
---

<style>
ul {
  columns: 3;
  -webkit-columns: 3;
  -moz-columns: 3;
}
</style>

## People

<ul>
{% for person in site.people %}
{% unless person.alumni %}{% include listperson.html prefix="<li>" postfix="</li>" separator="" %}{% endunless %}
{% endfor %}
</ul>

## Alumni

<ul>
{% for person in site.people %}
{% if person.alumni %}{% include listperson.html prefix="<li>" postfix="</li>" separator="" %}{%endif%}
{% endfor %}
</ul>
