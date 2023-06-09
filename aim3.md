---
layout: default
title: Aim 3
permalink: /aim3
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
  background-color:#f0ddc0;
  }

   .bttn p:hover {
  font-weight:bold;
  }
  
  strong {
  color:white;
  }
  
  .bttn_show {
  border: 2.5px solid #ec970b;
  }

  .show_b {
  width:150%;
  }
  
 #cap {
  display:none;
  background-color: #f0d2a1;
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
  background-color: #f0d2a1;
  }
  
  
  #heading-left {
  width:250%;
  position: relative;
  
  }
  
 @media print,screen and (max-width: 945px) {
  #heading-left {
  width: 180%;
  }
  }
  
    @media print,screen and (max-width: 761px) {
  #heading-left {
  width: 130%;
  }
  }
  
     @media print,screen and (max-width: 701px) {
  #heading-left {
  width: 90%;
  }
  }
  
     @media print,screen and (max-width: 761px) {
  #heading-left {
  width: 130%;
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
  
<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, 280px);background-image:linear-gradient(to left, #f0d2a1, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);"> Aim 3: Support Equity and Improve Access </h1>
      <p style="align-self:start;padding-top:10px;" id="describe"> Ethical Open Data Science: Moving from CARE Principles to Practice </p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;align-self:center;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;max-width:305px;" id="pima">
        <img src="./images/pima.png" alt="Pima" style="width:100%">
        <figcaption id="cap">The 'Pima Indians Diabetes Data Set' is regularly used to train machine learning models, without the authorization of and without benefit to the Akimel O'odham community from which the data derives. Radin, 2017: 'Digital Natives': How Medical and Indigenous Histories Matter for Big Data. <i>Osiris.</i></figcaption>
      </figure>
    </div>
  </div>
  <div class="text-block-right" style="display:grid;grid-template-columns: repeat(auto-fit,375px);width:88%;padding-right:7%;padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>To advance the implementation of CARE best practices at all stages of the research data life cycle, we  have designed multiple overlapping efforts with clearly defined activities and deliverables.</p>
      <h2>Activities</h2>
        <button class="bttn" id="synth" onclick="Func_synth()">
          <div><p>The <strong>'Implementing CARE practices in Databases' case study</strong></p></div>
</button>
        <div class="collapse" id="readMore_synth">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>We will focus on two well-established open community data resources—Open Context and Neotoma—as  test cases for exploring how best to implement CARE practices in archaeological and paleoecological  datasets. CARE introduces a set of important technical requirements that need to be supported. For  example, data infrastructure needs to support Traditional Knowledge labels and notifications to help better express cultural aspects of data provenance and expectations for benefits sharing. Similarly, data infrastructure needs to be flexible enough to manage culturally specific systems of metadata documentation. These expanded and diversified sets of metadata needs will also need to be managed by curation workflows that inclusively represent stakeholder interests.</p>
            
<p>The exact form of implementation will vary among open data resources, and it is unlikely that a single solution will work for all. Hence, over the course of the symposia hackathons, webinars, and other activities, we will use Open Context and Neotoma as two representative instances of open community data resources in archaeology and paleoecology, with differing degrees of implementation of CARE principles and pre-existing relationships with Indigenous leaders and scholars. Symposia breakout sessions and hackathon  activities will help identify technical requirements to guide CARE principle-aligned improvements to Open Context and Neotoma, which can then serve as model examples for other data resources. 
 </p>
          </div>
        </div>
      <br>
        <button class="bttn" id="symp" onclick="Func_symp()">
          <div><p><strong>Annual plenary symposia</strong></p></div>
      </button>
        <div class="collapse" id="readMore_symp">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>All symposia will include activities specifically devoted to advancing FAIR and CARE principles, in order to  help set desired professional norms and provide examples of how CARE implementation can be advanced.  Symposia activities will emphasize the importance of CARE data principles at each stage of the research data lifecycle, from initial conceptualization of a project, to data collection and analysis, interpretation and  communication of results, and finally the long term curation and reuse of research data. In the early years  of our RCN activities, we will invite keynote speakers from Research Data Alliance, the Centre for Australian Biodiversity and Heritage (CABAH), and other organizations to provide model examples of advancing CARE, with breakout discussions on how to best advance CARE among participating open-data resources  and their networks of allied practitioners. In later years, we will review and discuss current efforts to begin  implementing CARE best practices in participating data resources.</p>
          </div>
       </div>
      <br>
          <button class="bttn" id="profs" onclick="Func_profs()"> 
            <div><p><strong>Professional development workshops</strong> focusing on training practitioners and early career researchers. </p></div>
      </button>
          <div class="collapse" id="readMore_profs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>In addition to the annual symposia, we plan to lead multiple, virtual, synchronous workshops that are devoted to the professional development of informaticists and early career researchers who are interested in learning about CARE and how best to translate principles to action. These workshops will be attended by RCN members as well as through open calls to the communities of paleo- and modern ecologists, environmental archaeologists, and paleoclimatologists, with early career researchers and members of descendant communities in particular encouraged to apply. Participants will be encouraged to do some reading and preparation in advance of each workshop, which will consist of short lectures and learning activities that contribute to the development of individual action plans for participants.</p>
<p>While early career researchers tend to think that working with data is important for them and their future careers, many believe that they lack both the comfort and training, especially around ethical practices, to do so. These workshops aim to provide this kind of training specifically for individuals who do not have access to similar resources through their own institutions. In this way, we will be able to expand knowledge around applying CARE to underserved communities, providing mentorship and support so that participants can develop skills that are critically important for their success. Moreover, we aim to publish our curriculum open access so that others can adopt and adapt it for other contexts and audiences, exponentially increasing the number of people this work reaches. </p>
            </div>
      </div>
      </div>
    </div>
    <div>
        <figure style="margin-right:0px;min-width:300px;" id="care-des">
        <img src="./images/CARE_diagram_v8.png" alt="CARE Project Design" style="width:100%">
        <figcaption style="text-align:center;"></figcaption>
        </figure>
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

</script>
