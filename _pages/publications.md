---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<div class="publications">
  <h2>Publications</h2>
  {% bibliography --query @*[keywords~=pub] %}
</div>

<div class="working-papers">
  <h2>Working Papers</h2>
  {% bibliography --query @*[keywords~=wp] %}
</div>

<div class="selected-work-in-progress">
  <h2>Selected Work in Progress</h2>
  {% bibliography --query @*[keywords~=wip] %}
</div>
