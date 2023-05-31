---
layout: default
title: "about"
permalink: /about
---

<style>
 .container {
  display: flex;
  <!-- align-items: center; -->
  <!-- justify-content: center -->
}
img {
  max-width: 100%;
  max-height:100%;
}

.text {
  font-size: 15px;
  padding-left: 3px;
  align-items: left;
  justify-content: left;
  text-align: left;
 
}
 </style>



<title>About</title>
<h1>About</h1>
The Past Global Change FAIROS RCN is an NSF-funded research coordination network, led by Professor Jessica Blois, University of California - Merced.

<h2>Meet the Principal Investigators</h2>
{% for team_member in site.team_members %}
<div class="container">
  <div class="image">
   <!-- # <img style="float:left" src={{ team_member.picture }}> remove pictures for now -->
  </div>
  <div class="text">
  <p style="text-align:left;"> {{ team_member.name }}, {{team_member.role }}, {{team_member.institution }} </p>
  </div>
</div>
{% endfor %} 

<h2>Biosphere Workshop</h2>
 <figure>
  <img src="./images/Blois_group_3.jpeg" alt="Group Picture" style="display:block" align="absbottom">
  <figcaption>Members of the FAIROS RCN gathered at the Biosphere 2 in Arizona to determine project goals. May 16-19, 2023. </figcaption>
 </figure>


Return to [main page](home.md)

