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
.edu-journey { max-width:980px; margin:2rem auto 3rem; }
.edu-timeline { display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); grid-template-rows:auto 46px auto; column-gap:1.25rem; position:relative; list-style:none; padding:0; margin:0; }
.edu-ribbon { grid-row:2; grid-column:1 / -1; align-self:stretch; display:flex; justify-content:center; align-items:center; border-radius:5px; background:linear-gradient(100deg,#233f5b,#376c79 52%,#733d65); color:white; font-size:.95rem; font-weight:700; letter-spacing:.12em; text-transform:uppercase; box-shadow:0 3px 10px rgba(20,40,60,.15); z-index:2; }
.edu-milestone { display:flex; flex-direction:column; align-items:center; text-align:center; position:relative; min-width:0; gap:.55rem; grid-column:var(--col); }
.edu-milestone:nth-child(odd) { grid-row:1; align-self:end; padding-bottom:0; }
.edu-milestone:nth-child(even) { grid-row:3; align-self:start; }
.edu-milestone:nth-child(even) .edu-logo { order:-1; border-radius:0 0 75px 75px; }
.edu-text { width:100%; max-width:275px; padding:0 .35rem; }
.edu-year { color:var(--global-text-color); font-size:1.45rem; font-weight:800; letter-spacing:.02em; line-height:1.1; margin:0 0 .35rem; }
.edu-degree { font-size:1rem; font-weight:750; line-height:1.4; margin:.2rem 0 .3rem; color:var(--global-text-color); }
.edu-university { font-size:.88rem; font-weight:600; line-height:1.45; color:var(--global-text-color); margin:0; }
.edu-place { font-size:.77rem; color:var(--global-text-color-light); display:block; margin:.2rem 0; }
.edu-logo { display:flex; width:142px; height:138px; align-items:center; justify-content:center; background:#fff; border:3px solid var(--accent); border-bottom:0; border-radius:75px 75px 0 0; padding:12px; margin:.15rem 0 0; text-decoration:none; box-shadow:0 4px 15px rgba(25,45,65,.10); transition:transform .2s,box-shadow .2s; }
.edu-milestone:nth-child(even) .edu-logo { border-bottom:3px solid var(--accent); border-top:0; margin:0 0 .15rem; }
.edu-logo img { width:100%; height:100%; object-fit:contain; }
.edu-logo:hover,.edu-logo:focus-visible { transform:scale(1.04); box-shadow:0 8px 22px rgba(25,45,65,.18); }
.edu-milestone:nth-child(even) .edu-text { padding-top:.2rem; }
@media(max-width:767px) { .edu-journey { margin:1.4rem auto 2rem; } .edu-timeline { display:flex; flex-direction:column; gap:1.2rem; border-left:3px solid #376c79; margin:0 0 0 .5rem; padding-left:1rem; } .edu-ribbon { order:-1; min-height:40px; margin-left:-1rem; } .edu-milestone { flex-direction:row; text-align:left; gap:.85rem; align-items:center!important; } .edu-milestone .edu-logo,.edu-milestone:nth-child(even) .edu-logo { order:-1; width:82px; height:90px; flex:0 0 82px; padding:6px; border:2px solid var(--accent); border-radius:9px; margin:0; } .edu-text { padding:0; max-width:none; } .edu-year { font-size:1.15rem; } .edu-degree { font-size:.92rem; } }
@media(prefers-reduced-motion:reduce) { .edu-logo { transition:none; } }

.edu-logo { overflow:hidden; box-sizing:border-box; padding:18px; }
.edu-logo img { display:block; width:100%; height:100%; max-width:100%; max-height:100%; object-fit:contain; }
.edu-milestone:nth-child(2) .edu-logo img { width:80%; height:80%; }
.edu-milestone:nth-child(3) .edu-logo img { width:82%; height:82%; }
.edu-place { color:var(--global-text-color); font-weight:700; }
@media(max-width:767px) { .edu-logo { padding:6px; } }
</style>

<div class="edu-journey" aria-label="Education timeline">
<ol class="edu-timeline">
<li class="edu-milestone" style="--col:1;--accent:#6b4b83">
<div class="edu-text"><div class="edu-year">2012</div><h2 class="edu-degree"><em>BTech in Information Technology Engineering</em></h2><p class="edu-university">Baba Ghulam Shah Badshah University</p><span class="edu-place">India</span></div>
<a class="edu-logo" href="https://www.bgsbu.ac.in/" target="_blank" rel="noopener" aria-label="Visit Baba Ghulam Shah Badshah University"><img src="/assets/img/education-bgsbu.png" alt="Baba Ghulam Shah Badshah University logo"></a>
</li>
<li class="edu-milestone" style="--col:2;--accent:#245c91">
<div class="edu-text"><div class="edu-year">2016</div><h2 class="edu-degree"><em>MS in Electronics and Information Engineering</em></h2><p class="edu-university">Chonbuk National University</p><span class="edu-place">South Korea</span></div>
<a class="edu-logo" href="https://www.jbnu.ac.kr/en/" target="_blank" rel="noopener" aria-label="Visit Jeonbuk National University"><img src="/assets/img/education-jeonbuk.png" alt="Jeonbuk National University logo"></a>
</li>
<li class="edu-milestone" style="--col:3;--accent:#a90055">
<div class="edu-text"><div class="edu-year">2024</div><h2 class="edu-degree"><em>PhD in Electrical and Electronic Engineering</em></h2><p class="edu-university">University of Galway</p><span class="edu-place">Ireland</span></div>
<a class="edu-logo" href="https://www.universityofgalway.ie/" target="_blank" rel="noopener" aria-label="Visit University of Galway"><img src="/assets/img/education-galway.png" alt="University of Galway logo"></a>
</li>
<li class="edu-ribbon" aria-hidden="true">Education Timeline &nbsp; →</li>
</ol>
</div>
