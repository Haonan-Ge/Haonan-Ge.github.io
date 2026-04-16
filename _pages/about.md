---
layout: about
title: About
permalink: /

profile:
  align: right
  image: johnny.jpg
  image_circular: false # crops the image to make it circular
  more_info: <p class="photo-note"> (at Laguna Beach, California)</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 20 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<section class="home-hero">
  <p class="hero-kicker">Haonan Ge · 葛浩南</p>
  <p class="hero-lead">
    I am an incoming CS Ph.D. student at <a href="https://www.ucsb.edu/">University of California, Santa Barbara (UCSB)</a><img src="/assets/img/ucsb.png" alt="icon"  style="height: 1.3em; width: auto; margin-left: 0.2em; position: relative; top: 0.3em;">
    advised by <a href="https://yaoqin1.github.io/#about">Prof. Yao Qin</a>. I am also a senior undergraduate student in Electrical
    and Computer Engineering at <a href="https://www.seu.edu.cn/english/">Southeast University</a>.
  </p>
  <p class="hero-lead">
    I currently work as a Research Intern with <a href="https://www.ucmerced.edu/">UC Merced</a> and
    <a href="https://www.uq.edu.au/">The University of Queensland</a>, advised by
    <a href="https://vanoracai.github.io/">Prof. Yujun Cai</a> (UQ) and
    <a href="https://wangywust.github.io/">Prof. Yiwei Wang</a> (UC Merced), and I collaborate with
    <a href="https://web.cs.ucla.edu/~kwchang/">Prof. Kai-Wei Chang</a> (UCLA) and
    <a href="https://faculty.ucmerced.edu/mhyang/">Prof. Ming-Hsuan Yang</a> (UC Merced).
  </p>
  <div class="hero-meta-row">
    <div class="hero-tags">
      <span>Incoming Ph.D. @ UCSB</span>
      <span>ECE @ Southeast University</span>
    </div>
    {% if page.social %}
      <div class="hero-social">
        <div class="contact-icons">{% include social.liquid %}</div>
      </div>
    {% endif %}
  </div>
</section>

<section class="research-interest">
  <h3>Research Interests</h3>
  <div class="interest-list">
    <article class="interest-item">
      <h4>Faithful Multimodal Intelligence and World Modeling</h4>
      <p>
        I build multimodal models that learn physical laws and world dynamics from large-scale unlabeled video, grounding decisions in
        perceptual evidence rather than language priors.
      </p>
    </article>
    <article class="interest-item">
      <h4>Scalable Multimodal Action Reasoning and Agents</h4>
      <p>
        I study controllable systems that integrate images, video, audio, and actions, aiming for practical agentic tools for creative
        workflows like filmmaking and design.
      </p>
    </article>
  </div>
</section>

<p class="opportunity-callout">
  I am actively seeking a Research Intern position. Feel free to reach out.
</p>

<div class="contact-strip">
  <a class="contact-link" href="mailto:haonange@ucsb.edu">haonange@ucsb.edu</a>
  <a class="contact-link" href="mailto:gehaonan82@gmail.com">gehaonan82@gmail.com</a>
  <a class="cv-btn" href="/assets/pdf/CV.pdf">Download CV</a>
</div>
