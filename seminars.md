---
layout: default
title: Seminar Series
---

The group has two seminar series.

## Formal Seminars

Our seminar series invites leading figures in machine learning to discuss topics of current interest. Upcoming events include:

**An AI revolution in science? Using machine learning for scientific discovery**
Neil Lawrence, Kyle Cranmer, Yolanda Gil, Pushmeet Kohli, Emily Shuckburgh
26 April 2021, 17:00 - 18:30 (register at: https://www.cst.cam.ac.uk/news/ai-revolution-science-using-machine-learning-scientific-discovery)

{% assign lastone = site.seminars | last %}
{% for seminar in site.seminars %}
{% include listseminar.html %}
{% endfor %}

## Ad Hoc Seminars

Our ad-hoc seminar series is organised on an opportunistic basis when someone interesting is in town. Upcoming talks include:

**GPs and Quantum Field Theory**
Jim Halverson, Northeastern University
 (4 May 2021, 15:00 - 16:00)

For further information about talks in this series, please visit: https://talks.cam.ac.uk/show/index/113458

{% assign lastone = site.ad-hoc-seminars | last %}
{% for seminar in site.ad-hoc-seminars %}
{% include listseminar.html %}
{% endfor %}


