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

<style>
  /* Variables de color extraídas de tu foto */
  :root {
    --tile-blue: #164e87;       /* Azul cobalto de las baldosas */
    --tile-red: #b83a24;        /* Rojo terracota/ladrillo de las baldosas */
    --tile-yellow: #d99b26;     /* Amarillo mostaza de las baldosas */
    --ink-dark: #18181b;        /* Negro carbón (abrigo y líneas del piso) */
    --ink-body: #27272a;        /* Gris tinta para lectura cómoda */
    --ink-muted: #52525b;       /* Gris medio para notas secundarias */
    --border-warm: #d4d4d8;     /* Borde neutro */
  }

  /* Oculta el título grande redundante de la plantilla */
  .page__title {
    display: none !important;
  }

  /* Ensancha el contenedor general de la plantilla en pantallas de computadora */
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

  /* Contenedor general */
  .academic-container {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: var(--ink-body);
    line-height: 1.65;
    margin-top: 0.5rem;
  }

  /* Fila superior: Foto a la izquierda + Bio alineada a la derecha */
  .hero-section {
    display: flex;
    align-items: center;
    gap: 2.2rem;
    margin: 0 0 1.4rem 0;
  }

  /* Foto en formato retrato rectangular */
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

  /* Contenedor de texto de la bio */
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

  /* Banner del Job Market a lo ancho de ambas columnas (en Azul Cobalto) */
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
  }
  .jm-banner strong {
    color: var(--tile-blue);
  }

  /* Adaptación automática para Celulares y Tablets pequeñas */
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
      text-align: center;
    }
  }

  /* Títulos de sección con subrayado bicolor (Terracota + Gris) */
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

  /* Lista de noticias */
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

  /* Tarjetas de Papers */
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

  /* Etiquetas (Badges) - Fondo de Job Market Paper en Azul Cobalto */
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

  /* Contenido del Abstract */
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
</style>

<div class="academic-container">

  <!-- Fila 1: Foto a la izquierda + Bio centrada verticalmente a la derecha -->
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

  <!-- Fila 2: Banner de Job Market ocupando el ancho total debajo de ambas columnas -->
<div class="jm-banner">
  <strong>I will be on the Academic Job Market 2026-2027</strong>.
</div>

<style>
  .jm-banner {
    text-align: center;
  }
</style>

  <h3 class="section-heading">News &amp; Upcoming</h3>
  <ul class="news-list">
    <li><strong>Spring 2026:</strong> Visiting <strong>Princeton University</strong> as a Visiting Student Research Collaborator.</li>
    <li><strong>December 2025:</strong> Presented my Job Market Paper at the <strong>CEPR Paris Symposium 2025</strong>.</li>
  </ul>

  <h3 class="section-heading">Working Papers</h3>

  <!-- Job Market Paper (Cerrado por defecto) -->
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

  <!-- WIP 1 (Movido desde Working Papers) -->
  <details class="paper-card">
    <summary>
      Pick or Make? Editorial Placement and the Demand for News
      <span class="badge-status">(First draft coming soon)</span>
    </summary>
    <div class="abstract-content">
      <p>
        Articles at the top of a newspaper’s homepage attract far more readers than those lower down. Do editors select articles that readers would have chosen anyway, or does prominent placement itself shape what gets read? I combine a year of daily data from The New York Times—covering every article published, daily rankings of the most-read articles, and hourly snapshots of the homepage. I exploit within-article variation in placement by comparing each article with itself across days as editors move it around the homepage. High exposure, defined as placement in the most prominent third of the homepage for much of the day, increases an article’s probability of appearing on the most-read list by roughly a factor of ten. Editors’ selection of intrinsically appealing articles explains between zero and about 7 percent of this premium. A demand model estimated on the daily rankings implies that high exposure is equivalent to roughly twenty standard deviations of article length, the content characteristic to which readers respond most strongly. Counterfactual homepages simulated from the model indicate that placement determines about half of the most-read list. A click-maximizing allocation of the same slots would favor day-old US politics over the fresh international and business news that editors prioritize, increasing the appeal of the articles read by the equivalent of about one standard deviation of article length. Although the appeal of a new article can be predicted out of sample, primarily from its topic, editors respond only weakly to these predictions. Among the articles a newspaper publishes, editors therefore exert substantial influence over which are read, but appear to exercise this influence in pursuit of freshness and importance rather than clicks.
      </p>
    </div>
  </details>

  <!-- WIP 2 -->
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

  <!-- WIP 3 -->
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

</div>
