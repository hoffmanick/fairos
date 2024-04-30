---
layout: default
title: Community Building
permalink: /community
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
  <!-- width:150%; -->
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
  
  #quilter:hover #cap {
  display:block;
  }
    
  .read-more-content {
  background-color: #fff;
  }
  
  @media print,screen and (max-width: 680px) {
  .read-more-content p {
  font-size: 0.15em;
  }
  }
  
  @media print, screen and (max-width: 720px) {
  .show_b {
  <!-- width:200%; -->
  }
  }

   @media print, screen and (max-width: 860px) {
  .show_b {
  width:95%;}
  }

  
    #heading-image {
  <!-- width:120%; -->
  }
  
      @media print, screen and (max-width: 660px) {
  #heading-image {
  width:90%;}
  }
  
 #main-text {
  <!-- width: 200%; -->
  position: relative;
  } 
  
  #fair-des {
  width:100%;
  margin-left: -20%;
  }
  
 @media print, screen and (max-width: 1300px) {
  #main-text {
  <!-- width: 170%; -->
  } 
  }

  
 @media print, screen and (max-width: 1215px) {
    #fair-des {
  width:100%;
  margin-left: -10%;
  }
  }
  
   @media print, screen and (max-width: 1180px) {
  #main-text {
  <!-- width: 150%; -->
  } 
  
    #fair-des {
  width:100%;
  margin-left: -5%;
  }
  }
  
     @media print, screen and (max-width: 1089px) {
  #main-text {
  <!-- width: 130%; -->
  } 
  
    #fair-des {
  width:100%;
  margin-left: 0%;
  }
  }
  
       @media print, screen and (max-width: 980px) {
  #main-text {
  <!-- width: 110%; -->
  } 
  }

         @media print, screen and (max-width: 890px) {
  #main-text {
  width: 100%;
  } 
  }
  
  </style>
<div class="text-block-main" style="display:grid;grid-template-columns: auto;margin-right:0px;width:100%;">
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);">Community Building & Reflection</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Building Interconnected and Open Data Resources</p>
    </div>
  <!--  <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;max-width:300px;" id="quilter">
        <img src="./images/interoperable_quilt.png" alt="quilt" style="width:100%">
        <figcaption id="cap">Making systems interoperable is a kind of quilting. Image originally from Rocky Mountain Quilt Museum. Thomer and Rayburn, 2023: “A Patchwork of Data Systems”: Quilting as an Analytic Lens and Stabilizing Practice for Knowledge Infrastructures. <i>Science, Technology, & Human Values.</i></figcaption>
      </figure>
    </div> -->
  </div>
  <div class="text-block-right" style="display:grid; width:95%;padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>We will develop a network of data managers, research practitioners, disciplinary experts, and early career researchers focused on identifying gaps and mismatches among Quaternary data resources, in order to improve interoperability among them. We will particularly prioritize: <ul>
      <li>outreach to data managers and assessment of the current Quaternary informatics landscape,</li>
      <li>identifying areas for crosswalk development to resolve conflicts between existing ontologies and to help support the adoption of CARE aims,</li>
        <li>identifying points of connection between repositories, where the addition of related identifiers could help bridge silos, and</li> 
        <li>building on existing initiatives to make data resources more open and interconnected.</li></ul></p>
      <h2>Activities</h2> 
       <button class="bttn" id="symp" onclick="Func_symp()">
          <div><p><strong>Structured Self-Reflection</strong></p></div>
      </button>
        <div class="collapse" id="readMore_symp">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p> RCN affiliates are engaging in a deep-dive reflection about ethical open science, FAIR, and CARE within both our personal scientific practice and within the policies of our organizations. We expect that our answers to these questions will change over time. The purpose of this self-reflection is to gain an initial honest assessment of where we as practitioners and where our repositories are now in terms of FAIR and CARE. </p>
          </div>
       </div>
      <br>
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>Annual Symposia</strong></p></div>
</button>
        <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
     <p>All symposia will include activities specifically devoted to advancing FAIR and CARE principles, in order to  help set desired professional norms and provide examples of how CARE implementation can be advanced.  Symposia activities will emphasize the importance of CARE data principles at each stage of the research data lifecycle, from initial conceptualization of a project, to data collection and analysis, interpretation and  communication of results, and finally the long term curation and reuse of research data. In the early years  of our RCN activities, we will invite keynote speakers from Research Data Alliance, the Centre for Australian Biodiversity and Heritage (CABAH), and other organizations to provide model examples of advancing CARE, with breakout discussions on how to best advance CARE among participating open-data resources  and their networks of allied practitioners. In later years, we will review and discuss current efforts to begin  implementing CARE best practices in participating data resources.</p>
          </div>
        </div>
    <br>
        <button class="bttn" id="symp-hack" onclick="Func_symphack()">
          <div><p><strong>Webinar series</strong></p></div>
      </button>
        <div class="collapse" id="readMore_symp-hack">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>The primary audience for the webinar series and symposium hackathon is data managers, with close interaction with disciplinary practitioners and other members of the broader community. A series of four webinars will be held prior to the symposium hackathon, to ensure that data managers have a common understanding of key concepts and toolsets applicable to the process of developing interoperable systems. These webinars will include opportunities for structured discussion to support the Mapping the Landscape project, as well as help build relationships between participants prior to the symposium hackathon.</p>
              <p>Webinar topics will include 
                <ol>
<li>an overview of common data standards (e.g. DublinCore, Science on Schema, Geoscience Standard Names)</li> 
<li>how individuals can serialize their data formats to JSON-LD or other metadata schemes, and</li> 
<li>how to improve findability and interoperability through services such as DataCite, GeoCODEs  or other tools.</li></ol></p>

          </div>
       </div>
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>Reading Group</strong></p></div>
      </button>
          <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>We're reading some good essays about colonial legacies in data and other things.
</p>
            </div>
      </div>
      </div>
    </div>

  </div>
</div>

<script>
function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
}

function Func_symphack() {
  document.getElementById("readMore_symp-hack").classList.toggle("show_b");
  document.getElementById("symp-hack").classList.toggle("bttn_show");
}

  function Func_casestudy() {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
}

   function Func_guidelines() {
  document.getElementById("readMore_guidelines").classList.toggle("show_b");
  document.getElementById("guidelines").classList.toggle("bttn_show");
}

  function Func_symp() {
  document.getElementById("readMore_symp").classList.toggle("show_b");
  document.getElementById("symp").classList.toggle("bttn_show");
}




</script>