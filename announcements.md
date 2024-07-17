---
layout: page
nav_exclude: false
nav_order: 2
title: Announcements
description: A feed containing all of program announcements.
---

# Announcements

This page contains announcements for the 2024 Blacks at Microsoft (BAM) Summer Mentorship Program. Be sure to check back regularly as they'll be updates week-to-week.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
