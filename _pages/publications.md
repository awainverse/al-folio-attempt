---
layout: page
permalink: /publications/
title: publications
description: publications and preprints in reversed chronological order. generated by jekyll-scholar.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="preprints">

{% bibliography --query "!@*[journal]" %}

</div>

<div class="publications">

{% bibliography --query "@*[journal]" %}

</div>