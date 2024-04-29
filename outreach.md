---
layout: default
title: Outreach
permalink: /outreach
---

<style>
  @media print, screen and (max-width:480px) {
   #heading-left {
      padding-bottom: 0%;
      }
}
  li {
  font-size:20px;
  color:#000;
  }
.collapse {
  display: none;
  top: 63px;
  z-index:10000;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  margin-bottom:5%;
}

.show_b {
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
  margin-bottom:4%;
  }
  
   .bttn:hover {
  background-color:#faf3e8;
  }

   .bttn:hover p {
  font-weight:bold;
  }
  
  .bttn:hover strong {
  font-weight:900;
  }
  
  
  strong {
  color:#ec970b;
  }
  
  .bttn_show {
  border: 2.5px solid #ec970b;
  background-color:#faf3e8;
  }

  .bttn_show p {
  font-weight:bold;
  }
  
  .bttn_show strong {
  font-weight:900;
  }
  .show_b {
  width:150%;
  }
  
 #cap {
  display:none;
  background-color: #fff;
  position: absolute;
  max-width:180px;
  border: 1px solid #ec970b;
  padding: 1%;
  margin-left: 2%;
  width:86%;
  z-index:10000;
  }
  
  #pima:hover #cap {
  display:block;
  }
  
  .read-more-content {
  background-color: #fff;
  }
  
  
  #heading-left {
  width:100%;
  position: relative;
  
  }
  
 @media print,screen and (max-width: 945px) {
  #heading-left {
  width: 100%;
  }
  }
  
    @media print,screen and (max-width: 761px) {
  #heading-left {
  width: 100%;
  }
  }
  
     @media print,screen and (max-width: 701px) {
  #heading-left {
  width: 100%;
  }
  }
  
     @media print,screen and (max-width: 761px) {
  #heading-left {
  width: 100%;
  }
  }
  
  
  @media print,screen and (max-width: 680px) {
  .read-more-content p {
  font-size: 0.15em;
  }
  }
  
  @media print, screen and (max-width: 720px) {
  .show_b {
  width:200%;
  }
  }

   @media print, screen and (max-width: 860px) {
  .show_b {
  width:95%;}
    
  }
  
   #main-text {
  width: 200%;
  position: relative;
  } 
  
  #care-des {
  width:100%;
  margin-left: -20%;
  }
  
 @media print, screen and (max-width: 1300px) {
  #main-text {
  width: 170%;
  } 
  }

  
 @media print, screen and (max-width: 1215px) {
    #care-des {
  width:100%;
  margin-left: -10%;
  }
  }
  
   @media print, screen and (max-width: 1180px) {
  #main-text {
  width: 150%;
  } 
  
    #care-des {
  width:100%;
  margin-left: -5%;
  }
  }
  
     @media print, screen and (max-width: 1089px) {
  #main-text {
  width: 130%;
  } 
  
    #care-des {
  width:100%;
  margin-left: 0%;
  }
  }
  
       @media print, screen and (max-width: 980px) {
  #main-text {
  width: 110%;
  } 
  }

         @media print, screen and (max-width: 890px) {
  #main-text {
  width: 100%;
  } 
  }



  </style>
<div class="text-block-main" style="display:grid;grid-template-columns: auto">
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);">Outreach & Education</h1>
      <p style="align-self:start;padding-top:10px;" id="describe"> Ethical Open Data Science: Moving from CARE Principles to Practice </p>
    </div>

  </div>
  <div class="text-block-right" style="display:grid;width:88%;padding-right:7%;padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>We will advance the implementation of CARE best practices at all stages of the research data life cycle.</p>
      <h2>Activities</h2>
        <button class="bttn" id="synth" onclick="Func_synth()">
          <div><p><strong>Implementing CARE practices in Databases</strong></p></div>
</button>
        <div class="collapse" id="readMore_synth">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>We will focus on two well-established open community data resources—Open Context and Neotoma—as  test cases for exploring how best to implement CARE practices in archaeological and paleoecological  datasets. CARE introduces a set of important technical requirements that need to be supported. For  example, data infrastructure needs to support Traditional Knowledge labels and notifications to help better express cultural aspects of data provenance and expectations for benefits sharing. Similarly, data infrastructure needs to be flexible enough to manage culturally specific systems of metadata documentation. These expanded and diversified sets of metadata needs will also need to be managed by curation workflows that inclusively represent stakeholder interests.</p>
            
<p>The exact form of implementation will vary among open data resources, and it is unlikely that a single solution will work for all. Hence, over the course of the symposia hackathons, webinars, and other activities, we will use Open Context and Neotoma as two representative instances of open community data resources in archaeology and paleoecology, with differing degrees of implementation of CARE principles and pre-existing relationships with Indigenous leaders and scholars. Symposia breakout sessions and hackathon  activities will help identify technical requirements to guide CARE principle-aligned improvements to Open Context and Neotoma, which can then serve as model examples for other data resources. 
 </p>
          </div>
        </div>
      <br>
     <button class="bttn" id="os-casestudy" onclick="Func_oscasestudy()">
          <div><p><strong>Doing Open Science Across Disparate Data Types</strong></p></div>
      </button>
        <div class="collapse" id="readMore_os-casestudy">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p> Quaternary and modern organismal  and environmental data can be linked by place and time, despite differing data types. For example, organismal occurrence data is typically georeferenced with a latitude and longitude, as well as both date of collection and, for non-modern collections, temporal age of the  specimen. Workflows to combine organismal and environmental data (both paleo and modern) are already being created by many different data practitioners, but many are either not reproducible or not formalized into a published and shareable pipeline. By leveraging existing tools  to access and create interoperable data, and methods already commonly used by data practitioners to link data sources by spatial region and temporal span, we will create a model open science workflow aimed at data practitioners within the broader Quaternary science community. Developing this case study and workflow will highlight potential interoperability issues among Quaternary and modern data resources and feed into Aim 1 interoperability work. Using this workflow, we can create a simple biology-motivated case study investigating macro-scale biodiversity change in relation to environmental and anthropogenic changes. </p>
          </div>
       </div>
  
      <br>
   
      </div>
    </div>

  </div>
</div>

<script>
function Func_synth() {
  document.getElementById("readMore_synth").classList.toggle("show_b");
  document.getElementById("synth").classList.toggle("bttn_show");
}

function Func_symp() {
  document.getElementById("readMore_symp").classList.toggle("show_b");
  document.getElementById("symp").classList.toggle("bttn_show");
}

  function Func_profs() {
  document.getElementById("readMore_profs").classList.toggle("show_b");
  document.getElementById("profs").classList.toggle("bttn_show");
}

  
function Func_oscasestudy() {
  document.getElementById("readMore_os-casestudy").classList.toggle("show_b");
  document.getElementById("os-casestudy").classList.toggle("bttn_show");
}

</script>
