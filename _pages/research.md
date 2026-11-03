---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---

<style>
:root {
  --tile-blue: #164e87;
  --tile-red: #b83a24;
  --ink-dark: #18181b;
  --ink-body: #27272a;
  --ink-muted: #52525b;
  --border-warm: #d4d4d8;
}
.page__title {
  display: none !important;
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
</style>

<h2 class="section-heading" style="margin-top:0;">Working Papers</h2>

<details class="paper-card jmp">
  <summary>
    Strategic Headline Selection
    <span class="badge-jmp">Job Market Paper</span>
    <span class="badge-status">Draft available upon request</span>
  </summary>
  <div class="abstract-content">
    <p>
      Online news markets separate the headline from the article it represents: the headline circulates freely, while access to the article may require payment. Because many readers consume news through headlines alone, the headline is often the only part of the news they ever see. I develop a model in which a profit-maximizing outlet observes a truthful article, publishes one of its components as the headline, and charges for access to the rest. The outlet selects the component that leaves readers with the most residual uncertainty about the article's conclusion. In equilibrium, this mechanism generates misleading headlines: truthful headlines that induce rational headline-only readers to take actions contrary to those they would take after reading the full article. The model predicts that more informative articles have more informative headlines, that greater internal heterogeneity reduces headline–article alignment, and that this disclosure rule is invariant to whether readership is monetized through subscriptions or advertising. I evaluate these predictions using two corpora comprising more than 440,000 headline–article pairs from major English-language newspapers. A scalable semantic procedure measures informativeness, article heterogeneity, and headline–article alignment. In the cross-section, more informative articles have more informative headlines, while more heterogeneous articles have more specific but less aligned headlines. A difference-in-differences analysis of the 2011 <em>New York Times</em> paywall finds no change in alignment relative to <em>The Guardian</em>. Together, the results identify a source of media bias arising from the truthful but strategic selection of headlines.
    </p>
  </div>
</details>

<details class="paper-card">
  <summary>
    Pick or Make? Editorial Placement and the Demand for News
    <span class="badge-status">Draft available upon request</span>
  </summary>
  <div class="abstract-content">
    <p>
      Articles prominently displayed on a newspaper's homepage attract the most readers. Because editors place articles according to their news value, how much of this premium is the effect of placement itself? I study how editorial placement shapes public attention using a year-long panel of all articles published by the New York Times, hourly homepage snapshots, and daily most-read rankings. I exploit within-article variation in placement across days and test whether placements track time-varying appeal. The premium reflects placement itself: appeal beyond an article's topic, timing, and measured content explains at most 7 percent of it, whereas high homepage exposure raises an article's probability of reaching the most-read list roughly tenfold. I then estimate a rank-ordered model of demand for articles from the daily menu and simulate counterfactual homepages to price editorial curation. Relative to a click-maximizing allocation of the same slots, editors forgo predictable readership to reserve prime display space for fresh international and business reporting. The readership they forgo lies mainly in U.S. politics and in stories at the peak of their readership cycle, typically a day after publication.
    </p>
  </div>
</details>

<h2 class="section-heading">Work in Progress</h2>

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
