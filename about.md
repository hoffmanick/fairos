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
 h1 {
   color: #42b7bf;
   -webkit-text-stroke-width: 2px;
   -webkit-text-stroke-color: black;
    }
  p {
    font-size: 20px;
  }
.text-block-right {
  width:500px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: 25%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to left, white, #97b779); 
  text-align: center;
}
  .text-block-left {
  width:500px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: -25%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to right, white, #97b779); 
  text-align: center;
}
  .text-block-main {
  width:800px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: -5%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to left, white, #97b779); 
}
  .text-block-main  p {
  font-size: 20px;
}
 </style>


<div class="text-block-main">
<h1>About</h1>
<p>The Past Global Change FAIROS RCN is an NSF-funded research coordination network, led by Professor Jessica Blois, University of California - Merced. </p>
</div>
<div class="text-block-right">
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
 </div>

<div class="text-box-left">
  <h2>Biosphere Workshop</h2>
  <figure>
  <img src="./images/Blois_group_3.jpeg" alt="Group Picture" style="display:block" align="absbottom"/>
  <figcaption>Members of the FAIROS RCN gathered at the Biosphere 2 in Arizona to determine project goals. May 16-19, 2023.</figcaption>
 </figure>
 </div>



