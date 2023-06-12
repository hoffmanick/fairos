---
layout: default
title: "Glossary"
permalink: /glossary
---

<style>
  
div.text-block-main {
  padding-left: 5%
  }

  #heading-image {
  padding-top: 0px;
  padding-bottom: 0px;
  margin-left:0px;
  margin-right:0px;
  align-self:center;
  }
  
  #scroll {
  margin-left:0px;
  margin-right:0px;
  }
  
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

  .bttn:hover p {
  font-weight:bold;
  }
  
  .bttn:hover strong {
  font-weight:900;
  }
  
  strong {
  color:white;
  }
  
  .bttn_show {
  border: 2.5px solid #ec970b;
  background-color:#f0ddc0;
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
  
  
  #title, #describe {
  width:212%;
  }
  
    @media print, screen and (max-width: 1070px) {
  #describe {
  width:190%;
  }
  }
  
      @media print, screen and (max-width: 1030px) {
  #describe {
  width:135%;
  }
  }
  
   @media print, screen and (max-width: 730px) {
  #describe {
  width:115%;
  }
  }
  
  
  @media print, screen and (max-width: 1055px) {
   #title {
  width:190%;
  }
  }
  
    @media print, screen and (max-width: 635px) {
   #title {
  width:135%;
  }
  }
  
    @media print, screen and (max-width: 435px) {
   #title, #describe {
  width:100%;
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



<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #f0d2a1, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);align-self:start;">Glossary</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Learn more about our key words.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end; margin-right:5%; margin-left: 5%; width: 90%;max-width:250px;" id="heading-image">
      <figure id="scroll">
        <img src="./images/scroll-trans.png" alt="scroll" style="width=100%;max-width:250px;">
        <figcaption></figcaption>
      </figure>
    </div>
  </div>
  
  
  
<div class="text-block-right" style="display:grid;grid-template-columns: repeat(auto-fit, 400px);width:95%;padding-left:5%;justify-content:space-between;">
    <div id="main-text">
      <h2>Activities</h2> 
        <button class="bttn" id="care" onclick="Func_care()">
            <div><p><strong>The CARE Principles</strong></p></div>
</button>
        <div class="collapse" id="readMore_care">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The CARE principles (Collective Benefit, Authority, Responsibility and Ethics) were formulated by Stephanie Carroll and ... in collaboration with ... to ...</p>
          </div>
        </div>
    <br>
        <button class="bttn" id="fair" onclick="Func_fair()">
          <div><p><strong>The FAIR Principles</strong></p></div>
      </button>
        <div class="collapse" id="readMore_fair">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>The FAIR principles (Findable, Accessible, Interoperable, and Reusable) were... to... </p>
          </div>
       </div>
        <br>
          <button class="bttn" id="quat" onclick="Func_quat()"> 
            <div><p><strong>The Quaternary Research Community</strong></p></div>
      </button>
          <div class="collapse" id="readMore_quat">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>The Quaternary research community is a network of scientists and data managers who study the archaeology, climate, and ecology of the Quaternary period, 
                a division of the Cenozoic Era. The Quaternary period began with the Pleistocene Epoch 2.58 million years ago and continues today.</p>
            </div>
      </div>
        <br>
      <button class="bttn" id="data" onclick="Func_data()"> 
          <div><p><strong>Data Science Terminology</strong></p></div>
      </button>
      <div class="collapse" id="readMore_data">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>What words like ontology mean?</p>
          </div>
      </div>
    </div>
</div>

<script>
function Func_care() {
  document.getElementById("readMore_care").classList.toggle("show_b");
  document.getElementById("care").classList.toggle("bttn_show");
}

function Func_fair() {
  document.getElementById("readMore_fair").classList.toggle("show_b");
  document.getElementById("fair").classList.toggle("bttn_show");
}

  function Func_quat() {
  document.getElementById("readMore_quat").classList.toggle("show_b");
  document.getElementById("quat").classList.toggle("bttn_show");
}

   function Func_data() {
  document.getElementById("readMore_data").classList.toggle("show_b");
  document.getElementById("data").classList.toggle("bttn_show");
}



</script>
