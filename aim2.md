---
layout: default
title: Aim 2
permalink: /aim2
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
  position: fixed;
  max-width:180px;
  right:1%;
  border: 1px solid #ec970b;
  padding: 1%;
  margin-left: 2%;
  width:86%;
  bottom:1%;
  }
  
  #heading-image {
  width:120%;
  }
  
  #neo:hover #cap {
  display:block;
  }
  
  @media print, screen and (max-width: 720px) {
  .show_b {
  width:200%;
  }
  }

      @media print, screen and (max-width: 580px) {
  #cap {
  left: unset;
  right: 1%;
  bottom: 1%;
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

  </style>
<div class="text-block-main" style="display:grid;grid-template-columns: auto; margin-right:0px; width:100%;">
  
<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit,280px);background-image:linear-gradient(to left, #f0d2a1, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);"> Aim 2: Enable FAIR Data Curation and Stewardship </h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Engaging Practitioners: Early Career Researchers, Disciplinary Scientists, and Data Managers</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; align-self:center;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;max-width:500px;" id="neo">
        <img src="./images/neotoma_ecosystem-transp.png" alt="neotoma-eco" style="width:100%">
        <figcaption id="cap">Neotoma's data ecosystem exemplifies the relationships between data managers and disciplinary practitioners in the Quaternary community. Williams, Grimm, Blois et al, 2018: The Neotoma Paleoecology Database, a multiproxy international, community-curated data resource.<i>Quaternary Research.</i></figcaption>
      </figure>
    </div>
  </div>
  <div class="text-block-right" style="display:grid;grid-template-columns: repeat(auto-fit, 400px);width:95%;padding-left:5%;justify-content:space-evenly;">
    <div>
    <h2>Overview</h2>
    <div>
      <p>As long-tail data disciplines, the Quaternary sciences have developed multiple mid-scale repositories containing large amounts of related but heterogeneously structured data. We must approach curation of this data—and data curation training—from two perspectives. On the one hand, we must work with disciplinary scientists to train them in best practices for collecting and publishing data to support dissemination and reuse; on the other hand, we must also work with the data  managers to design schema- and system-level best practices that facilitate data stewardship.</p>
      <h2>Activities</h2> 
        <button class="bttn" id="y2-web" onclick="Func_y2web()">
            <div><p>The <strong>Year 2 Webinar and Hackathon</strong></p></div>
</button>
        <div class="collapse" id="readMore_y2-web">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The Year 2 hackathon will be focused around science-driven use cases for community-curated data repository alignmen and will be preceded by a series of four webinars, introducing the early career researchers to the participating community-curated data repositories and to tools and approaches for data alignment. All participants will also be exposed to basic principles of software development through the use of adapted education modules, providing an opportunity to improve skills and to ensure all participants are able to engage fully in the workshop. Webinars following the hackathon will enable ongoing work, keep early career researchers engaged after the symposium, and support the resolution of any ongoing difficulties as participants return to their home institutions. </p>
          </div>
        </div>
    <br>
        <button class="bttn" id="os-casestudy" onclick="Func_oscasestudy()">
          <div><p>The <strong>‘Doing Open Science Across Disparate Data Types’ case study</strong></p></div>
      </button>
        <div class="collapse" id="readMore_os-casestudy">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p> Quaternary and modern organismal  and environmental data can be linked by place and time, despite differing data types. For example, organismal occurrence data is typically georeferenced with a latitude and longitude, as well as both date of collection and, for non-modern collections, temporal age of the  specimen. Workflows to combine organismal and environmental data (both paleo and modern) are already being created by many different data practitioners, but many are either not reproducible or not formalized into a published and shareable pipeline. By leveraging existing tools  to access and create interoperable data, and methods already commonly used by data practitioners to link data sources by spatial region and temporal span, we will create a model open science workflow aimed at data practitioners within the broader Quaternary science community. Developing this case study and workflow will highlight potential interoperability issues among Quaternary and modern data resources and feed into Aim 1 interoperability work. Using this workflow, we can create a simple biology-motivated case study investigating macro-scale biodiversity change in relation to environmental and anthropogenic changes. </p>
          </div>
       </div>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Community-Curated Data Repository guidance</strong> aimed at data contributors and <strong>workshops at disciplinary conferences</strong></p></div>
      </button>
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Given the complexity of data resources within our disciplinary communities, a key need is guidance aimed at data generators on the set of options for data curation within different disciplinary communities. Early career researchers will also be engaged in data curation, and one outcome of their activities will be documentation of best practices to support the onboarding of data. This documentation may include
                <ul>
                  <li>a resource describing the scope of data repositories amongst the community,</li> 
                  <li>goals and aims of different community-curated data repositories,</li>
                    <li>types of data and formats accepted by community-curated data repositories, and </li> 
                  <li>checklists to facilitate ease of use.</li>
              </ul></p>
<p>The adoption of ethical open science principles depends not just on technical advances but also on establishing a culture of openness, literacy, and trust in FAIR and CARE principles. In order to disseminate ethical and open curatorial practices amongst the broader community, we will lead and facilitate training and outreach workshops at professional society meetings. To do this, we will convert the various best practices documentation into training videos and other introductory resources aimed at the core disciplinary practitioner communities. </p>
            </div>
      </div>
      <button class="bttn" id="year3" onclick="Func_year3()"> 
          <div><p>The <strong>Year 3 Webinar and Hackathon</strong> and guidance on <strong>data stewardship best practices</strong></p></div>
      </button>
      <div class="collapse" id="readMore_year3">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>Interoperability and reproducibility are only part of the FAIROS puzzle. Repositories require trust and practitioners require skills to implement sustainable ethical open science practices. The focus in Year 3 is on solidifying the adoption of better data science and curation practices 1) to support ethical open science in the future, and 2) to preserve the critical role that small- and mid-scale data resources provide in the information architecture of the sciences. We will support the adoption of best practices through continued engagement with early career researchers, while re-engaging members within the Informatics  domain to address technical gaps identified through the Years 1 and 2 hackathon efforts. Year 3 activities  will also focus on software practices that can support trust in online data repositories, including OAuth systems, data versioning, JSON-LD serialization, APIs, and other technical architecture that is required to  properly support ethical open science. The hackathon will focus on implementation of software practices within community-curated data repositories, and follow-up webinars will focus on developing and refining documentation of best practices for  implementing these applications and tools within Quaternary community-curated data repositories.
</p>
          </div>
      </div>
    </div>
    </div>
  <div>
        <figure style="margin-left:0px;margin-right:0px;min-width:220px;" id="stakes">
        <img src="./images/FAIR_Diagram_v5.png" alt="FAIR Project Design" style="width:100%">
        <figcaption style="text-align:center;"></figcaption>
        </figure>
    </div>
  </div>
</div>

<script>
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
