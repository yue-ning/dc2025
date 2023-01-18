---
layout: page
title: Invited Talks
permalink: "/speakers/"
---

{% for speaker in site.speakers %}
  <div class="speaker">
     <p>
     <a href="{{ site.baseurl }}/{{ speaker.day }}">{{ speaker.label }} &nbsp; {{ speaker.time }}</a> &nbsp; 
     <h2>{{ speaker.name }}</h2> 
    {{ speaker.role }}, &nbsp;  {{ speaker.institution }} &nbsp; <a href="{{ speaker.website }}"> Homepage </a> <br>
    <b>Title</b>: {{ speaker.title }} <br>
    <a href="..{{ speaker.url }}">link</a>
    </p>
  </div>
{% endfor %}
