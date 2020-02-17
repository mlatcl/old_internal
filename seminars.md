---
layout: default
title: Seminar Series
---

The group has two seminar series.

## Formal Seminars

Firstly, our monthly seminar series which is organised by invite.

{% assign lastone = site.seminars | last %}
{% for seminar in site.seminars %}
{% include listseminar.html %}
{% endfor %}

## Ad Hoc Seminars

Secondly, our ad-hoc seminar series organised on an opportunistic basis when someone interesting is in town.

{% assign lastone = site.ad-hoc-seminars | last %}
{% for seminar in site.ad-hoc-seminars %}
{% include listseminar.html %}
{% endfor %}


