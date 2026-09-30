---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<style>
  /* Preprints와 Publications 섹션 사이 간격 */
  .publications-section + .publications-section {
    margin-top: 3.5rem;
  }

  /* 오른쪽 연도 표시 */
  .publications h2.bibliography {
    color: #707070 !important;
    font-size: 1.7rem;
    font-weight: 600;
  }

  /* 다크 모드의 연도 표시 */
  html[data-theme='dark'] .publications h2.bibliography {
    color: #aaaaaa !important;
  }

  @media (prefers-color-scheme: dark) {
    html:not([data-theme='light']) .publications h2.bibliography {
      color: #aaaaaa !important;
    }
  }
</style>

<div class="publications">
  <section class="publications-section">
    <h2>Preprints</h2>

    {% bibliography --query @unpublished %}
  </section>

  <section class="publications-section">
    <h2>Publications</h2>

    {% bibliography --query @inproceedings || @incollection || @article %}
  </section>
</div>
