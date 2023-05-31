---
layout: default
title: "about"
permalink: /about
---

<style>
 h1 h1 h2 h3 h4 h5 {
   color: #42b7bf;
   -webkit-text-stroke-width: 1px;
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
<h1 style="color:#42b7bf;-webkit-text-stroke-width:1px;-webkit-text-stroke-color:black;">About</h1>
 <p>This project is supported by the National Science Foundation: <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226368&HistoricalAwards=false">NSF-2226368</a> to Jessica Blois (University of California - Merced), <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226369&HistoricalAwards=false">NSF-2226369</a> to Jack Williams and Simon Goring (University of Wisconsin - Madison), <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226370&HistoricalAwards=false">NSF-2226370</a> to Kitty Emery and Michelle LeFebvre (University of Florida) and Suzanne Pilaar Birch (University of Georgia), <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226371&HistoricalAwards=false">NSF-2226371</a> to Andrea Thomer (University of Michigan, now at U. Arizona), <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226372&HistoricalAwards=false">NSF-2226372</a> to Meghan Balk (NEON), and <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2226373&HistoricalAwards=false">NSF-2226373</a> to Leigh Anne Lieberman (The Alexandria Archive Institute/Open Context). For more information, consult the linked individual NSF award abstracts. </p>
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




