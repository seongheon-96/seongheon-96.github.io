---
layout: page
permalink: /publications/
title: Selected Publications
nav: false
nav_order: 2
---

{% include publications_note.liquid %}

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[selected=true]* %}

</div>
