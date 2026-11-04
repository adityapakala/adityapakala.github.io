---
layout: single
author_profile: true
title: "Projects"
description: "Selected AI systems, software engineering, and research contributions by Aditya Pakala."
permalink: /projects/
---

<style>
  .projects-intro { margin: .2rem 0 1.7rem; color: #64748b; line-height: 1.6; }
  .projects-list { margin: 0 0 1.5rem; padding: 0; }
  .project-item { padding: 1.25rem 0 1.35rem; border-bottom: 1px solid #e5e7eb; }
  .project-item:first-child { padding-top: .3rem; }
  .project-item:last-child { border-bottom: 0; }
  .project-eyebrow { display: block; font-size: .82rem; color: #64748b; margin-bottom: .4rem; letter-spacing: .01em; }
  .project-item h2 { margin: 0 0 .55rem; padding: 0; font-size: 1.2rem; line-height: 1.35; border: 0; }
  .project-item p { margin: 0 0 .8rem; line-height: 1.65; }
  .project-tags { display: flex; flex-wrap: wrap; gap: .4rem; margin: 0 0 .65rem; }
  .project-tags span { display: inline-block; font-size: .76rem; line-height: 1.3; padding: .3rem .6rem; color: #42526a; background: #f1f5f9; border: 1px solid #e2e8f0; border-radius: 5px; }
  .project-footer { display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: .5rem; color: #64748b; font-size: .84rem; }
  .project-footer a { color: #2563eb; }
  .projects-more { margin: 1rem 0; }
  @media (max-width: 600px) { .project-item h2 { font-size: 1.1rem; } .project-footer { align-items: flex-start; } }
</style>

A few AI, software, and research projects I've contributed to. Professional work is summarized at a high level.

<div class="projects-list">
  <article class="project-item">
    <span class="project-eyebrow">01 / Amazon · AI systems</span>
    <h2>Reliability for multi-agent diagnosis</h2>
    <p>Developed grounding guardrails and a multi-judge evaluation methodology for root-cause analysis agents. Focused on catching unsupported conclusions and measuring diagnosis quality against expert-resolved references.</p>
    <div class="project-tags"><span>AWS Bedrock</span><span>Multi-agent systems</span><span>LLM-as-judge</span><span>Evaluation</span></div>
  </article>

  <article class="project-item">
    <span class="project-eyebrow">02 / Walmart Global Tech · Applied AI</span>
    <h2>Making retail data conversational</h2>
    <p>Developed an agentic retrieval assistant for natural-language data access. Paired retrieval and answer evaluation with ML data pipelines and APIs for downstream consumers.</p>
    <div class="project-tags"><span>Agentic RAG</span><span>Spark</span><span>BigQuery</span><span>FastAPI</span></div>
    <div class="project-footer"><span>Jun – Aug 2025</span></div>
  </article>

  <article class="project-item">
    <span class="project-eyebrow">03 / ZeoAuto (Y Combinator) · Backend &amp; ML systems</span>
    <h2>ML inference for fleet routing</h2>
    <p>Built Python inference services and integrated routing models with operational software. Emphasized availability, fast response times, and scalable deployment.</p>
    <div class="project-tags"><span>Python</span><span>AWS Lambda</span><span>Docker</span><span>FastAPI</span></div>
    <div class="project-footer"><span>Aug 2023 – Jul 2024</span></div>
  </article>

  <article class="project-item">
    <span class="project-eyebrow">04 / AIISC · Multimodal research</span>
    <h2>FACTIFY3M</h2>
    <p>Contributed to benchmark development and evaluation for multimodal fact verification, bringing text, images, paraphrases, adversarial stories, and explainability into one research setting.</p>
    <div class="project-tags"><span>Multimodal ML</span><span>Datasets</span><span>Evaluation</span><span>EMNLP 2023</span></div>
    <div class="project-footer"><span>Sep 2022 – Jul 2023</span><a href="https://aclanthology.org/2023.emnlp-main.945/" target="_blank" rel="noopener noreferrer">Read paper ↗</a></div>
  </article>
</div>

<div class="projects-more"><a href="{{ '/cv/' | relative_url }}">See detailed experience ↗</a></div>
