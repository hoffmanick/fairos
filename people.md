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
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:40px;align-self:start;">Meet our Team</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">We have a lead team of principal investigators, an external advisory committee, personnel, and other RCN members.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/team.jpg" alt="Stakeholders" style="width=100%;border: 1px solid #ec970b;">
        <figcaption>Members of the Ethical FAIROS RCN at the first annual symposium, on the premises of the Biosphere 2, in Arizona, May 2023. Photo: Kitty Emery.</figcaption>
      </figure>
    </div>
  </div>

<div class="text-block-right" style="display:grid;grid-template-rows:1.5em auto 1.5em auto;background-color:#f0d2a1;padding-left:0; width:100%;" id="meatblock">
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;width:100%;" id="pi-title">
  <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; background-color:#f0d2a1;;z- index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%">The Principal Investigators</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:95%;margin-left:5%;">
  
    {% for team_member in site.team_members %}
        <div class="text-block-right" style="padding-left:0%;display:grid;grid-template-columns: auto auto; align-content:center;align-items:center;justify-content:space-evenly;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; padding-top:0px;padding-bottom:0px;width:93%;padding-right:2%; margin-left:3%; border-left: 1px solid #ec970b; padding-left:2%;justify-items:center;max-width:290px;grid-auto-rows: 1fr;">
          <div style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content:center;padding-left:50%;width:150%;">
            <p style="font-size:15px;font-weight:bold;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.name }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.role }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.institution }} </span></p>
          </div>
          
          <div class="image" style="padding:5px;">
            <img src={{ team_member.picture }} style="min-width:100px;border:1px solid #ec970b;">
          </div>
        </div>
    {% endfor %} 
  </div>
<br>
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px; width:100%;" id="advise-title">
   <h2 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;margin-bottom:0px; background-color:#f0d2a1;z-index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%;">The Advisory Committee</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:95%;margin-left:5%;">
  
      {% for advise_member in site.advise_members %}
        <div class="text-block-right" style="padding-left:0%;width:100%;display:grid;grid-template-columns: auto auto; align-content:center;align-items:center;justify-content:space-evenly;justify-items:start;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; padding-top:0px;padding-bottom:0px;width:93%;padding-right:2%; margin-left:3%; border-left: 1px solid #ec970b; padding-left:2%;justify-items:center;max-width:290px;grid-auto-rows: 1fr;">

          <div style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content: center;font-size:15px;padding-left:8%;width:92%;padding-left:50%;width:150%;">
            <p style="font-size:15px;font-weight:bold;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ advise_member.name }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ advise_member.institution }}</span></p>
          </div>
          
          <div class="image" style="padding:5px;">
            <img src={{ advise_member.picture }} style="min-width:100px;border:1px solid #ec970b;">
          </div>
          
        </div>
      {% endfor %} 
  </div>
</div>
  
  
 
