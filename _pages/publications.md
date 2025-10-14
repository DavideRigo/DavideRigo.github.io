---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 2
hide_title: true
---


<div class="publications">

 <h2 class="pubyear">peer reviewed articles</h2>
{% bibliography -f papers %} 

<h2 class="pubyear">working papers</h2>
{% bibliography -f workingpapers %}

<h2 class="pubyear">selected work in progress</h2>
{% bibliography -f inprogress %}

</div>
