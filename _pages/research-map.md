---
layout: page
title: Research Map
permalink: /research-map/
nav: true
nav_order: 8
description: Explore shared research interests and potential collaboration.
---

<style>
.rm-shell { max-width: 960px; margin: 1.2rem auto 3rem; --rm-accent: #356b91; }
.rm-intro { max-width: 720px; line-height: 1.65; }
.rm-grid { display: grid; grid-template-columns: 1.05fr 1fr; gap: 1.2rem; margin: 1.5rem 0; align-items: start; }
.rm-panel { padding: 1.25rem; border: 1px solid var(--global-divider-color, #cbd5e1); border-radius: 12px; background: var(--global-card-bg-color, #f5f6f7); }
.rm-panel h2 { font-size: 1.1rem; font-weight: 700; margin: 0 0 .8rem; }
.rm-option { display: flex; align-items: center; gap: .7rem; border: 1px solid var(--global-divider-color,#cbd5e1); border-left: 4px solid var(--area); border-radius: 7px; padding: .75rem; margin: .55rem 0; cursor: pointer; }
.rm-option:has(input:checked) { background: rgba(53,107,145,.12); }
.rm-option input { accent-color: var(--rm-accent); width: 1.15rem; height: 1.15rem; flex-shrink: 0; }
.rm-option span { flex: 1; font-size: .94rem; font-weight: 600; }
.rm-option small { color: var(--global-text-color-light); white-space: nowrap; }
.rm-score { text-align: center; font-size: 3rem; font-weight: 750; line-height: 1.1; color: var(--rm-accent); font-variant-numeric: tabular-nums; }
.rm-band { text-align: center; font-weight: 600; margin: .5rem; }
.rm-progress { height: 9px; border-radius: 10px; background: rgba(128,128,128,.22); overflow: hidden; margin: .9rem 0; }
.rm-progress div { height: 100%; width: 0; background: var(--rm-accent); transition: width .35s ease; }
.rm-chart { width: 100%; max-width: 380px; height: auto; display: block; margin: auto; }
.rm-chart text { fill: var(--global-text-color); font-size: 11px; font-weight: 600; }
.rm-chart .rm-gridline { stroke: #91a1ad; fill: none; stroke-width: .75; opacity: .5; }
.rm-chart .rm-reference { stroke: #8b9aa7; stroke-dasharray: 4 4; fill: none; stroke-width: 1.5; }
.rm-chart .rm-match { stroke: #356b91; fill: #60a5c7; fill-opacity: .28; stroke-width: 2.5; transition: all .25s ease; }
.rm-key { display: flex; justify-content: center; gap: 1rem; font-size: .76rem; color: var(--global-text-color-light); }
.rm-key b { color: #356b91; }
.rm-shared { min-height: 2.5rem; font-size: .9rem; }
.rm-pill { display: inline-block; margin: .15rem .25rem .15rem 0; padding: .25rem .5rem; border: 1px solid var(--global-divider-color,#cbd5e1); border-radius: 20px; font-size: .78rem; }
.rm-note { font-size: .82rem; color: var(--global-text-color-light); line-height: 1.6; }
.rm-textarea { width: 100%; min-height: 100px; border: 1px solid var(--global-divider-color,#cbd5e1); background: var(--global-bg-color); color: var(--global-text-color); padding: .8rem; border-radius: 7px; margin: .5rem 0 .9rem; }
.rm-button { display: inline-block; padding: .7rem 1.1rem; border-radius: 7px; border: 0; background: #234e75; color: white !important; font-weight: 600; text-decoration: none; cursor: pointer; }
.rm-button:disabled { opacity: .48; cursor: not-allowed; }
.rm-reset { border: 0; background: transparent; color: var(--global-theme-color); cursor: pointer; padding: .5rem 0; font-size: .85rem; }
@media(max-width:767px) { .rm-grid { grid-template-columns: 1fr; } }
@media(prefers-reduced-motion:reduce) { .rm-progress div,.rm-match { transition: none; } }

.rm-shell { --rm-accent:#356b91; }
.rm-panel { box-shadow: 0 5px 20px rgba(23,63,95,.08); }
.rm-option { transition: transform .18s, background .18s, box-shadow .18s; background: color-mix(in srgb, var(--area) 7%, var(--global-card-bg-color, #f5f6f7)); }
.rm-option:hover { transform: translateY(-2px); box-shadow: 0 3px 12px rgba(23,63,95,.14); }
.rm-option:has(input:checked) { background: color-mix(in srgb, var(--area) 19%, var(--global-card-bg-color, #f5f6f7)); outline: 1px solid var(--area); }
.rm-option input { accent-color: var(--area); }
.rm-option small { color: var(--global-text-color); background: color-mix(in srgb, var(--area) 19%, transparent); border-radius: 20px; padding: .23rem .5rem; }
.rm-score { color: var(--rm-score-color,#356b91); font-size: 3.5rem; }
.rm-progress div { background: linear-gradient(90deg,#356b91,#337b76,#557b4e); }
.rm-axis { cursor:pointer; stroke-width: 2; transition: r .2s, fill .2s; }
.rm-axis:focus { outline: none; stroke-width: 4; }
.rm-axis:hover { r: 9; }
.rm-ranges { display:grid; grid-template-columns:repeat(4,1fr); gap:.25rem; margin:.65rem 0 .9rem; font-size:.66rem; text-align:center; }
.rm-ranges span { border-radius: 4px; padding:.4rem .15rem; color:var(--global-text-color); border-top:3px solid var(--range); background:color-mix(in srgb,var(--range) 12%,transparent); }
.rm-pill { border-color:var(--pill); background: color-mix(in srgb,var(--pill) 14%,transparent); }
.rm-actions { display:flex; justify-content:space-between; align-items:center; gap: .7rem; }
.rm-chart { overflow: visible; }
.rm-chart text { font-size: 10px; }
</style>

<div class="rm-shell">
<p class="rm-intro">Interested in working together? Explore the intersection between your research interests and mine. Select the areas you actively work on or intend to investigate, and see how they align with my current research profile.</p>
<div class="rm-grid">
<section class="rm-panel" aria-labelledby="rm-select-title">
<h2 id="rm-select-title">Your research interests</h2>
<p class="rm-note">Select all applicable research areas. The percentages indicate their relative weight in my research profile.</p>
<label class="rm-option" style="--area:#356b91"><input type="checkbox" data-weight="25" data-area="Large Language Models and Generative AI"><span>Large Language Models &amp; Generative AI</span><small>25%</small></label>
<label class="rm-option" style="--area:#337b76"><input type="checkbox" data-weight="20" data-area="Knowledge Graphs and Semantic Ontologies"><span>Knowledge Graphs &amp; Semantic Ontologies</span><small>20%</small></label>
<label class="rm-option" style="--area:#735b9b"><input type="checkbox" data-weight="20" data-area="Trustworthy AI and Factual Reasoning"><span>Trustworthy AI &amp; Factual Reasoning</span><small>20%</small></label>
<label class="rm-option" style="--area:#a34d55"><input type="checkbox" data-weight="15" data-area="Counterfactual and Causal Reasoning"><span>Counterfactual &amp; Causal Reasoning</span><small>15%</small></label>
<label class="rm-option" style="--area:#967033"><input type="checkbox" data-weight="10" data-area="Prediction Markets and Decision Intelligence"><span>Prediction Markets &amp; Decision Intelligence</span><small>10%</small></label>
<label class="rm-option" style="--area:#557b4e"><input type="checkbox" data-weight="10" data-area="Generalisable Machine Ethics and Semantic Reasoning"><span>Generalisable Machine Ethics &amp; Semantic Reasoning</span><small>10%</small></label>
<div class="rm-actions"><button type="button" class="rm-reset" id="rm-clear">Reset selections</button><span id="rm-count" class="rm-note" aria-live="polite">0 of 6 selected</span></div>
</section>
<section class="rm-panel" aria-labelledby="rm-result-title">
<h2 id="rm-result-title">Research alignment</h2>
<div aria-live="polite"><div class="rm-score" id="rm-score">0%</div><div class="rm-band" id="rm-band">Select your research interests</div></div>
<div class="rm-progress" aria-hidden="true"><div id="rm-fill"></div></div><div class="rm-ranges"><span style="--range:#a34d55">0–39%<br>Limited</span><span style="--range:#967033">40–59%<br>Potential</span><span style="--range:#356b91">60–79%<br>Strong</span><span style="--range:#337b76">80–100%<br>Excellent</span></div>
<svg class="rm-chart" id="rm-radar" viewBox="-25 0 410 310" role="img" aria-label="Radar chart of selected interests across six research areas">
<g id="rm-gridlines"></g><polygon class="rm-reference" id="rm-reference"></polygon><polygon class="rm-match" id="rm-match"></polygon><g id="rm-markers"></g>
<text x="180" y="17" text-anchor="middle">LLMs</text><text x="307" y="84" text-anchor="middle">Knowledge graphs</text><text x="307" y="230" text-anchor="middle">Trustworthy AI</text><text x="180" y="300" text-anchor="middle">Causal reasoning</text><text x="52" y="230" text-anchor="middle">Prediction markets</text><text x="52" y="84" text-anchor="middle">Machine ethics</text>
</svg>
<div class="rm-key"><span>– – Research profile</span><span><b>●</b> Shared interests</span></div>
<p class="rm-note" style="text-align:center;margin:.55rem 0">Click or use the keyboard on a coloured radar point to toggle an interest.</p><h2 style="margin-top:1.4rem">Shared research areas</h2>
<div class="rm-shared" id="rm-shared">No areas selected yet.</div>
</section>
</div>
<section class="rm-panel">
<h2>Research collaboration enquiry</h2>
<p>Alignment of 40% or above indicates a potential starting point for a research discussion.</p>
<label for="rm-proposal">Proposed research topic or collaboration idea (optional)</label>
<textarea id="rm-proposal" class="rm-textarea" maxlength="1500" placeholder="Briefly describe the research question, possible collaboration, or relevant experience."></textarea>
<button class="rm-button" id="rm-email" type="button" disabled>Discuss Research Collaboration</button>
<p class="rm-note" id="rm-hint" style="margin-top:.8rem">Select research areas to reach at least 40% alignment and enable the enquiry button.</p>
<p class="rm-note">This is a self-reported, weighted overlap indicator, not a validated psychometric assessment or a decision about eligibility. The radar chart represents selected areas, not expertise levels. Your selections stay in your browser; the enquiry button opens your email application with a draft that you can review and send. Interdisciplinary enquiries are also welcome via my <a href="mailto:abdul.wahid@setu.ie">university email</a>.</p>
</section>
</div>
<script>
(function () {
  const root = document.querySelector('.rm-shell');
  if (!root) return;
  const inputs = Array.from(root.querySelectorAll('input[type="checkbox"]'));
  const byId = id => document.getElementById(id);
  const point = (i, ratio) => {
    const a = -Math.PI / 2 + i * Math.PI / 3;
    return [180 + Math.cos(a) * 110 * ratio, 155 + Math.sin(a) * 110 * ratio];
  };
  const polygon = ratios => ratios.map((r,i) => point(i,r).map(n => n.toFixed(2)).join(',')).join(' ');
  const ns = 'http://www.w3.org/2000/svg';
  [0.25,0.5,0.75,1].forEach(r => {
    const p = document.createElementNS(ns,'polygon');
    p.setAttribute('class','rm-gridline'); p.setAttribute('points',polygon(Array(6).fill(r))); byId('rm-gridlines').appendChild(p);
  });
  for (let i=0;i<6;i++) {
    const line=document.createElementNS(ns,'line'); const p=point(i,1);
    line.setAttribute('x1',180);line.setAttribute('y1',155);line.setAttribute('x2',p[0]);line.setAttribute('y2',p[1]);line.setAttribute('class','rm-gridline');byId('rm-gridlines').appendChild(line);
  }
  byId('rm-reference').setAttribute('points',polygon(Array(6).fill(1)));
  const colours=['#356b91','#337b76','#735b9b','#a34d55','#967033','#557b4e'];
  const markers=inputs.map((input,i)=>{
    const el=document.createElementNS(ns,'circle'); const p=point(i,1);
    el.setAttribute('cx',p[0]);el.setAttribute('cy',p[1]);el.setAttribute('r','7');
    el.setAttribute('class','rm-axis');el.setAttribute('stroke',colours[i]);el.setAttribute('tabindex','0');el.setAttribute('role','button');
    el.setAttribute('aria-label',input.dataset.area);
    const toggle=()=>{input.checked=!input.checked;update();};
    el.addEventListener('click',toggle);
    el.addEventListener('keydown',e=>{if(e.key==='Enter'||e.key===' '){e.preventDefault();toggle();}});
    byId('rm-markers').appendChild(el);return el;
  });
  function chosen(){ return inputs.filter(i=>i.checked); }
  function score(){ return chosen().reduce((s,i)=>s+Number(i.dataset.weight),0); }
  function update(){
    const n=score(); const selected=chosen();
    byId('rm-score').textContent=n+'%';
    root.style.setProperty('--rm-score-color',n>=80?'#337b76':n>=60?'#356b91':n>=40?'#967033':'#a34d55');
    byId('rm-count').textContent=selected.length+' of 6 selected';
    markers.forEach((m,i)=>{m.setAttribute('fill',inputs[i].checked?colours[i]:'var(--global-bg-color, #ffffff)');m.setAttribute('aria-pressed',String(inputs[i].checked));});
    byId('rm-fill').style.width=n+'%';
    byId('rm-band').textContent=n===0?'Select your research interests':n>=80?'Excellent alignment':n>=60?'Strong alignment':n>=40?'Potential interdisciplinary collaboration':'Limited direct alignment';
    byId('rm-match').setAttribute('points',polygon(inputs.map(i=>i.checked?1:0)));
    byId('rm-radar').setAttribute('aria-label','Research alignment radar: '+(selected.map(i=>i.dataset.area).join(', ')||'no shared areas selected'));
    const shared=byId('rm-shared');shared.replaceChildren();
    if(!selected.length) shared.textContent='No areas selected yet.';
    selected.forEach(i=>{const s=document.createElement('span');s.className='rm-pill';s.style.setProperty('--pill',colours[inputs.indexOf(i)]);s.textContent=i.dataset.area;shared.appendChild(s);});
    byId('rm-email').disabled=n<40;
    byId('rm-hint').textContent=n>=40?'Your alignment meets the suggested threshold. Open a draft email to discuss your research idea.':'Select research areas to reach at least 40% alignment and enable the enquiry button.';
  }
  inputs.forEach(i=>i.addEventListener('change',update));
  byId('rm-clear').addEventListener('click',()=>{inputs.forEach(i=>i.checked=false);update();});
  byId('rm-email').addEventListener('click',()=>{
    if(score()<40)return;
    const proposal=byId('rm-proposal').value.trim();
    const body=['Dear Dr Wahid,','','I would like to discuss a potential research collaboration.','','Research alignment: '+score()+'%','Shared interests:',...chosen().map(i=>'- '+i.dataset.area),'','Proposed research idea:',proposal||'[Please describe your idea]','','Kind regards,','[Your name]'].join('\n');
    window.location.href='mailto:abdul.wahid@setu.ie?subject='+encodeURIComponent('Research collaboration enquiry')+'&body='+encodeURIComponent(body);
  });
  update();
})();
</script>
