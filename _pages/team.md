---
title: "Neutrino Interactions - Team"
layout: gridlay
excerpt: "Group Members"
sitemap: false
permalink: /team/
---

# Group Members

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <!-- <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" /> -->
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive team-photo" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {%- capture icons -%}
  {% if member.email %}<a href="mailto:{{ member.email }}"><i class="fas fa-envelope-square fa-2x"></i></a>{% endif %}
  {% if member.site %}<a href="{{ member.site }}"><span class="fa-stack fa-1x fa-stacked"><i class="fas fa-square fa-stack-2x"></i><i class="fas fa-home fa-stack-1x fa-inverse"></i></span></a>{% endif %}
  {% if member.orcid %}<a href="https://orcid.org/{{ member.orcid }}"><i class="ai ai-orcid-square ai-2x"></i></a>{% endif %}
  {% if member.scholar %}<a href="https://scholar.google.com/citations?user={{ member.scholar }}"><i class="ai ai-google-scholar-square ai-2x"></i></a>{% endif %}
  {% if member.github %}<a href="https://github.com/{{ member.github }}"><i class="fab fa-github-square fa-2x"></i></a>{% endif %}
  {% if member.twitter %}<a href="https://twitter.com/{{ member.twitter }}"><i class="fab fa-twitter-square fa-2x"></i></a>{% endif %}
  {% if member.inspire %}<a href="{{ member.inspire }}"><i class="ai ai-inspire-square ai-2x"></i></a>{% endif %}
  {%- endcapture -%}
  {{ icons | strip_newlines }}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<div class="row">
<div class="col-sm-12">
<p>
<strong>This could be you!</strong><br>
Check out our <a href="thesis-topics.md">master thesis subjects</a> or contact us for possibilities.
</p>
</div>
</div>

 
## Former BSc/ MSc students
<div class="row">
<div class="col-sm-4 clearfix">
<h3>Master students</h3>
{% for member in site.data.alumni_msc %}
<p>
<strong>{{ member.name }}</strong><br>
{% if member.subject %}<span>{{ member.subject }}</span><br>{% endif %}
{% if member.year %}<span>{{ member.year }}</span>{% endif %}
</p>
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h3>Bachelor students</h3>
{% for member in site.data.alumni_bsc %}
<p>
<strong>{{ member.name }}</strong><br>
{% if member.subject %}<span>{{ member.subject }}</span><br>{% endif %}
{% if member.year %}<span>{{ member.year }}</span>{% endif %}
</p>
{% endfor %}
</div>
</div>

