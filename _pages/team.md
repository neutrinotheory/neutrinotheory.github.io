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
  <!-- <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> --> 
  <i>{{ member.info }}{% if member.info2 %}<br>{{ member.info2 }}{% endif %} </i>
  {% if member.email or member.inspire %}
  <div style="margin-top: 0.35em; margin-bottom: 0.35em;">
    {% if member.email %}
      <a href="mailto:{{ member.email }}" aria-label="Email {{ member.name }}" style="margin-right: 0.75em;">
        <i class="fa-solid fa-envelope"></i>
        <span style="margin-left: 0.25em;">Email</span>
      </a>
    {% endif %}
    {% if member.inspire %}
      <a href="{{ member.inspire }}" target="_blank" rel="noopener noreferrer" aria-label="INSPIRE profile for {{ member.name }}">
        <i class="fa-solid fa-atom"></i>
        <span style="margin-left: 0.25em;">INSPIRE</span>
      </a>
    {% endif %}
  </div>
  {% endif %}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  <li> {{ member.education3 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  <li> {{ member.education3 | markdownify}} </li>
  <li> {{ member.education4 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  <li> {{ member.education3 | markdownify}} </li>
  <li> {{ member.education4 | markdownify}} </li>
  <li> {{ member.education5 | markdownify}} </li>
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
Check out our master thesis subjects or contact us for possibilities.
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

