---
layout: home
title: "Accueil"
nav_key: home
lang: fr
en_url: /en/
---

<!-- 🔥 Hero -->
<section class="hero">
  <div class="hero-inner">
    <p class="hero-kicker">
      IA · Automatisation · Transformation numérique
    </p>

    <h1 class="hero-title">
      Construire le <span>Business 2.0</span> — version PME
    </h1>

    <p class="hero-subtitle">
      Je suis J.P. Henri — analyste TI et intégrateur IA basé à Gatineau.
      J’aide les petites entreprises à gagner du temps, structurer leurs opérations
      et produire plus de marketing grâce à des systèmes simples (pas des usines à gaz).
    </p>

    <div class="hero-actions">
      <a href="#business" class="btn btn-primary">Voir l’approche</a>
      <a href="#contact" class="btn btn-ghost">Réserver un appel</a>
    </div>
  </div>
</section>

<!-- 🔥 Cards -->
<section class="cards-grid">

  <article class="card">
    <h2>Business 2.0 pour PME</h2>
    <p>
      Audit rapide, optimisation de processus, automatisation des tâches répétitives,
      et intégration d’IA (contenu, emails, documentation, opérations).
    </p>
    <a href="#business" class="card-link">Découvrir l’approche →</a>
  </article>

  <article class="card">
    <h2>Automatisation du marketing</h2>
    <p>
      Système IA pour produire plus de contenu (blog, réseaux sociaux, scripts vidéo),
      sans y passer vos soirées — et sans perdre votre ton.
    </p>
    <a href="#blog" class="card-link">Voir des exemples →</a>
  </article>

  <article class="card">
    <h2>Projets concrets</h2>
    <p>
      Projets appliqués sur le terrain : e-commerce, SEO local, sites rapides,
      workflows IA, documentation et automatisations légères.
    </p>
    <a href="#projects" class="card-link">Voir les projets →</a>
  </article>

</section>

<!-- Business -->
<section id="business" class="section">
  <h2>Business 2.0</h2>
  <p class="section-lead">
    Business 2.0, c’est une approche simple : clarifier, alléger, automatiser, puis mesurer.
    L’objectif : gagner du temps, réduire les erreurs, et mieux servir vos clients.
  </p>

  <p>
    La majorité des PME n’ont pas besoin d’un “gros système”.
    Elles ont besoin de visibilité sur ce qui se passe réellement : courriels, Excel,
    commandes, demandes clients, tâches répétitives… et des petites améliorations qui
    font une grande différence.
  </p>

  <ul>
    <li><strong>Comprendre le terrain</strong> : comment le travail se fait aujourd’hui, pas en théorie.</li>
    <li><strong>Alléger avant d’ajouter</strong> : enlever la friction avant d’ajouter des outils.</li>
    <li><strong>Automatiser ce qui revient souvent</strong> : seulement si ça sauve du temps ou diminue le risque.</li>
    <li><strong>Utiliser l’IA comme assistant</strong> : contenu, documentation, décisions — pas pour “remplacer du monde”.</li>
    <li><strong>Mesurer l’impact</strong> : temps gagné, erreurs réduites, clients mieux servis.</li>
  </ul>

  <p>
    Si vous êtes à Gatineau/Ottawa, on peut commencer par un appel rapide :
    je vous pose 10 questions, et je vous propose un plan clair.
  </p>
</section>

<!-- Projects -->
<section id="projects" class="section">
  <h2>Projets</h2>
  <p class="section-lead">
    Quelques projets concrets où j’applique Business 2.0, web, IA et automatisation.
  </p>

  <section class="projects-grid">

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Business 2.0 · Commerce local</span>
        <h3 class="project-card-title"><a href="https://chezgerry1958.com">Chez Gerry 1958</a></h3>
        <p class="project-card-meta">Cordonnerie haut de gamme · Gatineau</p>
      </div>
      <p class="project-card-desc">
        SEO, contenu avant/après, optimisation Shopify, automatisations légères et structuration du contenu.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Site statique</span>
        <h3 class="project-card-title"><a href="https://chucks-casse-croute.com">Chuck’s Casse-Croute</a></h3>
        <p class="project-card-meta">Vitrine légère · GitHub Pages</p>
      </div>
      <p class="project-card-desc">
        Site rapide, simple, sans CMS, pensé mobile et local.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">E-commerce</span>
        <h3 class="project-card-title"><a href="https://web.archive.org/...">Pronatureqc.com (2015–2018)</a></h3>
        <p class="project-card-meta">Boutique en ligne · Archive</p>
      </div>
      <p class="project-card-desc">
        Catalogue, SEO, paiements, optimisation de parcours d’achat.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Consultation TI</span>
        <h3 class="project-card-title"><a href="https://web.archive.org/...">Assystech SENC</a></h3>
        <p class="project-card-meta">Dév. Web · Infra</p>
      </div>
      <p class="project-card-desc">
        Support et optimisation TI pour PME.
      </p>
    </article>

  </section>
</section>

<!-- Blog -->
<section id="blog" class="section">
  <h2>Blog</h2>
  <p class="section-lead">Derniers articles en français.</p>

  <div class="latest-posts-grid">
    {% assign posts_fr = site.posts | where: "lang", "fr" | sort: "date" | reverse %}
    {% for post in posts_fr limit:3 %}
      <article class="post-card">
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p class="post-card-meta">{{ post.date | date: "%Y-%m-%d" }}</p>
        <p class="post-card-excerpt">{{ post.excerpt | strip_html | truncate: 150 }}</p>
      </article>
    {% endfor %}
  </div>

  <p class="section-more"><a href="/fr/blog/">Voir tous les articles →</a></p>
</section>

<!-- Contact -->
<section id="contact" class="section section-contact">
  <h2>Contact</h2>
  <p class="section-lead">
    Vous avez une idée, mais vous ne savez pas par où commencer ?
  </p>

  <p>
    On peut démarrer simple : une discussion de 20–30 minutes pour clarifier
    votre contexte, vos blocages, et où l’IA/automatisation peut réellement aider.
  </p>

  <ul>
    <li>🔗 LinkedIn: <a href="https://www.linkedin.com/in/jphenriIT/">LinkedIn</a></li>
  </ul>

  <p>
    Envoyez-moi 3 lignes : qui vous êtes, ce que vous faites, et ce qui vous ralentit en ce moment.
  </p>
</section>
