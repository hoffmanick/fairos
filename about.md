---
layout: default
title: "about"
permalink: /about
---

{% include navigation.html %}

# About
The Past Global Change FAIROS RCN is an NSF-funded research coordination network, led by Professor Jessica Blois, University of California - Merced.

## Meet the Principal Investigators
{% for team_member in site.team_members %}
- {{ team_member.name }}, {{team_member.role }}, {{team_member.institution }}
{% endfor %} 

<img src="./images/Blois_group_3.jpeg" alt="Group Picture" style="display:block">
<p><small>Members of the FAIROS RCN gathered at the Biosphere 2 in Arizona to determine project goals. May 16-19, 2023. </small></p>

Return to [main page](home.md)
