---
title: "ITAP Robotics & Computer Vision - Projects"
layout: gridlay
excerpt: "ITAP Robotics & Computer Vision - Projects"
sitemap: false
permalink: /projects/
---


# Projects

## **Social Robotics**

{% assign number_printed = 0 %}
{% for proj in site.data.projectlist %}
{% if proj.category == "socialRobotics" %}
<div style="padding-left:15px;padding-right:15px;">
<div class="well" style="overflow: hidden;">
<img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ proj.image }}" class="img-responsive" width="33%" style="float: left" />
<pubtit><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ proj.url }}">{{ proj.title }}</a></pubtit>
<p>{{ proj.description }}</p>
</div>
</div>
{% endif %}
{% endfor %}

## **Manufacturing**

{% assign number_printed = 0 %}
{% for proj in site.data.projectlist %}
{% if proj.category == "manufacturing" %}
<div style="padding-left:15px;padding-right:15px;">
<div class="well" style="overflow: hidden;">
<img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ proj.image }}" class="img-responsive" width="33%" style="float: left" />
<pubtit><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ proj.url }}">{{ proj.title }}</a></pubtit>
<p>{{ proj.description }}</p>
</div>
</div>
{% endif %}
{% endfor %}

## **Cultural Heritage**

{% assign number_printed = 0 %}
{% for proj in site.data.projectlist %}
{% if proj.category == "cultural" %}
<div style="padding-left:15px;padding-right:15px;">
<div class="well" style="overflow: hidden;">
<img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ proj.image }}" class="img-responsive" width="33%" style="float: left" />
<pubtit><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ proj.url }}">{{ proj.title }}</a></pubtit>
<p>{{ proj.description }}</p>
</div>
</div>
{% endif %}
{% endfor %}

## **Smart Technologies**

{% assign number_printed = 0 %}
{% for proj in site.data.projectlist %}
{% if proj.category == "smartTechnologies" %}
<div style="padding-left:15px;padding-right:15px;">
<div class="well" style="overflow: hidden;">
<img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ proj.image }}" class="img-responsive" width="33%" style="float: left" />
<pubtit><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ proj.url }}">{{ proj.title }}</a></pubtit>
<p>{{ proj.description }}</p>
</div>
</div>
{% endif %}
{% endfor %}

<p> &nbsp; </p>

<!--
{% assign number_printed = 0 %}
{% for proj in site.data.projectlist %}

<div style="padding-left:15px;padding-right:15px;">
<div class="well" style="overflow: hidden;">
<img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ proj.image }}" class="img-responsive" width="33%" style="float: left" />
<pubtit><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ proj.url }}">{{ proj.title }}</a></pubtit>
<p>{{ proj.description }}</p>
</div>
</div>


{% endfor %}
<p> &nbsp; </p>
-->


