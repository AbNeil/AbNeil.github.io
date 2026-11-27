---
layout: page
title: Education
permalink: /education/
nav: true
nav_order: 6
_styles: |
  .post-header { display: none; }
---

<style>
.edu-journey { max-width: 950px; margin: 1.8rem auto 3rem; }
.edu-steps { list-style: none; display:grid; grid-template-columns: repeat(3,minmax(0,1fr)); gap:1rem; padding:0; margin:0; align-items:start; position:relative; }
.edu-step { min-width:0; position:relative; margin-top:var(--rise); }
.edu-card { position:relative; overflow:hidden; border:1px solid var(--global-divider-color,#cbd5e1); border-top:4px solid var(--accent); border-radius:12px; padding:1rem; background:var(--global-card-bg-color,#f5f6f7); background-image:linear-gradient(135deg,color-mix(in srgb,var(--accent) 12%,transparent),transparent 70%); box-shadow:0 4px 15px rgba(25,45,65,.08); transition:transform .2s,box-shadow .2s; }
.edu-card:hover,.edu-card:focus-within { transform:translateY(-4px); box-shadow:0 8px 22px rgba(25,45,65,.15); }
.edu-top { display:flex; align-items:center; justify-content:space-between; gap:.6rem; margin-bottom:.8rem; }
.edu-year { font-size:1.45rem; font-weight:750; color:var(--global-text-color); line-height:1; }
.edu-level { font-size:.73rem; font-weight:700; padding:.3rem .65rem; border-radius:20px; background:var(--accent); color:white; }
.edu-logo { display:flex; justify-content:center; align-items:center; background:white; border-radius:8px; height:102px; padding:.65rem; margin:.65rem 0 .9rem; }
.edu-logo img { width:100%; max-width:152px; max-height:84px; object-fit:contain; }
.edu-degree { font-size:1rem; line-height:1.45; font-weight:700; margin:0 0 .5rem; color:var(--global-text-color); }
.edu-university { font-size:.86rem; line-height:1.4; color:var(--global-text-color); margin:0; }
.edu-place { display:block; color:var(--global-text-color-light); font-size:.76rem; margin:.35rem 0 0; }
.edu-node { display:flex; align-items:center; justify-content:center; width:27px; height:27px; border:3px solid var(--accent); border-radius:50%; background:var(--global-bg-color,#fff); color:var(--global-text-color); margin: .65rem auto 0; font-size:.73rem; font-weight:700; }
.edu-path { display:block; width:100%; height:44px; margin-top:1rem; }
.edu-path path { stroke:#8da2b3; stroke-width:2; fill:none; stroke-linecap:round; stroke-linejoin:round; }
.edu-path text { fill:var(--global-text-color-light); font-size:10px; letter-spacing:.08em; font-weight:600; }
@media (max-width: 767px) { .edu-steps { grid-template-columns:1fr; gap:.8rem; border-left:2px solid #8da2b3; margin-left:12px; padding-left:16px; } .edu-step { margin-top:0; } .edu-card { padding:.85rem; } .edu-logo { height:80px; } .edu-logo img { max-height:65px; } .edu-node { position:absolute; top:0; left:-31px; margin:0; } .edu-path { display:none; } }
@media(prefers-reduced-motion:reduce) { .edu-card { transition:none; } }
</style>

<div class="edu-journey" aria-label="Academic journey from undergraduate degree to doctorate">
<ol class="edu-steps">
<li class="edu-step" style="--accent:#997143;--rise:60px">
<article class="edu-card">
<div class="edu-top"><span class="edu-year">2012</span><span class="edu-level">BTech</span></div>
<a class="edu-logo" href="https://www.bgsbu.ac.in/" target="_blank" rel="noopener"><img src="https://successphd.com/wp-content/uploads/2025/12/Baba-Ghulam-Shah-Badshah-University-logo.png" alt="Baba Ghulam Shah Badshah University logo"></a>
<h2 class="edu-degree"><em>Bachelor of Technology in Information Technology Engineering</em></h2>
<p class="edu-university">Baba Ghulam Shah Badshah University</p>
<span class="edu-place">India · Completed 2012</span>
</article><span class="edu-node" aria-hidden="true">1</span>
</li>
<li class="edu-step" style="--accent:#397b78;--rise:30px">
<article class="edu-card">
<div class="edu-top"><span class="edu-year">2016</span><span class="edu-level">MS</span></div>
<a class="edu-logo" href="https://www.jbnu.ac.kr/en/" target="_blank" rel="noopener"><img src="https://www.timeshighereducation.com/cms-academic/sites/default/files/migrated_institution_logos/logo_jeonbuk-natonal-uni.jpg" alt="Jeonbuk National University logo"></a>
<h2 class="edu-degree"><em>MS in Electronics and Information Engineering</em></h2>
<p class="edu-university">Chonbuk National University</p>
<span class="edu-place">South Korea · Completed 2016</span>
</article><span class="edu-node" aria-hidden="true">2</span>
</li>
<li class="edu-step" style="--accent:#315d8c;--rise:0px">
<article class="edu-card">
<div class="edu-top"><span class="edu-year">2024</span><span class="edu-level">PhD</span></div>
<a class="edu-logo" href="https://www.universityofgalway.ie/" target="_blank" rel="noopener"><img src="https://stories.nuigalway.ie/prof-caroline-mcintosh/assets/KVZKw6d9kZ/university_of_galway_logo__positive_landscape_stacked-4096x2537.png" alt="University of Galway logo"></a>
<h2 class="edu-degree"><em>PhD in Electrical and Electronic Engineering</em></h2>
<p class="edu-university">University of Galway</p>
<span class="edu-place">Ireland · Completed 2024</span>
</article><span class="edu-node" aria-hidden="true">3</span>
</li>
</ol>
<svg class="edu-path" viewBox="0 0 900 44" preserveAspectRatio="none" aria-hidden="true"><path d="M 35 30 H 300 L 332 22 H 600 L 632 14 H 865 M 855 7 L 865 14 L 855 21"/><text x="35" y="12">ACADEMIC JOURNEY</text></svg>
</div>
