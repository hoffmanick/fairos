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
.topnav {
  background-color: #d3d9ed;
  overflow: hidden;
 }
.topnav a {
  float: left;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
 }
.topnav a:hover {
  background-color: #e1e5f0;
  color: #5e72ab;
 }
.topnav a.active {
  background-color: #e1e5f0;
  color: #4860a3;
}
 </style>


<div class="topnav">
 <a target="_blank" style="border-right: 1px solid blue;" href="home">Home</a>
 <a style="border-right: 1px solid blue;" class="active" href="about">About</a>
 <a style="border-right: 1px solid blue;" href="research">Research</a>
 <a style="border-right: 1px solid blue;" href="calendar">Calendar</a>
</div>
<br>
<hr>


# About
The Past Global Change FAIROS RCN is an NSF-funded research coordination network, led by Professor Jessica Blois, University of California - Merced.

## Meet the Principal Investigators
{% for team_member in site.team_members %}
<div class="container">
  <div class="image">
   <!-- # <img src={{ team_member.picture }}> remove pictures for now -->
  </div>
  <div class="text">
  <p style="text-align:left;"> {{ team_member.name }}, {{team_member.role }}, {{team_member.institution }} </p>
  </div>
</div>
{% endfor %} 

<div style="line-height:10px">
  <img src="./images/Blois_group_3.jpeg" alt="Group Picture" style="display:block" align="absbottom">
  </div>
<p><small>Members of the FAIROS RCN gathered at the Biosphere 2 in Arizona to determine project goals. May 16-19, 2023. </small></p>

Return to [main page](home.md)

