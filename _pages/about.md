---
permalink: /
layout: home
hide_site_header: true
author_profile: false
excerpt: "Yanchen Huang is a Ph.D. student in Computer Science."
intro: "Hi there! I'm Huang Yanchen. I obtained my Bachelor of Engineering degree in Software Engineering from Nanjing University. I am pursuing a Ph.D. in Computer Science at Westlake University & Zhejiang University. Feel free to contact me!"
redirect_from:
  - /about/
  - /about.html
---

<section id="publications" class="home-section">
  <h2>Publications</h2>

{% include publications.html
  image_path="/images/SpiLiFormer.png"
  title="SpiLiFormer: Enhancing Spiking Transformers with Lateral Inhibition"
  authors="Zeqi Zheng*, <strong>Yanchen Huang*</strong>, Yingchao Yu, Zizheng Zhu, Junfeng Tang, Zhaofei Yu, Yaochu Jin"
  paper_url="https://arxiv.org/pdf/2503.15986"
  code_url="https://github.com/KirinZheng/SpiLiFormer"
  conference="ICCV 2025"
  presentation_type="Poster"
%}
</section>

<section id="education" class="home-section">
  <h2>Education</h2>
  {% include education.html %}
</section>

<section id="experience" class="home-section">
  <h2>Academic Experience</h2>
  {% include academic.html %}
</section>
