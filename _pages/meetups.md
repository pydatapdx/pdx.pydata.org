---
title:  PyData PDX
permalink: /meetups/
author_profile: false
---
# Past Meetup Events
_materials for some talks pending_

{% assign past_meetups = site.meetups | sort: 'date' | reverse %}
{% for meetup in past_meetups %}
{{ meetup.date | date: '%B %d, %Y' }}
{{ meetup.content }}

{% endfor %}
