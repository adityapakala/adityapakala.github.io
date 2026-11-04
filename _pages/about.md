---
layout: single
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .home-intro { margin: 0 0 1.4rem; }
  .home-intro h2 { margin: 0 0 .7rem; font-size: 1.55rem; border-bottom: 0; }
  .home-intro p { margin: 0; line-height: 1.7; }
  .home-main { display: grid; grid-template-columns: minmax(0, 2fr) minmax(0, 3fr); gap: 1.6rem; align-items: start; margin: 1.3rem 0 1.2rem; }
  .home-main > * { min-width: 0; }
  .home-photo { display: block; width: 100%; height: auto; border-radius: 6px; margin: 0; }
  .home-timeline h2 { font-size: 1.15rem; margin: 0 0 .85rem; padding: 0; border: 0; }
  .home-links { margin: 0 0 1.3rem; font-size: .94rem; }
  .home-links a { margin-right: 1.2rem; white-space: nowrap; }
  .experience-timeline { list-style: none !important; margin: .4rem 0 .6rem !important; padding: 0 0 0 1.55rem !important; border-left: 2px solid #dce2e9; }
  .experience-timeline li { list-style: none !important; position: relative; margin: 0 !important; padding: 0 0 .8rem .15rem; }
  .experience-timeline li:last-child { padding-bottom: .1rem; }
  .experience-timeline li::before { content: ""; position: absolute; left: -1.96rem; top: .34rem; width: 11px; height: 11px; border-radius: 50%; background: #aab5c4; border: 2px solid #fff; box-sizing: content-box; }
  .experience-timeline li:first-child::before { background: #2563eb; }
  .experience-timeline strong { display: block; font-size: .93rem; line-height: 1.3; }
  .experience-timeline span { display: block; color: #64748b; font-size: .8rem; margin-top: .15rem; }
  @media (max-width: 700px) {
    .home-main { display: flex; flex-direction: column; gap: 1rem; }
    .home-timeline { order: 1; width: 100%; }
    .home-photo { order: 2; width: 100%; max-width: 460px; }
    .home-intro h2 { font-size: 1.35rem; }
  }
</style>

<div class="home-intro">
  <h2>Hey, I'm Aditya!</h2>
  <p>Just a curious guy who loves building things and figuring out how they work. I believe AI is one of the biggest revolutions of our time, and I want to play my part in making it more capable, safe, and useful for everyone.</p>
</div>

<div class="home-main">
  <img class="home-photo" src="{{ '/aditya-mit-portrait.jpg' | relative_url }}" alt="Aditya at the MIT campus" loading="eager">
  <section class="home-timeline" aria-labelledby="experience-heading">
    <h2 id="experience-heading">Experience at a glance</h2>
    <ol class="experience-timeline">
      <li><strong>Amazon Ads</strong><span>Agentic AI</span></li>
      <li><strong>Amazon Robotics</strong><span>Robotics · Software Engineering</span></li>
      <li><strong>Walmart Global Tech</strong><span>Fortune 1 · Applied AI</span></li>
      <li><strong>ZeoAuto (Y Combinator)</strong><span>Startup · Engineering</span></li>
      <li><strong>AIISC, University of South Carolina</strong><span>Multimodal AI Research</span></li>
      <li><strong>IIT Delhi</strong><span>Machine Learning Research</span></li>
    </ol>
  </section>
</div>

<div class="home-links">
  <a href="{{ '/resume/' | relative_url }}">Resume ↗</a>
  <a href="{{ '/publications/' | relative_url }}">Research ↗</a>
</div>

[Explore my experience]({{ '/cv/' | relative_url }}) · [Projects]({{ '/projects/' | relative_url }}) · [Gallery]({{ '/gallery/' | relative_url }})
