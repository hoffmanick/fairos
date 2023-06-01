---
layout: default
title: "people"
permalink: /people
---

<style>
  div.image {
  object-fit: contain;
  width: 25%;
  height: 25%
  min-width: 100px;
  }  
</style>


<div class="text-block-main" style="width:250px;">
  <h1>Meet our Team</h1>
</div>

<div class="text-block-right">
  <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;">The Principal Investigators</h2>
  {% for team_member in site.team_members %}
      <div class="text-block-main">
        <div class="image">
          <img src={{ team_member.picture }}>
        </div>
        <div class="text">
          <p style="text-align:left;"> {{ team_member.name }}, {{team_member.role }}, {{team_member.institution }} </p>
        </div>
      </div>
  {% endfor %} 
</div>
