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

<div style="color: #000000;">
  <p>
    <a
      href="mailto:joonpark2247@gmail.com"
      style="color: #000000; text-decoration: underline;"
    >
      joonpark2247@gmail.com
    </a>
  </p>

  <p>
    Hi, I’m
    <span style="color: #8b5a2b; font-weight: 700;">
      Seong-Joon Park
    </span>,
    a Staff Engineer at Samsung Electronics. I was a Postdoctoral Researcher in
    the Institute of Artificial Intelligence at
    <a
      href="https://www.postech.ac.kr/eng/"
      style="color: #000000; text-decoration: underline;"
    >
      Pohang University of Science and Technology (POSTECH)
    </a>
    hosted by Prof.
    <a
      href="https://iil.postech.ac.kr/people"
      style="color: #000000; text-decoration: underline;"
    >
      Yongjune Kim
    </a>.
    I received Ph.D. and M.S. degrees in Electrical and Computer Engineering at
    <a
      href="https://en.snu.ac.kr/index.html"
      style="color: #000000; text-decoration: underline;"
    >
      Seoul National University (SNU)
    </a>,
    where I was advised by Prof.
    <a
      href="https://scholar.google.com/citations?user=ZL-p_cIAAAAJ&hl=ko&oi=ao"
      style="color: #000000; text-decoration: underline;"
    >
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
