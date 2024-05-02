---
layout: default
title: research
permalink: /research
---
<style>

  #j {
    display: none;
  }

  
  .abtext2 {
    margin-left: 5%;
    border: 2px solid black;
    margin-right: 5%;
    width: 90%;
  }
  .toggler {
    display:block;
  }
  h4 {
  color:black;
  }

  .abtext {
    width: 90%;
    margin-left: 5%;
    border: 2px solid black;
    max-width: 200px;
  }
  #page {
  width:900px;
  display: grid;
 /*    margin-left: 14%;
    margin-right: 7%;
 width: 90%; */
  height: 1100px;
  grid-template-areas:
    "h h h h"
    "e d d c"
    "e d d c"
    "a f g b";
grid-template-rows: 0.1fr 0.1fr 500px 200px;
  grid-template-columns: 200px calc(100px + 10vw) calc(100px + 10vw) 200px; 
}

  div.abtext p {
    font-size: 15px;
  }

  .abtext h4 {
    margin-bottom: 0px;
    margin-top: 0px;

    
  }
  #comtext {
    background-color: #93c57e;
    width:100%;
    position:relative;
    top: -250%;
    left: -20%;
  }
  #interoptext {
    background-color: #738995;
    width: 100%;
    position:relative;
    top: -250%;
/*    left: 20%; */


  }

  #repotext {
    background-color: #46bec6;
    width:100%;
    position:relative;
    top: calc(-150% + 20vw);
    left: -8%;
  }

    #outreachtext {
    background-color: #ff9b01;
    position: relative;
    width: 100%;
    top: calc(-150% + 20vw);
    left: 8%;

  }

   #interoptext2 {
    background-color: #738995;

    position:relative;
/*    top: -250%;
    left: 20%; */


  }
   #comtext2 {
    background-color: #93c57e;
    position:relative;
    /*top: -250%;
    left: -20%;*/
  }
  #repotext2 {
    background-color: #46bec6;
    position:relative;
    height: calc(305px - 20vw);
   /* top: calc(-150% + 20vw);
    left: -8%; */
  }

    #outreachtext2 {
    background-color: #ff9b01;
    position: relative;
    /*top: calc(-150% + 20vw);
    left: 8%;*/

  }
      #interoptext strong, #repotext strong, #outreachtext strong, #comtext strong {
     display: none;
   }

  #i {
    grid-area: i;
    display: none;
  }
#a {
  grid-area: a;
 /* background-color: #8ca0ff; */
}

#b {
  grid-area: b;
 /* background-color: #ffa08c; */
}

#c  {
  grid-area: c;
/*  background-color: #ffff64; */
}

#d  {
  grid-area: d;
/*  background-color: #8cffa0; */
  text-align:center;
  align-content:center;
}

#e  {
  grid-area: e;
/*  background-color: #8ca2d0; */
}

  #h {
    grid-area: h;
  }

#f  {
  grid-area: f;
/*  background-color: #2ca2d0; */
}

#g  {
  grid-area: g;
/*  background-color: rgb(100,100,100); */
}


.begin {
  display:none;
}
  .begin2 {
  display:none;
}
  
div.text-block-main {
  display: grid;
  grid-template-rows: auto auto auto;
  margin-right:0px;
  padding-bottom:0px;
  background: #fff;
  }
div.text-block-right {
  margin-right:0px;
  padding-right:0px;
  width:100%;
  padding-left:0px;
  }
#stakes {
  margin-left: 0px;
  margin-right: 0px;
  }
  h3 {
  color: #000;
  }
  
  #aimses {
  /**
   * User input values.
   */
  --grid-layout-gap: 10px;
  --grid-column-count: 3;
  --grid-item--min-width: 220px;

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

 @media print, screen and (max-width: 900px) {
   #j {
     display:block;
   }
   #page {
     width: 100%;
     height: auto;
     grid-template-columns: 1fr 10px 10px 1fr;
     grid-template-rows: 0.1fr 0fr 0.1fr 1fr;
     grid-template-areas: 
       "h h h h"
       "j j j j"
       "j j j j"
       "i i i i";
   }

   #i {
     display: grid;
   }

   #d {
     display: none;
   }

   #a, #b, #f, #g, #e, #c {
     display: none;
   }
   
 }
  
 @media print, screen and (max-width: 1280px) {
    #repotext, #outreachtext {
      top: calc(-120% + 20vw);
    }

 /*   #interoptext strong, #repotext strong, #outreachtext strong, #comtext strong {
     display: inline;
   }

   #interoptext p, #repotext p, #outreachtext p, #comtext p {
     display: none;
   } */
  #stakes, #describe {
    width:200px;
     } 
  #headingblock {
    justify-content: left;
    justify-items: center;
     }
  #heading-left, #heading-image, #stakes {
    justify-content: left;
    /* justify-items: center; */
    justify-self: center;
   }
  #heading-image {
    padding-top:0px;
   }
  
  #stakes {
  text-align: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
   }
  #heading-left {
  padding-bottom:0px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  }
  }


  
/* @media print, screen and (max-width: 490px) {
   
   #interoptext, #repotext, #outreachtext, #comtext {
     display: none;
   }

   #page {
     height: 400px;
     grid-template-rows: 0fr 10fr 10fr 0fr;
     grid-template-columns: 0fr 10fr 10fr 0fr;
   }
 } */
</style>




<div class="text-block-main" style="display:grid;grid-template-rows:auto auto;margin:0;padding-left:0;width:100%;" id="block1">
  <div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:40px auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);align-self:start;">Our Work</h1>
      <p style="align-self:start;padding-top:10px;margin-top:3%;" id="describe">We aim to improve data infrastructure for the Quaternary scientific community.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/rcn_aims-trans.png" alt="Stakeholders" style="width=100%;">
       <!-- <figcaption>The sets of lead and affiliated data resources involved in this RCN. </figcaption> -->
      </figure>
    </div>
  </div>

  
  <div class="text-block-right" style="display:flex;flex-direction: row;flex-wrap:wrap;background-color:white;padding:0px;justify-content:center;" id="meatblock">

    
    <div class="text-block-right" style="max-width:300px;display:grid;justify-content:space-around;padding-top:17px;margin-right:0px;padding-left:0%;padding-right:4.5%;width:91%;grid-template-columns:auto;" id="aimses">
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid                #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="{{site.baseurl}}/aim1" style="font-size:1.4em">Aim 1: Improve Interoperability and Reproducibility</a></h3>
        <p style="text-align:center;"> We will develop guidance for interoperability and reproducibility among Quaternary community-curated data resources and
        promote adoption of broader and more equitable metadata standards. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="{{site.baseurl}}/aim2" style="font-size:1.4em">Aim 2:  Advance Data Curation and Stewardship</a></h3>
        <p style="text-align:center;">  We will promote better data science and curation practices among disciplinary practitioners, with a particular focus on early-career researchers, and develop and promote best practices and standards for ethical data stewardship. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="{{site.baseurl}}/aim3" style="font-size:1.4em">Aim 3: Support Equity and Improve Access</a></h3>
        <p style="text-align:center;"> We will democratize science in a manner that recognizes broader concepts of data ownership and ethical data curation. </p>
      </div>
    </div>


<!-- max-width:calc(200px + 35vw);-->
    <div id="page">

  
  <div id='c'></div>
  
  <div id='d'>
   <img src="./images/eos_circle.png" alt="circle" style="width:calc(200px + 20vw);max-width:750px;z-index:1; position:relative;" usemap="#image-map"></div>
<map name="image-map">
    <area target="_blank" style="cursor:pointer;" alt="community" title="community" coords="7,190,194,189,196,5,145,13,115,23,91,36,60,62,32,102,16,139,10,165,7,176" shape="poly" onclick="func_community()">
    <area target="_blank" style="cursor:pointer;" alt="repo governance" title="repo governance" coords="5,199,7,223,7,241,12,258,17,272,24,285,34,297,44,316,61,333,73,341,83,353,96,357,113,366,132,376,151,383,169,384,187,384,188,196" shape="poly" onclick="func_repogov()">
    <area target="_blank" style="cursor:pointer;" alt="outreach" title="outreach" coords="195,195,195,380,223,384,249,375,276,366,296,358,312,347,327,333,342,317,359,293,371,261,376,244,383,215,383,197" shape="poly" onclick="func_out()">
    <area target="_blank" style="cursor:pointer;" alt="interoperability" title="interoperability" coords="199,7,198,181,197,188,383,189,383,159,375,125,357,89,333,61,311,41,279,20,238,5" shape="poly" onclick="func_interop()">
</map>

<div id='j' style="justify-self:center;">
   <img src="./images/eos_circle.png" alt="circle" style="width:calc(200px + 20vw);max-width:750px;z-index:1; position:relative;" usemap="#image-map2"></div>
<map name="image-map2">
    <area target="_blank" style="cursor:pointer;" alt="community" title="community" coords="7,190,194,189,196,5,145,13,115,23,91,36,60,62,32,102,16,139,10,165,7,176" shape="poly" onclick="func_community2()">
    <area target="_blank" style="cursor:pointer;" alt="repo governance" title="repo governance" coords="5,199,7,223,7,241,12,258,17,272,24,285,34,297,44,316,61,333,73,341,83,353,96,357,113,366,132,376,151,383,169,384,187,384,188,196" shape="poly" onclick="func_repogov2()">
    <area target="_blank" style="cursor:pointer;" alt="outreach" title="outreach" coords="195,195,195,380,223,384,249,375,276,366,296,358,312,347,327,333,342,317,359,293,371,261,376,244,383,215,383,197" shape="poly" onclick="func_out2()">
    <area target="_blank" style="cursor:pointer;" alt="interoperability" title="interoperability" coords="199,7,198,181,197,188,383,189,383,159,375,125,357,89,333,61,311,41,279,20,238,5" shape="poly" onclick="func_interop2()">
</map>
   
  <div id='e'></div>
    <div id="a">
  <div class="abtext begin" id="comtext">
    <h4>Annual Symposia<strong>.</strong></h4>
    <p>We are meeting yearly in person to think together about implementing ethical open science in our data ecosystems, furthering all our aims.</p>
    <h4>Ethical Open Science Self-Reflection Survey<strong>.</strong></h4>
    <p>Our self-reflection survey on our personal and institutional relationships to FAIR, CARE, and EOS have been guiding our subsequent actions.</p>
    <h4>Webinar Series<strong>.</strong></h4>
    <p>We provide a forum for experts in informatics and ethics to share their work with us. Click <a href="https://hoffmanick.github.io/fairos/webinarview" target="_blank">here</a> for more info.</p>
    <h4>Reading Group<strong>.</strong></h4>
    <p>We meet monthly to discuss selections from the literature on the political economy of data.</p>
  </div></div>
  
  <div id = 'b'>
    <div class="abtext begin" id="interoptext">
    <h4>Mapping the Interoperability Landscape<strong>.</strong></h4>
      <p>We are interviewing data managers and disciplinary practitioners to map the ways they interoperate data, suprporting aims 1 and 3.</p>
    <h4>Case Study: Linking data across repositories<strong>.</strong></h4>
      <p>Using our focal repositories as a case study, we are developing a workflow to enhance data linkages, furthering all our aims.</p>
    <h4>Neotoma constituent database landing pages<strong>.</strong></h4>
      <p>These pages offer greater transparency for users of Neotoma's data, a facet of aims 2 and 3.</p>
  </div></div>
  <div id='f'>
    <div class="abtext begin" id="repotext">
    <h4>Case studies: Neotoma, Open Context, Florida Museum<strong>.</strong></h4>
      <p>We are using our focal repositories as case studies for improving data governance and bolstering our commitment to Indigenous data sovereignty.</p>
  </div></div>
  
  <div id='g'>
      <div class="abtext begin" id="outreachtext">
        <h4>ECR Projects: Doing Ethical Open Science Across Disparate Data Types<strong>.</strong></h4>
        <p>We are working with early career researchers to.... ? </p>
        <h4>FAIR/CARE educational materials<strong>.</strong></h4>
        <p>We are producing material for undergraduates studying data science and ecology to introduce them to principles of ethical open data management.</p>
        <h4>Data repository decision tree<strong>.</strong></h4>
        <p>We are supporting early career researchers by providing them with a resource to guide their choice of repository for data or specimen upload.</p>
      </div>
    </div>

    <div id='h'>
      <div>
        <h2>RCN Activities</h2>
        <p>Our RCN Aims have so far coalesced around the following domains of activity. 
        Click any sector of the circle below to learn more about that domain.</p>
      </div>
    </div>

    <div id="i">

        <div class="abtext2 begin2" id="interoptext2">
    <h4>Mapping the Interoperability Landscape<strong>.</strong></h4>
      <p>We are interviewing data managers and disciplinary practitioners to map the ways they interoperate data, suprporting aims 1 and 3.</p>
    <h4>Case Study: Linking data across repositories<strong>.</strong></h4>
      <p>Using our focal repositories as a case study, we are developing a workflow to enhance data linkages, furthering all our aims.</p>
    <h4>Neotoma constituent database landing pages<strong>.</strong></h4>
      <p>These pages offer greater transparency for users of Neotoma's data, a facet of aims 2 and 3.</p>
  </div>
    
  <div class="abtext2 begin2" id="comtext2">
    <h4>Annual Symposia<strong>.</strong></h4>
    <p>We are meeting yearly in person to think together about implementing ethical open science in our data ecosystems, furthering all our aims.</p>
    <h4>Ethical Open Science Self-Reflection Survey<strong>.</strong></h4>
    <p>Our self-reflection survey on our personal and institutional relationships to FAIR, CARE, and EOS have been guiding our subsequent actions.</p>
    <h4>Webinar Series<strong>.</strong></h4>
    <p>We provide a forum for experts in informatics and ethics to share their work with us. Click <a href="https://hoffmanick.github.io/fairos/webinarview" target="_blank">here</a> for more info.</p>
    <h4>Reading Group<strong>.</strong></h4>
    <p>We meet monthly to discuss selections from the literature on the political economy of data.</p>
  </div>
  
      <div class="abtext2 begin2" id="outreachtext2">
        <h4>ECR Projects: Doing Ethical Open Science Across Disparate Data Types<strong>.</strong></h4>
        <p>We are working with early career researchers to.... ? </p>
        <h4>FAIR/CARE educational materials<strong>.</strong></h4>
        <p>We are producing material for undergraduates studying data science and ecology to introduce them to principles of ethical open data management.</p>
        <h4>Data repository decision tree<strong>.</strong></h4>
        <p>We are supporting early career researchers by providing them with a resource to guide their choice of repository for data or specimen upload.</p>
      </div>

        <div class="abtext2 begin2" id="repotext2">
    <h4>Case studies: Neotoma, Open Context, Florida Museum<strong>.</strong></h4>
      <p>We are using our focal repositories as case studies for improving data governance and bolstering our commitment to Indigenous data sovereignty.</p>
  </div>
    </div>
  
</div>


</div>



<script>

  !function(){"use strict";function r(){function e(){var r={width:u.width/u.naturalWidth,height:u.height/u.naturalHeight},a={width:parseInt(window.getComputedStyle(u,null).getPropertyValue("padding-left"),10),height:parseInt(window.getComputedStyle(u,null).getPropertyValue("padding-top"),10)};i.forEach(function(e,t){var n=0;o[t].coords=e.split(",").map(function(e){var t=1==(n=1-n)?"width":"height";return a[t]+Math.floor(Number(e)*r[t])}).join(",")})}function t(e){return e.coords.replace(/ *, */g,",").replace(/ +/g,",")}function n(){clearTimeout(d),d=setTimeout(e,250)}function r(e){return document.querySelector('img[usemap="'+e+'"]')}var a=this,o=null,i=null,u=null,d=null;"function"!=typeof a._resize?(o=a.getElementsByTagName("area"),i=Array.prototype.map.call(o,t),u=r("#"+a.name)||r(a.name),a._resize=e,u.addEventListener("load",e,!1),window.addEventListener("focus",e,!1),window.addEventListener("resize",n,!1),window.addEventListener("readystatechange",e,!1),document.addEventListener("fullscreenchange",e,!1),u.width===u.naturalWidth&&u.height===u.naturalHeight||e()):a._resize()}function e(){function t(e){e&&(!function(e){if(!e.tagName)throw new TypeError("Object is not a valid DOM element");if("MAP"!==e.tagName.toUpperCase())throw new TypeError("Expected <MAP> tag, found <"+e.tagName+">.")}(e),r.call(e),n.push(e))}var n;return function(e){switch(n=[],typeof e){case"undefined":case"string":Array.prototype.forEach.call(document.querySelectorAll(e||"map"),t);break;case"object":t(e);break;default:throw new TypeError("Unexpected data type ("+typeof e+").")}return n}}"function"==typeof define&&define.amd?define([],e):"object"==typeof module&&"object"==typeof module.exports?module.exports=e():window.imageMapResize=e(),"jQuery"in window&&(window.jQuery.fn.imageMapResize=function(){return this.filter("map").each(r).end()})}();

imageMapResize();
  
</script>


<script>
function func_community() {
  document.getElementById("comtext").classList.toggle("toggler");
  document.getElementById("comtext").classList.toggle("begin");

}

function func_repogov() {
  document.getElementById("repotext").classList.toggle("toggler");
    document.getElementById("repotext").classList.toggle("begin");

}

  function func_out() {
  document.getElementById("outreachtext").classList.toggle("toggler");
      document.getElementById("outreachtext").classList.toggle("begin");

}

   function func_out2() {
  document.getElementById("outreachtext2").classList.toggle("toggler");
      document.getElementById("outreachtext2").classList.toggle("begin2");

     if (document.getElementById("repotext2").classList.contains("toggler")) {
       document.getElementById("repotext2").classList.toggle("toggler");
       document.getElementById("repotext2").classList.toggle("begin2");
     }

          if (document.getElementById("comtext2").classList.contains("toggler")) {
       document.getElementById("comtext2").classList.toggle("toggler");
       document.getElementById("comtext2").classList.toggle("begin2");
     }

        if (document.getElementById("interoptext2").classList.contains("toggler")) {
       document.getElementById("interoptext2").classList.toggle("toggler");
       document.getElementById("interoptext2").classList.toggle("begin2");
     }
}

   function func_community2() {
  document.getElementById("comtext2").classList.toggle("toggler");
      document.getElementById("comtext2").classList.toggle("begin2");

     if (document.getElementById("repotext2").classList.contains("toggler")) {
       document.getElementById("repotext2").classList.toggle("toggler");
       document.getElementById("repotext2").classList.toggle("begin2");
     }

          if (document.getElementById("outreachtext2").classList.contains("toggler")) {
       document.getElementById("outreachtext2").classList.toggle("toggler");
       document.getElementById("outreachtext2").classList.toggle("begin2");
     }

        if (document.getElementById("interoptext2").classList.contains("toggler")) {
       document.getElementById("interoptext2").classList.toggle("toggler");
       document.getElementById("interoptext2").classList.toggle("begin2");
     }

}


  
     function func_repogov2() {
  document.getElementById("repotext2").classList.toggle("toggler");
      document.getElementById("repotext2").classList.toggle("begin2");

     if (document.getElementById("outreachtext2").classList.contains("toggler")) {
       document.getElementById("outreachtext2").classList.toggle("toggler");
       document.getElementById("outreachtext2").classList.toggle("begin2");
     }

                 if (document.getElementById("comtext2").classList.contains("toggler")) {
       document.getElementById("comtext2").classList.toggle("toggler");
       document.getElementById("comtext2").classList.toggle("begin2");
     }

                 if (document.getElementById("interoptext2").classList.contains("toggler")) {
       document.getElementById("interoptext2").classList.toggle("toggler");
       document.getElementById("interoptext2").classList.toggle("begin2");
     }

}

     function func_interop2() {
  document.getElementById("interoptext2").classList.toggle("toggler");
      document.getElementById("interoptext2").classList.toggle("begin2");

     if (document.getElementById("outreachtext2").classList.contains("toggler")) {
       document.getElementById("outreachtext2").classList.toggle("toggler");
       document.getElementById("outreachtext2").classList.toggle("begin2");
     }

                 if (document.getElementById("comtext2").classList.contains("toggler")) {
       document.getElementById("comtext2").classList.toggle("toggler");
       document.getElementById("comtext2").classList.toggle("begin2");
     }

        if (document.getElementById("repotext2").classList.contains("toggler")) {
       document.getElementById("repotext2").classList.toggle("toggler");
       document.getElementById("repotext2").classList.toggle("begin2");
     }

}

   function func_interop() {
  document.getElementById("interoptext").classList.toggle("toggler");
       document.getElementById("interoptext").classList.toggle("begin");

}



</script>
