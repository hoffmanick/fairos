---
layout: default
title: Webinar Info
---

   <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;padding-left:0%;width:67%;align-content:start;padding-top:0px;margin-top:20px;border-top: 1px solid #ec970b;min-width:293px;">
     {% assign posts = site.posts | where_exp: "item", "item.tags contains 'webinar'" %}
      {% for post in posts %}
      <div class="text-block-right" style="display:grid; grid-template-columns: auto auto; justify-content: start; border-bottom: 1px solid #ec970b;width:95%;padding-top:2%;padding-bottom:2%;">
          {% if post.image %} 
            <img src={{ post.image }} width="180vw" alt="{{ post.alt }}" style="max-width:500px;">
          {% endif %}
          {% if post.image == %}
            <div class="test" style="width:180px;">
              <!-- <p style="">empty</p> -->
            </div>
          {% endif %}
        <div style="display:grid;grid-template-rows: auto auto;padding-left:20px;align-content:start">
        <p style="font-size:14px;">{{ post.date | date_to_string }}</p>
        <p><a href="{{ post.url | relative_url }}">{{ post.title }}</a></p>
         </div>
      </div>
{% endfor %}

    </div>
