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

 .container {
  display: flex;
  <!-- align-items: center; -->
  <!-- justify-content: center -->
}
img {
  max-width: 100%;
  max-height:100%;
}

.text {
  font-size: 15px;
  padding-left: 3px;
  align-items: left;
  justify-content: left;
  text-align: left;
 
}
 h1 h2 h3 h4 h5 {
   color: #42b7bf;
   -webkit-text-stroke-width: 1px;
   -webkit-text-stroke-color: black;
    }
  p {
    font-size: 20px;
  }
.text-block-right {
  width:500px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: 25%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to left, white, #97b779); 
  text-align: center;
}
  .text-block-left {
  width:500px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: -25%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to right, white, #97b779); 
  text-align: center;
}
  .text-block-main {
  width:800px;
  padding-bottom:20px;
  padding-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: -5%;
  margin-top: 5%;
  margin-bottom: 5%;
  background-image: linear-gradient(to left, white, #97b779); 
}
  .text-block-main  p {
  font-size: 20px;
}
</style>

<h1> Ethical Open Science in the News </h1>

{% for post in site.posts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

<h2>FAIROS Events Calendar</h2>
<p>Join us for webinars, workshops, and other events</p>
<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23B39DDB&ctz=America%2FChicago&title=Upcoming%20FAIROS%20Events&src=Y2U1NzRhZTM5Y2JhOTMyNDIyZDAzNjA1MzFlZDE1OGI0ZmQ4MjdiMDY1YmE3Yjk1YjMxNTk1MWVjYTYwNDVlOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%238E24AA?wmode=transparent" title = "FAIROS Events Calendar" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no" id="cal"> wmode="transparent" </iframe>

Return to [main page](home.md)
