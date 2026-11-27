---
layout: about
title: About
permalink: /
subtitle: <a class='about-affiliation' href='https://www.setu.ie/'>South East Technological University</a>.

profile:
  align: right
  image: profile-ati-2026-clean.jpeg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><strong>Email:</strong> <a href="mailto:abdul.wahid@setu.ie">abdul.wahid@setu.ie</a></p>
    <p><strong>Address:</strong><br>
    Room No. 3, Portacabin,<br>
    West Campus, Carriganore,<br>
    County Waterford, X91 XD96, Ireland</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

event_gallery:
  enabled: true
  title: A few moments from the event
  images:
    - path: /assets/img/ati-data-study-group-2026-group.jpg
      alt: Data Study Group participants at The Alan Turing Institute
      caption: Data Study Group participants at The Alan Turing Institute, September 2026.
    - path: /assets/img/ati-data-study-group-2026-abdul.jpeg
      alt: Abdul Wahid at The Alan Turing Institute
      caption: At The Alan Turing Institute during the September 2026 Data Study Group.

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
.profile img {
  aspect-ratio: 1 / 1;
  border-radius: 50% !important;
  object-fit: cover;
  object-position: center;
}

.about-affiliation,
.about-social-link,
.profile .more-info a {
  color: #173f5f !important;
  font-weight: 700;
}

.about-affiliation:hover,
.about-social-link:hover,
.profile .more-info a:hover {
  color: #0b2942 !important;
}

.about-social-links {
  align-items: center;
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  line-height: 1.5;
  margin-top: 1rem;
}

.about-social-link {
  align-items: center;
  border-bottom: 2px solid rgba(23, 63, 95, 0.25);
  display: inline-flex;
  gap: 0.35rem;
  line-height: 1.5;
  min-height: 1.5rem;
  padding: 0 0.2rem;
  text-decoration: none;
  vertical-align: middle;
}

.about-social-link i {
  display: inline-block;
  flex: 0 0 1rem;
  font-size: 0.95rem;
  line-height: 1;
  text-align: center;
  width: 1rem;
}

.about-social-link:hover {
  border-bottom-color: #173f5f;
  text-decoration: none;
}

.news .table {
  --bs-table-color: var(--global-text-color);
  color: var(--global-text-color);
}

.news .table > :not(caption) > * > * {
  color: var(--global-text-color);
}

.event-gallery {
  display: grid;
  grid-template-columns: minmax(0, 2fr) minmax(220px, 1fr);
  gap: 1rem;
  margin-bottom: 1.5rem;
}

.event-gallery figure {
  margin: 0;
}

.event-gallery img {
  border-radius: 0.35rem;
  display: block;
  height: auto;
  width: 100%;
}

.event-gallery figcaption {
  color: var(--global-text-color-light);
  font-size: 0.85rem;
  line-height: 1.4;
  margin-top: 0.5rem;
}

@media (max-width: 767px) {
  .event-gallery {
    grid-template-columns: 1fr;
  }
}

.career-timeline { clear: both; padding-top: 1.5rem; margin-bottom: 2rem; }
.career-map { margin-top: 1.2rem; }
.career-primary { max-width: 480px; margin: 0 auto; position: relative; }
.career-node { display: flex; align-items: flex-start; gap: .8rem; padding: 1rem; border: 1px solid var(--global-divider-color, #cbd5e1); border-radius: 8px; background: var(--global-card-bg-color, #f5f6f7); min-width: 0; }
.career-primary .career-node { border: 2px solid #49677e; box-shadow: 0 2px 8px rgba(23,63,95,.08); }
.career-branches { display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem; position: relative; padding-top: 28px; margin-bottom: 1.75rem; }
.career-branches::before { content: ""; position: absolute; top: 0; left: 50%; height: 14px; border-left: 2px solid #a3b4c1; }
.career-branches::after { content: ""; position: absolute; top: 14px; left: 25%; right: 25%; border-top: 2px solid #a3b4c1; }
.career-branch { position: relative; min-width: 0; }
.career-branch::before { content: ""; position: absolute; top: -14px; left: 50%; height: 14px; border-left: 2px solid #a3b4c1; }
.career-label { text-align: center; font-size: .72rem; text-transform: uppercase; letter-spacing: .08em; font-weight: 700; color: var(--global-text-color-light); margin: .45rem 0 .65rem; }
.career-past-label { text-align: left; border-top: 1px solid var(--global-divider-color, #cbd5e1); padding-top: 1rem; }
.career-history { display: grid; grid-template-columns: repeat(2,minmax(0,1fr)); gap: .85rem; }
.career-mark { flex: 0 0 58px; height: 44px; display: flex; align-items: center; justify-content: center; border: 1px solid #b7c5d1; border-radius: 6px; background: #e8edf1; color: #173f5f; font-size: .62rem; font-weight: 800; letter-spacing: .02em; }
.career-content { flex: 1; min-width: 0; }
.career-date { color: var(--global-text-color-light); font-size: .76rem; font-weight: 500; }
.career-role { font-size: .95rem; font-weight: 700; color: var(--global-theme-color); margin: .15rem 0; }
.career-org { font-size: .82rem; color: var(--global-text-color); }
.career-status { font-size: .65rem; font-weight: 700; padding: .15rem .4rem; margin-left: .25rem; border-radius: 4px; background: #dce8e4; color: #245646; }
.career-details { font-size: .8rem; margin-top: .35rem; }
.career-details summary { cursor: pointer; color: var(--global-text-color-light); }
.career-details p { margin: .35rem 0 0; color: var(--global-text-color); }
@media (max-width: 767px) { .career-branches, .career-history { grid-template-columns: 1fr; } .career-branches::before, .career-branches::after, .career-branch::before { display: none; } .career-primary { max-width: none; } .career-branches { padding-top: .5rem; } }

</style>

I am a Lecturer Above the Bar in Computer Science at South East Technological University (SETU), Ireland, and currently a Visiting Lecturer at Nanjing University of Information Science and Technology (NUIST), China. My work spans artificial intelligence, applied research and higher education.

My research explores large language models, knowledge graphs, semantic ontologies, counterfactual reasoning and prediction markets. I am particularly interested in how AI systems reason, where they fail, and how their factual accuracy, reliability and trustworthiness can be improved.

My previous research experience includes the Data Science Institute and Insight Centre for Data Analytics at the University of Galway, Fidelity Investments (as a Research Ireland Industry Fellow), Huawei Research Ireland, Zerve AI and Jeonbuk National University, South Korea. I have also collaborated with The Alan Turing Institute through its Data Study Group on AI-enabled analysis of maritime incident reports. Having worked across academia and industry in Europe and Asia, I am interested in interdisciplinary research and international collaboration that connects advances in AI with practical applications.

<p class="about-social-links"><span>You can find me on</span><a class="about-social-link" href="https://x.com/K_Neeil"><i class="fa-brands fa-x-twitter" aria-hidden="true"></i><span>X</span></a><span>and</span><a class="about-social-link" href="https://www.linkedin.com/in/abdul-wahid-a5a91368/"><i class="fa-brands fa-linkedin" aria-hidden="true"></i><span>LinkedIn</span></a><span>.</span></p>

<section class="career-timeline" aria-labelledby="career-timeline-title">
<h2 id="career-timeline-title">Career &amp; research timeline</h2>
<div class="career-map">
<div class="career-primary"><article class="career-node"><span class="career-mark" aria-hidden="true">SETU</span><div class="career-content"><div class="career-date">Sept 2026 – Present <span class="career-status">Current</span></div><div class="career-role">Lecturer Above the Bar</div><div class="career-org"><a href="https://www.setu.ie/">South East Technological University · Ireland</a></div><details class="career-details"><summary>Research &amp; activities</summary><p>Computer Science teaching and applied AI research.</p></details></div></article></div>
<div class="career-branches">
<div class="career-branch"><div class="career-label">Visiting appointment</div><article class="career-node"><span class="career-mark" aria-hidden="true">NUIST</span><div class="career-content"><div class="career-date">23 Oct – 16 Dec 2026 <span class="career-status">Current</span></div><div class="career-role">Visiting Lecturer</div><div class="career-org"><a href="https://en.nuist.edu.cn/mainm.htm">Nanjing University of Information Science and Technology · China</a></div><details class="career-details"><summary>Research &amp; activities</summary><p>Teaching Developer Operations, Network and System Security, and Distributed Systems.</p></details></div></article></div>
<div class="career-branch"><div class="career-label">Research collaboration</div><article class="career-node"><span class="career-mark" aria-hidden="true">ATI</span><div class="career-content"><div class="career-date">Sept 2026</div><div class="career-role">Data Study Group</div><div class="career-org">The Alan Turing Institute · UK</div><details class="career-details"><summary>Research &amp; activities</summary><p>AI-enabled analysis of maritime incident reports and recurring causal factors.</p></details></div></article></div>
</div>
<div class="career-label career-past-label">Previous research &amp; professional experience</div>
<div class="career-history"><article class="career-node"><span class="career-mark" aria-hidden="true">DSI</span><div class="career-content"><div class="career-date">Until Aug 2026</div><div class="career-role">Postdoctoral Researcher</div><div class="career-org"><a href="https://www.universityofgalway.ie/">Insight Centre &amp; Data Science Institute, University of Galway · Ireland</a></div><details class="career-details"><summary>Research &amp; activities</summary><p>AI, knowledge graphs and e-governance research.</p></details></div></article><article class="career-node"><span class="career-mark" aria-hidden="true">FCAT</span><div class="career-content"><div class="career-date">Jan – Nov 2026</div><div class="career-role">Research Ireland Industry Fellow</div><div class="career-org">Fidelity Investments · Ireland</div><details class="career-details"><summary>Research &amp; activities</summary><p>Factual precision in language models using counterfactual reasoning and knowledge graphs.</p></details></div></article><article class="career-node"><span class="career-mark" aria-hidden="true">ZERVE</span><div class="career-content"><div class="career-date">Sept 2022 – Jul 2023</div><div class="career-role">Data Scientist</div><div class="career-org">Zerve AI · Ireland</div><details class="career-details"><summary>Research &amp; activities</summary><p>Applied machine learning and predictive analytics.</p></details></div></article><article class="career-node"><span class="career-mark" aria-hidden="true">HUAWEI</span><div class="career-content"><div class="career-date">Earlier research</div><div class="career-role">Research Intern</div><div class="career-org">Huawei Research Ireland</div><details class="career-details"><summary>Research &amp; activities</summary><p>Digital twin research and cloud network simulation.</p></details></div></article><article class="career-node"><span class="career-mark" aria-hidden="true">JBNU</span><div class="career-content"><div class="career-date">Earlier research</div><div class="career-role">Associate Researcher</div><div class="career-org"><a href="https://www.jbnu.ac.kr/en/">Jeonbuk National University · South Korea</a></div><details class="career-details"><summary>Research &amp; activities</summary><p>Computer vision research.</p></details></div></article></div>
</div>
</section>
