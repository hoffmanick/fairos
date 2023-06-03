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
  
div.text-block-main {
  padding-left: 5%
  }
</style>

<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #f0d2a1, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:40px auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:40px;height:40px;align-self:start;">Meet our Team</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">We have a lead team of principal investigators, an external advisory committee, personnel, and other RCN members.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/team.jpg" alt="Stakeholders" style="width=100%;">
        <figcaption>Members of the Ethical FAIROS RCN at the first annual symposium, on the premises of the Biosphere 2, in Arizona, May 2023. Photo: Kitty Emery.</figcaption>
      </figure>
    </div>
  </div>

<div class="text-block-right" style="display:grid;grid-template-rows:1.5em auto 1.5em auto;background-color:#f0d2a1;padding-left:0; width:100%;" id="meatblock">
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;width:100%;" id="pi-title">
  <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; background-color:#f0d2a1;;z- index:9;position:relative;overflow:visible; border-right:1px solid #ec970b; border-bottom:1px solid #ec970b;width:100%">The Principal Investigators</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:100%;">
  
    {% for team_member in site.team_members %}
        <div class="text-block-right" style="padding-left:0%;width:100%;display:grid;grid-template-columns: auto auto; align-content:center;justify-content:space-between;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; max-width:350px;">
        
          <div class="image">
            <img src={{ team_member.picture }} style="min-width:100px;border:1px solid #ec970b;">
          </div>
        
          <div class="text" style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content:center;">
            <p style="margin-top:2px;margin-bottom:2px;">{{ team_member.name }}</p>
            <p style="margin-top:2px;margin-bottom:2px;">{{ team_member.role }}</p>
            <p style="margin-top:2px;margin-bottom:2px;">{{ team_member.institution }} </p>
          </div>
        </div>
    {% endfor %} 
  </div>
<br>
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;" id="advise-title">
   <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; background-color:#f0d2a1;z-index:9;position:relative;overflow:visible; border-right:1px solid #ec970b; border-bottom:1px solid #ec970b;width:100%;">The Advisory Committee</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:100%;">
  
      {% for advise_member in site.advise_members %}
        <div class="text-block-right" style="padding-left:0%;width:100%;display:grid;grid-template-columns: auto auto; align-content:center;justify-content:space-between;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; max-width:350px;">
        
          <div class="image">
            <img src={{ advise_member.picture }} style="min-width:100px;border:1px solid #ec970b;">
          </div>
        
          <div class="text" style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content:center;">
            <p style="margin-top:2px;margin-bottom:2px;">{{ advise_member.name }}</p>
            <p style="margin-top:2px;margin-bottom:2px;">{{ advise_member.institution }} </p>
          </div>
        </div>
      {% endfor %} 
  </div>
</div>
  
  
 
