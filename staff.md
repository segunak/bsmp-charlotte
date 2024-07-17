---
layout: page
nav_exclude: false
nav_order: 6
title: Staff
description: A listing of all the program staff members.
---

# Staff

Here are the staff members for the 2024 Blacks at Microsoft (BAM) Summer Mentorship Program in Charlotte, North Carolina. Feel free to **click on any staffers name to connect with them on LinkedIn!**

## Program Team

{% assign staff = site.staffers %}
{% for staffer in staff %}
{{ staffer }}
{% endfor %}
