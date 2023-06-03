---
layout: default
title: News
weight : 98
permalink: /news
---
<style>
#cal {
  position: relative;
  z-index: 0;
  }
h1#heading-left {
  font-size:40px;
  }
  
#posts-calendar {
  grid-template-columns:66.666% 33.3333%;
  }
@media print,screen and (max-width:620px) {
  #cal {
    width:200px;
  }
  #heading-left {
   padding-top:0px;
   padding-bottom:0px;
   align-content:space-between;
  }
  h1#heading-left {
   font-size:33px;
  }
  #posts-calendar {
  grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));}
 }
</style>


<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #f0d2a1, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="align-self:start;">Ethical Open Science in the News</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Learn about what we've been up to, and watch out for upcoming events.</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/team.jpg" alt="Stakeholders" style="width=100%;border: 1px solid #ec970b;">
        <figcaption>Some other image should go here?</figcaption>
      </figure>
    </div>
  </div>

<div class="text-block-right" style="display:grid;padding-left:5%;width:95%;" id="posts-calendar">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;padding-left:0%;width:100%;align-content:start;">
      <h2>Recent Ethical FAIROS Items</h2>
      <ul>
      {% for post in site.posts %}
      <li><p>{{ post.date | date_to_string }}: <a href="{{ post.url | relative_url }}">{{ post.title }}</a></p></li>
{% endfor %}
      </ul>
    </div>

    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto auto;padding-left:0%;width:100%;">
      <h2> FAIROS Events Calendar </h2>
      <p>Join us for webinars, workshops, and other events</p>
      <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23B39DDB&ctz=America%2FChicago&title=Upcoming%20FAIROS%20Events&src=Y2U1NzRhZTM5Y2JhOTMyNDIyZDAzNjA1MzFlZDE1OGI0ZmQ4MjdiMDY1YmE3Yjk1YjMxNTk1MWVjYTYwNDVlOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%238E24AA?wmode=transparent" title = "FAIROS Events Calendar" style="border: 1px solid #ec970b;" width="400" height="300" frameborder="0" scrolling="no" id="cal"> wmode="transparent" </iframe>
    </div>
</div>
