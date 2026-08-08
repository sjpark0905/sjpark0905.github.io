---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Preprints</h2>
{% bibliography --query @unpublished %}

<h2>Publications</h2>
{% bibliography --query @inproceedings || @incollection || @article %}

</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.publications .links a').forEach(function (link) {
      if (link.textContent.trim() === 'HTML') link.textContent = 'Paper';
    });
  });
</script>

<style>
  .post-header {
    display: none;
  }
</style>
