---
layout: page
permalink: /output/
title: Output
ord: 30
description:

years: [2022, 2021]
nav: true
---

<!-- _pages/publications.md

scholar jekyll plugin
https://www.amirasiaee.com/dailyreport/jekyll-scholar/
https://github.com/inukshuk/jekyll-scholar
-->

### <b>Papers</b>
***
<strong>Proceedings:</strong>
<div class="publications">
  {% bibliography -f refereed %}
</div>

<br>
<strong>Unpublished manuscripts:</strong>
<div class="publications">
  {% bibliography -f unpublished %}
</div>

<br>
### <b>Presentations</b>
***
<strong>Conference talks:</strong>
<div class="publications">
  {% bibliography -f talks %}
</div>

<br>
<strong>Poster presentations:</strong>
<div class="publications">
  {% bibliography -f posters %}
</div>
