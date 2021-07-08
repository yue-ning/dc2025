---
layout: page
title: Invited Talks
permalink: "/speakers/"
---

{% for speaker in site.speakers %}
  <div class="speaker">
     <p><a href="{{ site.baseurl }}/{{ speaker.day }}">{{ speaker.label }} &nbsp; {{ speaker.time }}</a> &nbsp; <a href="{{ speaker.website }}">{{ speaker.name }}</a> &nbsp; <a href="..{{ speaker.url }}">link</a></p>
  </div>
{% endfor %}
