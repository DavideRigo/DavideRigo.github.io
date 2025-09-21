---
layout: page
permalink: /publications/
title: 
description:
nav: true
nav_order: 2
hide_title: true
---

<div class="publications">
  <h2>publications</h2>
  {% bibliography --query @*[type~=pub] %}
</div>

<div class="working-papers">
  <h2>working papers</h2>
  {% bibliography --query @*[type~=wp] %}
</div>

<div class="selected-work-in-progress">
  <h2>selected work in progress</h2>
  {% bibliography --query @*[type~=wip] %}
</div>
