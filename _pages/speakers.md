---
layout: page
title: Invited Talks
permalink: "/speakers/"
---

{% for speaker in site.speakers %}
  <div class="speaker">
     <p>
     <h2>{{ speaker.name }}</h2> 
     <center>
    {{ speaker.role }}, &nbsp;  {{ speaker.institution }} &nbsp; <a href="{{ speaker.website }}"> Homepage </a> </center> <br>
    <p class="aligncenter">
             <img src="{{ page.image }}" alt="{{ page.image }}" style="max-height:250px;">
            </p>
    <b>Title</b>: {{ speaker.title }} <br>
    <a href="..{{ speaker.url }}">link</a>
    </p>
  </div>
{% endfor %}
