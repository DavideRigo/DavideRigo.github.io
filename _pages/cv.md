---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 6
cv_pdf: cv_web.pdf # you can also use external links here
description:
toc:
  sidebar: left
---

{% if page.cv_pdf contains '://' %}
  <meta http-equiv="refresh" content="0; url={{ page.cv_pdf }}">
{% else %}
  <meta http-equiv="refresh" content="0; url={{ page.cv_pdf | relative_url }}">
{% endif %}
