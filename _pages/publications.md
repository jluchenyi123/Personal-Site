---
layout: page
permalink: /publications/
title: publications
description: Yi Chen's publications, ordered from newest to oldest.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[selected=true] %}

</div>
