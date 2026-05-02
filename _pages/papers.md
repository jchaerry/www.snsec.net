---
layout: page
permalink: /papers/
title: papers
description: Publications by categories in reversed chronological order.
nav: false
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Journal &amp; Conference Papers</h2>

{% bibliography -f papers %}

<h2 class="bibliography">Datasets</h2>

{% bibliography -f datasets %}

<h2 class="bibliography">Standards &amp; Recommendations</h2>

{% bibliography -f standards %}

<h2 class="bibliography">Korean-Language Papers</h2>

{% bibliography -f korean %}

</div>
