---
permalink: /people/
layout: page
title: People
---

#### **We are looking for new PhD students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/apply) **!**


{% for member in site.data.team_members %}

<div class="row mt-3">
  <div class="col-md-4 col-offset-md-1 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="100%" style="float: left" /> </div>
  <div class="col-md-8 clearfix">
    <h4>{{ member.name }}</h4>
    <br>{{ member.info }}<br>Email: {{ member.email }}
    <p>{{ member.bio }}</p>
  </div>
</div>

{% endfor %}
