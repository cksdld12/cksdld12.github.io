---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Working Papers</h2>
{% bibliography --query @*[note!=Work in Progress] %}

<h2>Work in Progress</h2>
{% bibliography --query @*[note=Work in Progress] %}

</div>
