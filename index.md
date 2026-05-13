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
      Web · IA · Automatisation utile
    </p>

    <h1 class="hero-title">
      J’aide des <span>PME et projets locaux</span> que j’aime
    </h1>

    <p class="hero-subtitle">
      Je suis J.P. Henri — analyste TI et intégrateur IA basé à Gatineau.
      Je fais ça comme hobby : j’aide des PME et des projets locaux que j’apprécie
      avec des sites web simples, de l’automatisation légère et des outils IA utiles.
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
    <h2>Approche terrain</h2>
    <p>
      Pas de formule magique : j’observe, je simplifie et j’ajoute seulement
      la technologie qui aide vraiment.
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
      Projets appliqués sur le terrain : sites web, archives numériques,
      workflows IA, documentation et automatisations légères.
    </p>
    <a href="#projects" class="card-link">Voir les projets →</a>
  </article>

</section>

<!-- Business -->
<section id="business" class="section">
  <h2>Mon approche</h2>
  <p class="section-lead">
    Je ne cherche pas à vendre une méthode avec un nom.
    Je fais surtout ça comme hobby, en aidant des PME et des projets locaux que j’aime,
    avec des solutions simples, réalistes et maintenables.
  </p>

  <p>
    La majorité des PME n’ont pas besoin d’un “gros système”.
    Elles ont besoin de visibilité sur ce qui se passe réellement : courriels, Excel,
    commandes, demandes clients, tâches répétitives… et des petites améliorations qui
    font une grande différence.
  </p>

  <ul>
    <li><strong>Comprendre le terrain</strong> : comment le travail se fait aujourd’hui, pas en théorie.</li>
    <li><strong>Garder ça léger</strong> : enlever la friction avant d’ajouter des outils.</li>
    <li><strong>Automatiser ce qui revient souvent</strong> : seulement si ça sauve du temps ou diminue le risque.</li>
    <li><strong>Utiliser l’IA comme assistant</strong> : contenu, documentation, décisions — pas pour “remplacer du monde”.</li>
    <li><strong>Travailler avec les bonnes personnes</strong> : des projets locaux et des PME avec qui le fit est bon.</li>
  </ul>

  <p>
    Si votre projet me parle, on peut commencer par une courte conversation
    et voir simplement si je peux être utile.
  </p>
</section>

<!-- Projects -->
<section id="projects" class="section">
  <h2>Projets</h2>
  <p class="section-lead">
    Quelques projets concrets en web, IA, automatisation et présence numérique locale.
  </p>

  <section class="projects-grid">

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Projet local · Commerce de proximité</span>
        <h3 class="project-card-title"><a href="https://chezgerry1958.com">Chez Gerry 1958</a></h3>
        <p class="project-card-meta">Cordonnerie haut de gamme · Gatineau</p>
      </div>
      <p class="project-card-desc">
        SEO, contenu avant/après, optimisation Shopify, automatisations légères et structuration du contenu.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Archive hommage · Patrimoine local</span>
        <h3 class="project-card-title"><a href="https://www.guysauriol.ca">guysauriol.ca</a></h3>
        <p class="project-card-meta">Archive vivante · Lutte professionnelle en Outaouais</p>
      </div>
      <p class="project-card-desc">
        Site hommage conçu comme une archive évolutive pour préserver la mémoire de Guy Sauriol :
        biographie, parcours, galerie, archives et contributions du public.
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
        Support TI, développement web et accompagnement de proximité pour PME.
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

  <p class="section-more"><a href="/blog/">Voir tous les articles →</a></p>
</section>

<!-- Contact -->
<section id="contact" class="section section-contact">
  <h2>Contact</h2>
  <p class="section-lead">
    Vous avez une PME ou un projet local et vous pensez qu’on pourrait bien collaborer ?
  </p>

  <p>
    Je prends surtout des projets locaux et des PME avec qui le fit est bon.
    Que ce soit pour un site web, un workflow, de la documentation ou un cas d’usage IA,
    la première étape reste simple : comprendre votre réalité.
  </p>

  <ul class="contact-methods">
    <li>Courriel : <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>
    <li>LinkedIn : <a href="{{ site.social.linkedin }}">LinkedIn</a></li>
  </ul>

  <p>
    Envoyez-moi 3 lignes : qui vous êtes, ce que vous faites, et ce qui vous ralentit en ce moment.
  </p>

  {% include contact-form.html lang="fr" %}
</section>
