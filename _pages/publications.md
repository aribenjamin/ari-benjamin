---
layout: page
permalink: /publications/
title: publications
description: Selected highlights, followed by all publications in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Highlights</h2>

{% bibliography --query @*[selected=true]* --group_by none %}

<h2>All publications</h2>

{% bibliography %}

</div>
