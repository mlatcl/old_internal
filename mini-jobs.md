---
layout: default
title: Mini-jobs
---

## What's a mini-job you say? 🤔

## Mini-job properties include:
 
1. A small task that someone needs to do. This may or may not be related to research. These shouldn't be big time investments, more like small things that we collectively should remember to do. 💭
2. Relates to the team / group's overall well-being. Mini-jobs are something the group needs to do, and benefits us all. Ex. Organizing a reading group 📗
3. Needs to be done on an ongoing basis. One-off tasks like organizing a workshop aren't mini-jobs. Organizing a monthly pub outing is though. 🍻
4. Can be owned by one person. It is their responsibility to make sure the task gets done. This doesn't mean you have to do it all by yourself, but its your responsibility 💃🏼
5. Everyone should have one! The purpose is to balance side work across the team so a few people don't end up doing all the organizing / admin / etc. 👨‍👩‍👧‍👧👨‍👨‍👧‍👦👩‍👩‍👦‍👦 If there aren't enough jobs... Find something else to help out with and make one up!
6. Includes a detailed enough description for someone else to pick up the mini-job in your stead. This will differ for each job, but just make sure that someone else wouldn't be lost if they needed to do it . Links to relevant pages are great here 👏

## List of Minijobs

{% for job in site.minijobs %}
{% include listminijob.html %}
{% endfor %}
