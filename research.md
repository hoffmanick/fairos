---
layout: default
title: research
permalink: /research
---
<style>

div.text-block-main {
  display: grid;
  grid-template-rows: auto auto auto;
  margin-right:0px;
  padding-bottom:0px;
  }
div.text-block-right {
  margin-right:0px;
  padding-right:0px;
  width:100%;
  padding-left:0px;
  }
  
  h3 {
  color: #000;
  }
  
  #aimses {
  /**
   * User input values.
   */
  --grid-layout-gap: 10px;
  --grid-column-count: 4;
  --grid-item--min-width: 160px;

  /**
   * Calculated values.
   */
  --gap-count: calc(var(--grid-column-count) - 1);
  --total-gap-width: calc(var(--gap-count) * var(--grid-layout-gap));
  --grid-item--max-width: calc((100% - var(--total-gap-width)) / var(--grid-column-count));

  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(max(var(--grid-item--min-width), var(--grid-item--max-width)), 1fr));
  grid-gap: var(--grid-layout-gap);
}
  
 @media print, screen and (max-width: 480px) {
  #stakes, #describe {
  width:200px;
  }
  }
  
</style>

<div class="text-block-main" style="display:grid;grid-template-rows:auto auto;margin:0;padding-left:0;width:100%;" id="block1">
  <div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #f0d2a1, #97b779);padding:0;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:40px auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:40px;height:40px;align-self:start;">Research</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">We are pursuing three research aims.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;" id="stakes">
        <img src="./images/fairos-stakeholders.jpg" alt="Stakeholders" style="width=100%;">
        <figcaption>The sets of lead and affiliated data resources involved in this RCN. </figcaption>
      </figure>
    </div>
  </div>
  
  <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:blue;padding:0px;" id="meatblock">
    <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;" id="aims-title">
      <h2 style="margin-bottom:0px;padding-bottom:3px;border-bottom: 1px solid #ec970b;">Project Aims</h2>
    </div>
    <div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fill, minmax(400px, 1fr));justify-content:space-around;justify-items: space-around; padding-top:17px;margin-right:0px;" id="aimses">
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim1" style="font-size:1.4em">Aim 1:</a> Improve Interoperability and Reproducibility </h3>
        <p> We will a) develop guidance for interoperability among long-tail community-curated data resources and
        b) promote adoption of broader metadata standards. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim2" style="font-size:1.4em">Aim 2:</a> Enable FAIR Data Curation and Stewardship </h3>
        <p>  We will a) promote better data science and curation practices among disciplinary practitioners, with a particular focus on    early-career disciplinary         researchers and b) develop and promote best practices and standards for data stewardship. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim3" style="font-size:1.4em">Aim 3:</a> Support Equity and Improve Access </h3>
        <p> We will democratize science in a manner that recognizes broader concepts of data ownership and ethical data curation. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <figure>
          <img src="./images/rcn_aims.png" alt="goals" style="display:block" align="absbottom">
          <figcaption>The central aims, people, and outcomes that motivate this RCN. </figcaption>
        </figure>
       </div>
    </div>
</div>
