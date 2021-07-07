---
layout: page
title: Career Panel
permalink: "/panel/"
---

{% for speaker in site.panelists %}
  <div class="panelist">
    <p><a href="{{ speaker.website }}">{{ speaker.name }}</a></p>
  </div>
{% endfor %}
