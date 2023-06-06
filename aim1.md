---
layout: default
title: Aim 1
permalink: /aim1
---

<style>
  @media print, screen and (max-width:480px) {
   #heading-left {
      padding-bottom: 0%;
      }
}
  
.collapse {
  display: none;
  top: 63px;
  z-index:10000;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  margin-bottom:5%;
}

.show {
  display: grid;
  grid-template-rows: auto;
  
}

  .bttn {
  background-color:transparent;
  cursor:pointer;
  border: 0;
  border-bottom:1px solid #ec970b;
  padding-top:1%;
  font-size:17px;
  text-align:left;
  }
  .bttn_show {
  border: 2.5px solid #ec970b;
  }

#clip {
  position: absolute;
  clip-path: inset(0 50px 0px 0);
  }
  </style>
<div class="text-block-main" style="display:grid;grid-template-columns: auto">
  
<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #f0d2a1, 90%, #97b779);padding:0;align-content:center;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:40px;"> Aim 1: Improve Interoperability and Reproducibility </h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Building Interconnected and Open Data Resources</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;" id="stakes">
        <img src="./images/fairos-stakeholders.jpg" alt="Stakeholders" style="width:100%">
        <figcaption>This image is relevant to aim 1 </figcaption>
      </figure>
    </div>
  </div>
  <div class="text-block-right" style="display:grid;grid-template-rows: auto auto;width:90%;padding-right:5%;padding-left:5%;">
    <h2>Overview</h2>
    <div>
      <p>We will develop a network of data managers, research practitioners, disciplinary experts, and early career researchers to  identify gaps and mismatches among Quaternary data resources, with the aim of improving interoperability among data resources. We will particularly prioritize: outreach to data managers and assessment of the current Quaternary informatics landscape; identifying areas for crosswalk development to resolve conflicts  between existing ontologies and to help support the adoption of CARE aims; identifying points of connection between repositories, where the addition of related identifiers could help bridge silos; and building on existing initiatives, such as Earth Science Information Partners’ Science on Schema to make data resources more open and interconnected.  </p>
      <p>Five primary activities form the core of focus: 
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p>Data manager outreach and an <strong>informatics landscape analysis</strong>, identifying gaps and opportunities for alignment in existing  infrastructures</p></div>
</button>
        <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The aim of this analysis is to map the current Quaternary informatics landscape, evaluate current interoperability efforts, and recommend best practices going forward. Webinar discussions and symposia hackathons will be used to  better understand how data managers are using metadata standards and curating data. We will additionally conduct a structured evaluation of three widely used data resources spanning different data domains: Global Biodiversity Information Facility (GBIF),  the Open Context archaeological repository, and Neotoma Paleoecology Database. This evaluation approach will be grounded in prior informatics research on  metadata crosswalking and integration. </p>
            <p>We will evaluate 
              <li>1) the semantic  <i>coverage</i> of each repository (e.g. what data elements are captured by each repository, and what are the  specific meanings of those elements?); </li>
              <li>2) points of <i>convergence and conflict</i> between repositories (e.g. what data elements overlap and which are fundamentally mismatched?);</li>
              <li> 3) the <i>completeness</i> of records within repositories; and finally,</li>
              <li>4) points for further curatorial intervention—places where additional data curation could make records more accessible or interoperable.</li></p>
          </div>
        </div>
        <li>A <strong>webinar series</strong> and a <strong>symposium hackathon</strong> to  build community between data managers and make progress on improving interoperability and data alignment across community-curated data repositories</li>
          <li>The <strong>“Creating Interoperable Data” case study</strong></li>
          <li>A coalescence of these efforts into <strong>guidelines for data alignment</strong> between repositories and domains</li>
 </p>
    </div>
  </div>
</div>

<script>
function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
}


</script>
