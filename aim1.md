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
  margin-bottom:4%;
  }
  .bttn_show {
  border: 2.5px solid #ec970b;
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
      <p>Five primary activities form the core of focus:</p> 
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p>Data manager outreach and an <strong>informatics landscape analysis</strong>, identifying gaps and opportunities for alignment in existing  infrastructures</p></div>
</button>
        <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The aim of this analysis is to map the current Quaternary informatics landscape, evaluate current interoperability efforts, and recommend best practices going forward. Webinar discussions and symposia hackathons will be used to  better understand how data managers are using metadata standards and curating data. We will additionally conduct a structured evaluation of three widely used data resources spanning different data domains: Global Biodiversity Information Facility (GBIF),  the Open Context archaeological repository, and Neotoma Paleoecology Database. This evaluation approach will be grounded in prior informatics research on  metadata crosswalking and integration. </p>
            <p>We will evaluate 
              <ol>
              <li>the semantic  <i>coverage</i> of each repository (e.g. what data elements are captured by each repository, and what are the  specific meanings of those elements?); </li>
              <li>points of <i>convergence and conflict</i> between repositories (e.g. what data elements overlap and which are fundamentally mismatched?);</li>
              <li>the <i>completeness</i> of records within repositories; and finally,</li>
              <li>points for further curatorial intervention—places where additional data curation could make records more accessible or interoperable.</li></ol></p>
          </div>
        </div>
        <button class="bttn" id="symp-hack" onclick="Func_symphack()">
          <div><p>A <strong>webinar series</strong> and a <strong>symposium hackathon</strong> to  build community between data managers and make progress on improving interoperability and data alignment across community-curated data repositories</p></div>
      </button>
        <div class="collapse" id="readMore_symp-hack">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>The primary audience for the webinar series and symposium hackathon is data managers, with close interaction with disciplinary practitioners and other members of the broader community. A series of four webinars will be held prior to the symposium hackathon, to ensure that data managers have a common understanding of key concepts and toolsets applicable to the process of developing interoperable systems. These webinars will include opportunities for structured discussion to support the Mapping the Landscape project, as well as help build relationships between participants prior to the symposium hackathon.</p>
              <p>Webinar topics will include 
                <ol>
<li>an overview of common data standards (e.g. DublinCore, Science on Schema, Geoscience Standard Names);</li> 
<li>how individuals can serialize their data formats to JSON-LD or other metadata schemes; and</li> 
<li>how to support improving Findability and Interoperability through services such as DataCite, GeoCODEs  or other tools.</li></ol></p>
            <p>The hackathon aims to accelerate development of the community of practice established  through the webinars—to learn about ourselves, the work we have done in the past and wish to do in the  future, and start a full assessment of existing open data science resources and opportunities for improved  integration. Development of the hackathon will draw from discussions in webinars and be focused on  implementing solutions, specifically using the identified case studies from across the project to anchor discussions. Two webinars will follow the symposium, designed to support work arising from the in-person meeting.  
</p>
          </div>
       </div>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p>The <strong>“Creating Interoperable Data” case study</strong></p></div>
      </button>
          <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Many legacy Quaternary datasets are found in specimen-curation repositories (e.g. museums) with database structures designed to capture specimen-specific long-tail data and often curated decades past without regard to FAIR or CARE principles. A guiding use case for this aim will focus on expanding FAIR data curation protocols from the ZooArchNet (ZAN) project to 
                <ol>
<li>propagate/link legacy museum-curated zooarcheological data across various community-curated data repositories, and</li>
                  <li>align with CARE guidelines and descendant  community priorities.</li></ol></p>
<p>ZAN has created pathways to standardize, crosswalk and link (using Linked Open Data protocols) zooarchaeological datasets across archaeological (with partner Open Context) and biological (VertNet/GBIF) repositories, including the implementation of a vital new Darwin Core Extension for the publication of chronometric age data for paleo/archaeological specimens.</p>
          
<p>In this case study, UF personnel will work with RCN informatics domain experts and repository data managers, in consultation with Indigenous stakeholders, to expand the ZAN protocols. Continued work on data standards alignments, Linked Open Data, and other intersectional methods will  be used to mobilize Darwin Core enabled legacy zooarchaeological data from the Florida Museum curation database across multiple repositories including: 
  <ol>
<li>Neotoma (to update existing legacy records with complete Florida Museum datasets including isotope data),</li>
<li>archaeological repositories Open Context and tDAR, and  extended specimen specific repositories such as CARD (for radiocarbon data), and</li>
    <li>FuTRES (for metric data).</li>
            </ol></p>
<p>Our work will be grounded in consultation with descendant community members and tribal authorities to ensure that their interests are represented in our decisions of how to integrate CARE principles within open data sharing. Our tribal collaborators will form an integral part of our use case activities, ensuring that any data sharing is culturally appropriate, ethical, and in support of tribal priorities involving the documentation and protection of environmental resources and cultural heritage. This effort will represent a proof-of-concept workflow and produce best-practice guidelines for such interdisciplinary, inter-repository FAIR and CARE open sharing of legacy curated data that will be disseminated via workshops for the archaeological and zooarchaeological communities.  
</p>
            </div>
      </div>
      <button class="bttn" id="guidelines" onclick="Func_guidelines()"> 
          <div><p>A coalescence of these efforts into <strong>guidelines for data alignment</strong> between repositories and domains</p></div>
      </button>
      <div class="collapse" id="readMore_guidelines">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>Data managers will draw on findings from the Mapping the Landscape effort, webinars, hackathon, and the case study to develop specific guidelines for alignment between Quaternary data resources. Unlike many crosswalks, we will focus on aligning repositories rather than individual datasets, and will center the specific integration needs of the Quaternary community. Likely outcomes will include best practices for setting up repository APIs or  other access points; crosswalks between repository schemas; guidance for the implementation and use of  external APIs, such as ORCID, CrossRef, and DataCite, to help manage links to external data; and the use of Science on Schema or other external ontologies for reporting data.  </p>
          </div>
      </div>
    </div>
  </div>
</div>

<script>
function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
}

function Func_symphack() {
  document.getElementById("readMore_symp-hack").classList.toggle("show");
  document.getElementById("symp-hack").classList.toggle("bttn_show");
}

  function Func_casestudy() {
  document.getElementById("readMore_case-study").classList.toggle("show");
  document.getElementById("case-study").classList.toggle("bttn_show");
}

   function Func_guidelines() {
  document.getElementById("readMore_guidelines").classList.toggle("show");
  document.getElementById("guidelines").classList.toggle("bttn_show");
}



</script>
