---
layout: page
permalink: /speakers/
title: Speakers
nav: true
nav_order: 3
---

<style>
  .speakers-profile .more-info {
    text-align: center;
  }

  .talk-title-line {
    color: #d96b1f;
    font-weight: 700;
  }
</style>

<hr>
<div class="profile float-left speakers-profile">
  {% include figure.liquid loading="eager" path="assets/img/loic_lannelongue.jpg" class="img-fluid z-depth-1 rounded-circle" alt="Loic Lannelongue" %}
  <div class="more-info">
    <p>University of Cambridge, UK</p>
  </div>
</div>

<div class="clearfix">
  <p><strong><a href="https://www.jesus.cam.ac.uk/people/loic-lannelongue" target="_blank" rel="noopener"> <font size="5">Loic Lannelongue</font></a></strong></p>
  {% capture loic_content %}{% include_relative about_loic_lannelongue.md %}{% endcapture %}
  {{ loic_content | markdownify }}
</div>

<hr>
<div class="profile float-left speakers-profile">
  {% include figure.liquid loading="eager" path="assets/img/pierre_jacquet.jpg" class="img-fluid z-depth-1 rounded-circle" alt="Pierre Jacquet" %}
  <div class="more-info">
    <p>Universite du Quebec (ETS Montreal, Canada) and OVHcloud</p>
  </div>
</div>

<div class="clearfix">
  <p><strong><a href="https://jacquetpi.github.io/" target="_blank" rel="noopener"> <font size="5">Pierre Jacquet</font></a></strong></p>
  {% capture pierre_content %}{% include_relative about_nic_lane.md %}{% endcapture %}
  {{ pierre_content | markdownify }}
</div>

<hr>
<div class="profile float-left speakers-profile">
  {% include figure.liquid loading="eager" path="assets/img/edoardo_ponti.jpeg" class="img-fluid z-depth-1 rounded-circle" alt="Edoardo M. Ponti" %}
  <div class="more-info">
    <p>University of Edinburgh, UK</p>
  </div>
</div>

<div class="clearfix">
  <p><strong><a href="https://ducdauge.github.io/" target="_blank" rel="noopener"> <font size="5">Edoardo M. Ponti</font></a></strong></p>
  {% capture edoardo_content %}{% include_relative about_edoardo_ponti.md %}{% endcapture %}
  {{ edoardo_content | markdownify }}
</div>


<div class="profile float-left speakers-profile">
  {% include figure.liquid loading="eager" path="assets/img/maximilian_boether.jpg" class="img-fluid z-depth-1 rounded-circle" alt="Maximilian Boether" %}
  <div class="more-info">
    <p>ETH Zurich and DatologyAI</p>
  </div>
</div>

<div class="clearfix">
  <p><strong><a href="https://mboether.com/" target="_blank" rel="noopener"> <font size="5">Maximilian Boether</font></a></strong></p>
  {% capture maximilian_content %}{% include_relative about_maximilian_boether.md %}{% endcapture %}
  {{ maximilian_content | markdownify }}
</div>

<hr>
