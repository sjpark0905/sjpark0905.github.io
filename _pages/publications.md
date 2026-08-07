---
layout: page
permalink: /publications/
title: publications
description: Preprints and peer-reviewed publications.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Preprints</h2>
{% bibliography --query @unpublished %}

<h2>2026</h2>
{% bibliography --query @inproceedings[year=2026] %}

<h2>2025</h2>
{% bibliography --query @inproceedings[year=2025] || @article[year=2025] %}

<h2>2023</h2>
{% bibliography --query @article[year=2023] %}

<h2>2022</h2>
{% bibliography --query @article[year=2022] %}

<h2>2021</h2>
{% bibliography --query @article[year=2021] %}

</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.publications .links a').forEach(function (link) {
      if (link.textContent.trim() === 'HTML') link.textContent = 'Paper';
    });
  });
</script>
