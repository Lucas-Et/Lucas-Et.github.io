---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

<p style="margin-left: 40px"><b>Ph.D on "Imputation of Missing Not at Random values in proteomics with transcriptomics integration"</b>
<br>Université Grenoble-Alpes, Grenoble
<br><i>Since November 2020</i></p>

<p style="margin-left: 40px"><b>MSc in Industrial and Applied Mathematics</b>
<br>Grenoble INP - Ensimag, Université Grenoble-Alpes, Grenoble
<br><i>2020</i></p>

Work experience
======

<p style="margin-left: 40px"><b>Master Internship</b>
<br>GE Healthcare (Buc)
<br>Automated labelling of prostate arteries 3D network with Deep Learning.
<br><i>February 2020 - August 2020</i></p>


Publications
======

{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %} 
