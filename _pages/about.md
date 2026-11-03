---
permalink: /
title: ""
excerpt: "Ph.D. Candidate in Economics at the University of Bologna"
author_profile: true
classes: wide
redirect_from:
  - /about/
  - /about.html
---

<script>
document.documentElement.removeAttribute('data-theme');
document.documentElement.setAttribute('data-theme', 'light');
try {
  localStorage.setItem('theme', 'light');
} catch (e) {}
</script>

<style>
:root {
  --tile-blue: #164e87;
  --tile-red: #b83a24;
  --tile-yellow: #d99b26;
  --ink-dark: #18181b;
  --ink-body: #27272a;
  --ink-muted: #52525b;
  --border-warm: #d4d4d8;
  color-scheme: light only;
}
#theme-toggle,
.theme-toggle,
li:has(#theme-toggle),
button[title*="theme" i],
a[title*="theme" i],
.masthead__menu-item:has(.fa-moon),
.masthead__menu-item:has(.fa-sun) {
  display: none !important;
}
html, body, html[data-theme="dark"], body.dark-theme {
  background-color: #ffffff !important;
  color: var(--ink-body) !important;
}
.page__title {
  display: none !important;
}
@media (min-width: 1024px) {
  #main {
    max-width: 1380px !important;
    padding-left: 2rem !important;
    padding-right: 2rem !important;
  }
  .page {
    width: calc(100% - 240px) !important;
    padding-right: 0 !important;
  }
}
.academic-container {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: var(--ink-body);
  line-height: 1.65;
  margin-top: 0.5rem;
}
.hero-section {
  display: flex;
  align-items: center;
  gap: 2.2rem;
  margin: 0 0 1.4rem 0;
}
.profile-hero {
  flex-shrink: 0;
  width: 240px;
  height: 260px;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 10px 25px rgba(24, 24, 27, 0.14);
  border: 4px solid #ffffff;
  background-color: #ffffff;
}
.profile-hero img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 50% 25%;
  display: block;
}
.hero-text {
  flex: 1;
}
.bio-lead {
  font-size: 1.08em;
  color: var(--ink-body);
  margin: 0;
  line-height: 1.7;
}
.bio-lead strong {
  color: var(--ink-dark);
}
.jm-banner {
  width: 100%;
  box-sizing: border-box;
  background-color: #ffffff;
  border: 1px solid var(--border-warm);
  border-left: 5px solid var(--tile-blue);
  padding: 13px 18px;
  border-radius: 0 8px 8px 0;
  font-size: 1.02em;
  color: var(--ink-dark);
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.04);
  margin: 0 0 2.2rem 0;
  text-align: center;
}
.jm-banner strong {
  color: var(--tile-blue);
}
.cv-btn {
  display: inline-block;
  margin-left: 10px;
  padding: 3px 12px;
  background-color: var(--tile-blue);
  color: #ffffff !important;
  font-size: 0.88em;
  font-weight: 600;
  border-radius: 6px;
  text-decoration: none !important;
  transition: background-color 0.2s ease;
}
.cv-btn:hover {
  background-color: var(--tile-red);
}
@media (max-width: 768px) {
  .hero-section {
    flex-direction: column;
    text-align: center;
    gap: 1.25rem;
  }
  .profile-hero {
    width: min(240px, 75vw);
    height: min(260px, 80vw);
    margin: 0 auto;
  }
  .jm-banner {
    border-left: 1px solid var(--border-warm);
    border-top: 4px solid var(--tile-blue);
    border-radius: 8px;
  }
  .cv-btn {
    display: inline-block;
    margin-top: 8px;
    margin-left: 0;
  }
}
.section-heading {
  position: relative;
  font-size: 1.3em;
  font-weight: 700;
  color: var(--ink-dark);
  border-bottom: 2px solid var(--border-warm);
  padding-bottom: 0.45rem;
  margin-top: 2.2rem;
  margin-bottom: 1.1rem;
}
.section-heading::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -2px;
  width: 48px;
  height: 2px;
  background-color: var(--tile-red);
}
.news-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}
.news-list li {
  position: relative;
  padding-left: 1.2rem;
  margin-bottom: 0.65rem;
  color: var(--ink-body);
}
.news-list li::before {
  content: "■";
  position: absolute;
  left: 0;
  top: 1px;
  color: var(--tile-red);
  font-size: 0.65em;
}
details.paper-card {
  background: #ffffff;
  border: 1px solid var(--border-warm);
  border-left: 4px solid transparent;
  border-radius: 10px;
  padding: 15px 20px;
  margin: 1rem 0;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.03);
  transition: all 0.2s ease;
}
details.paper-card:hover {
  border-color: #a1a1aa;
  border-left-color: var(--tile-blue);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
}
details.paper-card[open] {
  border-left: 5px solid var(--tile-blue);
}
details.paper-card.jmp {
  border: 1px solid #b6cce2;
  border-left: 5px solid var(--tile-blue);
  background: #ffffff;
}
details.paper-card summary {
  cursor: pointer;
  font-weight: 700;
  font-size: 1.06em;
  color: var(--ink-dark);
  line-height: 1.4;
  outline: none;
  transition: color 0.15s ease;
}
details.paper-card summary:hover {
  color: var(--tile-blue);
}
.badge-jmp {
  display: inline-block;
  margin-left: 8px;
  padding: 3px 10px;
  border-radius: 999px;
  font-size: 0.74em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.03em;
  background-color: var(--tile-blue);
  color: #ffffff;
  vertical-align: middle;
}
.badge-status {
  display: inline-block;
  margin-left: 8px;
  font-size: 0.86em;
  font-weight: 500;
  color: var(--ink-muted);
}
.coauthor-text {
  font-weight: 400;
  font-size: 0.92em;
  color: var(--ink-muted);
}
.coauthor-text a {
  font-weight: 600;
  color: var(--tile-blue);
  text-decoration: none;
}
.coauthor-text a:hover {
  color: var(--tile-red);
  text-decoration: underline;
}
.abstract-content {
  margin-top: 14px;
  padding-top: 14px;
  border-top: 1px solid #e4e4e7;
  font-size: 0.98em;
  color: var(--ink-body);
  line-height: 1.72;
}
.abstract-content p {
  margin: 0 0 0.85rem 0;
}
.abstract-content p:last-child {
  margin-bottom: 0;
}
.teaching-list {
  display: flex;
  flex-direction: column;
  gap: 0.9rem;
  margin-top: 1rem;
}
.teaching-card {
  background: #ffffff;
  border: 1px solid var(--border-warm);
  border-left: 4px solid var(--tile-yellow);
  border-radius: 10px;
  padding: 15px 20px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.02);
}
.teaching-header {
  font-size: 1.05em;
  font-weight: 700;
  color: var(--ink-dark);
  margin-bottom: 0.55rem;
}
.teaching-role {
  font-weight: 500;
  color: var(--ink-muted);
}
.course-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.course-item {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  padding: 0.3rem 0;
  border-top: 1px dashed #e4e4e7;
  font-size: 0.98em;
  color: var(--ink-body);
}
.course-item:first-child {
  border-top: 1px solid #e4e4e7;
  padding-top: 0.5rem;
}
.course-item:last-child {
  padding-bottom: 0;
}
.course-year {
  font-size: 0.92em;
  font-weight: 600;
  color: var(--tile-blue);
  margin-left: 1rem;
  white-space: nowrap;
}
</style>

<div class="academic-container">
<div class="hero-section">
<div class="profile-hero">
<img src="https://manuelblasco.github.io/images/profile5.png" alt="Manuel Blasco">
</div>
<div class="hero-text">
<div class="bio-lead">
I am a <strong>Ph.D. Candidate in Economics</strong> at the <strong>University of Bologna</strong>. I am a microeconomist working on <strong>Media Economics</strong> and <strong>Political Economy</strong>. My research agenda examines how economic incentives in digital media shape the supply, demand, and quality of information.
</div>
</div>
</div>

<div class="jm-banner">
<strong>I will be on the Academic Job Market 2026-2027.</strong>
<a href="/files/cv.pdf" class="cv-btn" target="_blank" rel="noopener noreferrer">Download CV (PDF)</a>
</div>

<h3 class="section-heading">News &amp; Upcoming</h3>
<ul class="news-list">
<li><strong>Spring 2026:</strong> Visiting <strong>Princeton University</strong> as a Visiting Student Research Collaborator.</li>
<li><strong>December 2025:</strong> Presented my Job Market Paper at the <strong>CEPR Paris Symposium 2025</strong>.</li>
</ul>

<h3 class="section-heading">Working Papers</h3>

<details class="paper-card jmp">
<summary>
Headline Selection and Misleading Information
<span class="badge-jmp">Job Market Paper</span>
<span class="badge-status">Draft available upon request</span>
</summary>
<div class="abstract-content">
<p>
Online news markets separate the headline from the article it represents: the headline circulates freely, while access to the article may require payment. Because many readers consume news through headlines alone, the headline is often the only part of the news they ever see. I develop a model in which a profit-maximizing outlet observes a truthful article, publishes one of its components as the headline, and charges for access to the rest. The outlet selects the component that leaves readers with the most residual uncertainty about the article's conclusion. In equilibrium, this mechanism generates misleading headlines: truthful headlines that induce rational headline-only readers to take actions contrary to those they would take after reading the full article. The model predicts that more informative articles have more informative headlines, that greater internal heterogeneity reduces headline–article alignment, and that this disclosure rule is invariant to whether readership is monetized through subscriptions or advertising. I evaluate these predictions using two corpora comprising more than 440,000 headline–article pairs from major English-language newspapers. A scalable semantic procedure measures informativeness, article heterogeneity, and headline–article alignment. In the cross-section, more informative articles have more informative headlines, while more heterogeneous articles have more specific but less aligned headlines. A difference-in-differences analysis of the 2011 <em>New York Times</em> paywall finds no change in alignment relative to <em>The Guardian</em>. Together, the results identify a source of media bias arising from the truthful but strategic selection of headlines.
</p>
</div>
</details>

<h3 class="section-heading">Work in Progress</h3>

<details class="paper-card">
<summary>
Pick or Make? Editorial Placement and the Demand for News
<span class="badge-status">(First draft coming soon)</span>
</summary>
<div class="abstract-content">
<p>
Articles prominently displayed on a newspaper's homepage attract the most readers, but does prominence reflect consumer appeal or create it? I study how editorial curation shapes public attention using a novel year-long panel of all articles published by the New York Times, hourly homepage snapshots, and daily most-read rankings. Exploiting within-article variation in placement across days and testing for dynamic selection, I find that editors make rather than pick winners: selection on unobserved appeal explains at most 7 percent of the prominence premium, whereas high homepage exposure multiplies an article's odds of being read fourteenfold. Estimating a rank-ordered demand model, I simulate counterfactual homepages to price editorial gatekeeping. Relative to a click-maximizing benchmark, human editors knowingly forgo predictable readership—primarily on U.S. politics and yesterday's viral stories—to reserve prime display space for fresh international and business reporting.
</p>
</div>
</details>

<details class="paper-card">
<summary>
Civil Rights Riots and Fiscal Transfers in the U.S.
<span class="coauthor-text">
(with <a href="https://sites.google.com/view/mgeiras/inicio" target="_blank" rel="noopener noreferrer">Martin Gonzalez-Eiras</a>)
</span>
</summary>
<div class="abstract-content">
<p>
How do governments adjust the allocation of resources in the face of civil unrest? We study the fiscal response to the U.S. 1960s racial riots, mapping the near-universe of race-related civil disturbances to annual Community Action Program (CAP) transfers at the commuting zone (CZ) level. We find that riot severity—not mere occurrence—is associated with an increase in transfers to the affected CZ the following fiscal year, a result robust across empirical specifications. Greater riot severity in neighboring, same-state, CZs reduces a CZ's own transfers, suggesting that government's reaction to unrest thus took the form of a reallocation of antipoverty funds across poor communities. To disentangle whether the relation between rioting activity and transfers is direct, or mediated through media coverage of these events, we add a measure of media reporting and find that its effect is negligible.
</p>
</div>
</details>

<details class="paper-card">
<summary>
The Curse of Popularity: Endogenous Agendas and Media Bias
</summary>
<div class="abstract-content">
<p>
I develop a model where media outlets jointly choose which topic to cover (agenda setting) and how to report (editorial slant) under limited consumer attention. I characterize the conditions under which a “curse of popularity” emerges: when a topic becomes sufficiently popular, competing outlets converge on that same issue and—rather than conveying the most informative coverage—have incentives to introduce editorial bias, crowding out other topics and reducing welfare. By contrast, when attention is more dispersed, outlets tend to specialize across topics and (in equilibrium) report more truthfully, improving informational quality and decision-making.
</p>
</div>
</details>

<h3 class="section-heading">Teaching</h3>
<div class="teaching-list">
<div class="teaching-card">
<div class="teaching-header">
University of Bologna <span class="teaching-role">— Teaching Assistant</span>
</div>
<ul class="course-list">
<li class="course-item">
<span>Health Econometrics</span>
<span class="course-year">2025</span>
</li>
<li class="course-item">
<span>Macroeconomics</span>
<span class="course-year">2024</span>
</li>
</ul>
</div>

<div class="teaching-card">
<div class="teaching-header">
Johns Hopkins University SAIS Europe <span class="teaching-role">— Teaching Assistant</span>
</div>
<ul class="course-list">
<li class="course-item">
<span>Quantitative Research Methods</span>
<span class="course-year">2024</span>
</li>
<li class="course-item">
<span>Statistics for Data Analysis</span>
<span class="course-year">2023</span>
</li>
</ul>
</div>

<div class="teaching-card">
<div class="teaching-header">
National University of Córdoba <span class="teaching-role">— Teaching Assistant</span>
</div>
<ul class="course-list">
<li class="course-item">
<span>International Economics</span>
<span class="course-year">2014, 2016</span>
</li>
</ul>
</div>
</div>
</div>
