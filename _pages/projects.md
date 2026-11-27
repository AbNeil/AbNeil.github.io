---
layout: page
title: Projects
permalink: /Projects/
description: Selected research and industry projects in trustworthy AI, knowledge graphs, multilingual language technologies, digital twins, and predictive analytics.
nav: true
nav_order: 3
---

<style>
.project-list { display:grid; grid-template-columns:repeat(2,minmax(0,1fr)); gap:1rem; margin:1.4rem 0 2.5rem; }
.project-panel { min-width:0; padding:1.15rem 1.2rem; border:1px solid var(--global-divider-color,#cbd5e1); border-top:4px solid var(--accent); border-radius:10px; background:var(--global-card-bg-color,#f5f6f7); background-image:linear-gradient(145deg,color-mix(in srgb,var(--accent) 12%,transparent),transparent 75%); box-shadow:0 3px 12px rgba(25,45,65,.08); transition:transform .2s,box-shadow .2s; }
.project-panel:hover { transform:translateY(-3px); box-shadow:0 7px 20px rgba(25,45,65,.13); }
.project-panel:last-child { grid-column:1 / -1; }
.project-kicker { display:flex; align-items:center; flex-wrap:wrap; gap:.45rem; margin-bottom:.75rem; }
.project-num { display:inline-flex; align-items:center; justify-content:center; border-radius:6px; padding:.3rem .5rem; background:var(--accent); color:white; font-weight:700; font-size:.75rem; }
.project-category { font-size:.73rem; font-weight:650; color:var(--global-text-color); border-radius:15px; padding:.28rem .6rem; background:color-mix(in srgb,var(--accent) 16%,transparent); }
.project-panel h2 { font-size:1rem; line-height:1.45; font-weight:750; color:var(--global-text-color); margin:0 0 .4rem; }
.project-affiliation { font-size:.78rem; font-weight:650; color:var(--global-text-color); margin-bottom:.6rem; }
.project-panel p { font-size:.88rem; line-height:1.6; }
.project-tags { display:flex; flex-wrap:wrap; gap:.35rem; margin-top:.6rem; }
.project-tag { font-size:.72rem; font-weight:500; padding:.28rem .55rem; border-radius:6px; border:1px solid color-mix(in srgb,var(--accent) 40%,transparent); color:var(--global-text-color); background:color-mix(in srgb,var(--accent) 10%,transparent); }
.project-tech-label { font-size:.74rem; font-weight:700; margin-top:.9rem; }
@media(max-width:767px) { .project-list { grid-template-columns:1fr; } .project-panel:last-child { grid-column:auto; } }
@media(prefers-reduced-motion:reduce) { .project-panel { transition:none; } }
</style>

<div class="project-list">
<article class="project-panel" style="--accent:#315d8c">
<div class="project-kicker"><span class="project-num">01</span><span class="project-category">Language &amp; Knowledge</span></div>
<h2>Multilingual Knowledge Alignment using LLMs and Knowledge Graphs</h2>
<div class="project-affiliation">Horizon Europe</div>
<p>Developed a multilingual reasoning pipeline integrating transformer-based large language models with domain-specific knowledge graphs to detect semantic drift across languages and improve contextual consistency in machine translation systems.</p>
<div class="project-tech-label">Technologies:</div>
<div class="project-tags"><span class="project-tag">PyTorch</span><span class="project-tag">Hugging Face Transformers</span><span class="project-tag">Neo4j</span></div>
</article>
<article class="project-panel" style="--accent:#735b9b">
<div class="project-kicker"><span class="project-num">02</span><span class="project-category">Ethics &amp; Governance</span></div>
<h2>Graph-RAG for Ethics and IPR in Virtual Worlds</h2>

<p>Designed a retrieval-augmented generation framework combining structured knowledge graphs with generative language models to answer ethical, intellectual-property, and policy questions across multilingual datasets. Hybrid symbolic-neural reasoning improved retrieval precision by 34%.</p>
<div class="project-tech-label">Focus:</div>
<div class="project-tags"><span class="project-tag">Graph-RAG</span><span class="project-tag">ethical governance</span><span class="project-tag">intellectual property</span><span class="project-tag">multilingual retrieval</span></div>
</article>
<article class="project-panel" style="--accent:#337b76">
<div class="project-kicker"><span class="project-num">03</span><span class="project-category">Language Technology</span></div>
<h2>Language Quality Estimation using Generative Models</h2>

<p>Built a quality-estimation model for translated text using fine-tuned T5 and GPT architectures trained on synthetic multilingual data. Integrated uncertainty estimation for confidence scoring, improving automatic localisation-review accuracy by 28% in simulation.</p>
<div class="project-tech-label">Technologies:</div>
<div class="project-tags"><span class="project-tag">T5</span><span class="project-tag">GPT architectures</span><span class="project-tag">multilingual synthetic data</span><span class="project-tag">uncertainty estimation</span></div>
</article>
<article class="project-panel" style="--accent:#a34d55">
<div class="project-kicker"><span class="project-num">04</span><span class="project-category">Distributed AI</span></div>
<h2>Digital Twin Simulation Pipeline</h2>
<div class="project-affiliation">Huawei Research Ireland</div>
<p>Modelled AI-driven digital-twin environments for real-time cloud networks using distributed training and synchronisation across large datasets. Implemented model versioning, monitoring, and continuous-deployment workflows.</p>
<div class="project-tech-label">Technologies:</div>
<div class="project-tags"><span class="project-tag">Azure Machine Learning</span><span class="project-tag">MLflow</span><span class="project-tag">distributed training</span><span class="project-tag">continuous deployment</span></div>
</article>
<article class="project-panel" style="--accent:#967033">
<div class="project-kicker"><span class="project-num">05</span><span class="project-category">Predictive Analytics</span></div>
<h2>Predictive Analytics for Automotive Retail</h2>
<div class="project-affiliation">Zerve AI</div>
<p>Developed and deployed machine-learning models to predict vehicle-sales velocity from market dynamics and consumer behaviour. Supported production scalability through automated data pipelines, CI/CD workflows, and explainable dashboards for non-technical stakeholders.</p>
<div class="project-tech-label">Technologies:</div>
<div class="project-tags"><span class="project-tag">PyTorch</span><span class="project-tag">Azure Data Factory</span><span class="project-tag">CI/CD</span><span class="project-tag">explainable analytics</span></div>
</article>
</div>
