---
layout: main
title:  PyData PDX
---

{% include hero.html %}

# Welcome to Pydata PDX!
## About the Community

The monthly REMOTE meetups are put together by a group of volunteers organizers passionate about Python.
Since 2019, we have provided Pythonistas in Portland a forum to learn from each other on the use of Python in the ever-evolving fields of data management, processing, analytics and visualisation.
PyData PDX meetups (usually) take place on the second Wednesday of each month.

## Pandemic Update
We now meet online rather than in person, and will continue to do so for the duration of the coronavirus pandemic. While the meetups are now BYO pizza and drinks, we continue to provide community, interesting speakers (including local legends and some big names from out of town!), and all the Python and data talk you might want. Our remote meetups are going strong and we'd love to have you.

## About the Speakers
All speakers at PyData PDX meetups and conferences do so altruistically!
Many thanks to all speakers who volunteer their time to prepare fantastic content to educate and enlighten fellow Pythonistas.

We welcome speakers from all levels and backgrounds &mdash; [please submit a talk!](/submit)

## About the Organizers
Behind the scenes, unpaid volunteers organize the logistics and content of every meetup.
The organizers have day jobs to pay their bills and dedicate their free time for the benefit of the community.

The current organizers are:
{% assign current_organizers = site.organizers %}
{% for organizer in current_organizers %}
{{ organizer.content }}
{% endfor %}


