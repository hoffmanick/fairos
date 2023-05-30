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
ul.topnav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  background-color: #d3d9ed;
  overflow: hidden;
  position: sticky;
  top: 0;
 }
ul.topnav li {float: left;}
ul.topnav li a {
  float: left;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
 }
ul.topnav li a:hover:not(.active) {
  background-color: #e1e5f0;
  color: #5e72ab;
 }
ul.topnav a.active {
  background-color: #e1e5f0;
  color: #4860a3;
}
@media screen and (max-width: 600px) {
  ul.topnav li.right, 
  ul.topnav li {float: none;}
}
 </style>


{% include navigation.html %}

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

