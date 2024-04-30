---
layout: default
title: Improving Interoperability
permalink: /interoperability
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
  
  #title, #describe {
  width:100%;
  }
  
    @media print, screen and (max-width: 1070px) {
  #describe {
  width:100%;
  }
  }
  
      @media print, screen and (max-width: 1030px) {
  #describe {
  width:100%;
  }
  }
  
   @media print, screen and (max-width: 730px) {
  #describe {
  width:100%;
  }
  }
  
  
  @media print, screen and (max-width: 1055px) {
   #title {
  width:100%;
  }
  }
  
    @media print, screen and (max-width: 635px) {
   #title {
  width:100%;
  }
  }
  
    @media print, screen and (max-width: 435px) {
   #title, #describe {
  width:100%;
  }
  }
  
  #heading-image {
  width:100%;
  }
  
  #neo:hover #cap {
  display:block;
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
  
    @media print, screen and (max-width: 660px) {
  #heading-image {
  width:90%;}
  }
  
   #main-text {
  width: 200%;
  position: relative;
  } 
  
  #fair-des {
  width:100%;
  margin-left: -20%;
  }
  
 @media print, screen and (max-width: 1300px) {
  #main-text {
  width: 170%;
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
  width: 150%;
  } 
  
    #fair-des {
  width:100%;
  margin-left: -5%;
  }
  }
  
     @media print, screen and (max-width: 1089px) {
  #main-text {
  width: 130%;
  } 
  
    #fair-des {
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
<div class="text-block-main" style="display:grid;grid-template-columns: auto; margin-right:0px; width:100%;">
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 id="title" style="font-size:calc(20px + 3vw);">Improving Interoperability</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Engaging Early Career Researchers, Disciplinary Scientists, and Data Managers</p>
    </div>

  </div>
  <div class="text-block-right" style="display:grid;width:95%;padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>The Quaternary sciences have developed multiple mid-scale repositories containing large amounts of related but heterogeneously structured data. We must approach curation of this data from two perspectives. On the one hand, we must work with disciplinary scientists to train them in best practices for collecting and publishing data to support dissemination and reuse; on the other hand, we must also work with the data  managers to design best practices that facilitate data stewardship.</p>
      <h2>Activities</h2> 
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>An Informatics Landscape Analysis</strong></p></div>
</button>
        <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The aim of this analysis is to map the current Quaternary informatics landscape, evaluate current interoperability efforts, and recommend best practices going forward, with a focus on several widely used data resources spanning different domains. We will pay special attention to the power dynamics of these relationships: whose standards and best practices dominate, and whose are marginalized? </p>
            <p>We will evaluate 
              <ol>
              <li>the semantic  <i>coverage</i> of each repository (e.g. what data elements are captured by each repository, and what are the  specific meanings of those elements?) </li>
              <li>points of <i>convergence and conflict</i> between repositories (e.g. what data elements overlap and which are fundamentally mismatched?)</li>
              <li>the <i>completeness</i> of records within repositories, and</li>
              <li>points for further curatorial intervention—places where additional data curation could make records more accessible, interoperable, or ethical.</li></ol></p>
          </div>
        </div>
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>Creating Interoperable Data</strong></p></div>
      </button>
          <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Many legacy Quaternary datasets are found in specimen-curation repositories, like museums, with database structures designed to capture specimen-specific long-tail data and often curated decades past without regard to FAIR or CARE principles. This case study will focus on expanding FAIR data curation protocols from the ZooArchNet (ZAN) project to 
                <ol>
<li>link legacy museum-curated zooarcheological data across various community-curated data repositories, and</li>
                  <li>align with CARE guidelines and descendant  community priorities.</li></ol></p>
<p>ZAN has already created pathways to standardize, crosswalk and link zooarchaeological datasets across archaeological and biological repositories. In this case study, UF personnel will work with RCN informatics domain experts and repository data managers, in consultation with Indigenous stakeholders, to expand the ZAN protocols. Continued work on data standards alignments, Linked Open Data, and other intersectional methods will  be used to mobilize Darwin Core-enabled legacy zooarchaeological data from the Florida Museum curation database across multiple repositories.</p>
<p>Our work will be grounded in consultation with descendant community members and tribal authorities to ensure that their interests are represented in our decisions of how to integrate CARE principles within open data sharing. Our tribal collaborators will form an integral part of our use case activities, ensuring that any data sharing is culturally appropriate, ethical, and in support of tribal priorities involving the documentation and protection of environmental resources and cultural heritage. This effort will represent a proof-of-concept workflow and produce best-practice guidelines for such interdisciplinary, inter-repository FAIR and CARE open sharing of legacy curated data that will be disseminated via workshops for the archaeological and zooarchaeological communities.  
</p>
            </div>
      </div>
    <br>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Constituent Database Landing Pages</strong></p></div>
      </button>
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Increase transparency of Neotoma</p>

            </div>
      </div>
      <button class="bttn" id="year3" onclick="Func_year3()"> 
          <div><p>The <strong>Year 3 Webinar and Hackathon</strong> and guidance on <strong>data stewardship best practices</strong></p></div>
      </button>
      <div class="collapse" id="readMore_year3">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>Interoperability and reproducibility are only part of the open science puzzle. Repositories require trust and practitioners require skills to implement sustainable ethical open science practices. The focus in Year 3 is on solidifying the adoption of better data science and curation practices to support ethical open science in the future, and to preserve the critical role that small- and mid-scale data resources provide in the information architecture of the sciences. We will support the adoption of best practices through continued engagement with early career researchers, while re-engaging members within the Informatics  domain to address technical gaps identified through the Years 1 and 2 hackathon efforts. Year 3 activities  will also focus on software practices that can support trust in online data repositories, including OAuth systems, data versioning, JSON-LD serialization, APIs, and other technical architecture that is required to  properly support ethical open science. The hackathon will focus on implementation of software practices within community-curated data repositories, and follow-up webinars will focus on developing and refining documentation of best practices for  implementing these applications and tools within Quaternary community-curated data repositories.
</p>
          </div>
      </div>
    </div>
    </div>
  <!-- <div>
        <figure style="margin-right:0px;min-width:220px;" id="fair-des">
        <img src="./images/FAIR Diagram_v8.png" alt="FAIR Project Design" style="width:100%">
        <figcaption style="text-align:center;"></figcaption>
        </figure>
    </div> -->
  </div>
</div>

<script>
  function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
}


  function Func_casestudy() {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
}

function Func_y2web() {
  document.getElementById("readMore_y2-web").classList.toggle("show_b");
  document.getElementById("y2-web").classList.toggle("bttn_show");
}

function Func_oscasestudy() {
  document.getElementById("readMore_os-casestudy").classList.toggle("show_b");
  document.getElementById("os-casestudy").classList.toggle("bttn_show");
}

  function Func_pracs() {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");
}

   function Func_year3() {
  document.getElementById("readMore_year3").classList.toggle("show_b");
  document.getElementById("year3").classList.toggle("bttn_show");
}



</script>
