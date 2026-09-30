---
layout: about
title: about
permalink: /
subtitle: Staff Engineer at Samsung Electronics

profile:
  align: right
  image: profile.png
  image_circular: false
  more_info: >
    <p>Seoul, South Korea</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

<style>
  .about-introduction {
    color: var(--global-text-color);
  }

  .about-introduction .name-highlight {
    color: #8b5a2b;
    font-weight: 700;
  }

  .about-introduction a {
    color: var(--global-text-color) !important;
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 2px;
  }

  .about-introduction a:hover {
    color: var(--global-theme-color) !important;
  }

  html[data-theme='dark'] .about-introduction .name-highlight {
    color: #e0ad82;
  }

  @media (prefers-color-scheme: dark) {
    html:not([data-theme='light']) .about-introduction .name-highlight {
      color: #e0ad82;
    }
  }
</style>

<div class="about-introduction">
  <p>
    <a href="mailto:joonpark2247@gmail.com">
      joonpark2247@gmail.com
    </a>
  </p>

  <p>
    Hi, I’m
    <span class="name-highlight">Seong-Joon Park</span>,
    a Staff Engineer at Samsung Electronics. I was a Postdoctoral Researcher in
    the Institute of Artificial Intelligence at
    <a href="https://www.postech.ac.kr/eng/">
      Pohang University of Science and Technology (POSTECH)
    </a>
    hosted by Prof.
    <a href="https://iil.postech.ac.kr/people">
      Yongjune Kim
    </a>.
    I received Ph.D. and M.S. degrees in Electrical and Computer Engineering at
    <a href="https://en.snu.ac.kr/index.html">
      Seoul National University (SNU)
    </a>,
    where I was advised by Prof.
    <a href="https://scholar.google.com/citations?user=ZL-p_cIAAAAJ&hl=ko&oi=ao">
      Jong-Seon No
    </a>.
  </p>

  <p>
    My research focuses on information theory, channel coding, machine learning,
    quantum error correction, and quantum information theory.
  </p>

  <ul>
    <li>AI/ML-based decoders for error-correcting codes</li>
    <li>Quantum error correction and quantum information theory</li>
    <li>Channel coding for wireless communication and memory systems</li>
  </ul>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.publications .links a').forEach(function (link) {
      if (link.textContent.trim() === 'HTML') {
        link.textContent = 'Paper';
      }
    });
  });
</script>
