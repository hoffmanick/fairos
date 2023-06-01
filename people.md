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


<div class="text-block-main">
  <h1>Meet our Team</h1>
</div>

  <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; 
  background-color:#f0d2a1;margin-left:5%;padding-right:2.8%;padding-left:2%;max-width:350px;
  z-index:9;position:relative;overflow:visible; border-right:1px solid #ec970b; border-bottom:1px solid #ec970b;">
  The Principal Investigators</h2>
  
  <div class="text-block-main" style="flex-direction:column;flex-wrap:wrap;padding-top:0px; background-image:none; height:100px;">
    
    {% for team_member in site.team_members %}
        <div class="text-block-right" style="flex-direction:row; align-items:center;justify-content:space-around;
         border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; 
         max-width:350px;">
        
          <div class="image">
            <img src={{ team_member.picture }} style="min-width:100px;">
          </div>
        
          <div class="text" style="text-align:center;">
            <p>{{ team_member.name }}</p>
            <p style="padding:12px;">{{ team_member.role }}</p>
            <p style="padding:12px;">{{ team_member.institution }} </p>
          </div>
        </div>
    {% endfor %} 
  </div>
  
    <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; 
    background-color:#f0d2a1;margin-left:5%;padding-right:2.8%;padding-left:2%;max-width:350px;
    z-index:9;position:relative;overflow:visible; border-right:1px solid #ec970b; border-bottom:1px solid #ec970b;">
    The Advisory Committee</h2>
  
  <div class="text-block-main" style="flex-direction:column;flex-wrap:wrap;padding-top:0px; background-image:none;">
 
      {% for advise_member in site.advise_members %}
        <div class="text-block-right" style="flex-direction:row; align-items:center;justify-content:space-around;
        border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; max-width:350px;">
        
          <div class="image">
            <img src={{ advise_member.picture }} style="min-width:100px;">
          </div>
        
          <div class="text" style="text-align:center;">
            <p>{{ advise_member.name }}</p>
            <p style="padding:12px;">{{ advise_member.institution }} </p>
          </div>
        </div>
    {% endfor %} 
   </div>
