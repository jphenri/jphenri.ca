---
layout: home
title: "Home"
nav_key: home
lang: en
fr_url: /
---

<!-- 🔥 Hero -->
<section class="hero">
  <div class="hero-inner">
    <p class="hero-kicker">Web · AI · Useful automation</p>

    <h1 class="hero-title">
      I help <span>small businesses and local projects</span> I genuinely care about
    </h1>

    <p class="hero-subtitle">
      I’m J.P. Henri — IT analyst and AI systems consultant based in Gatineau.
      I do this as a hobby: helping local projects and small businesses I like
      with simple websites, light automation and practical AI tools.
    </p>

    <div class="hero-actions">
      <a href="#business" class="btn btn-primary">Explore the approach</a>
      <a href="#contact" class="btn btn-ghost">Start a conversation</a>
    </div>
  </div>
</section>

<!-- 🔥 Cards -->
<section class="cards-grid">

  <article class="card">
    <h2>Practical approach</h2>
    <p>No magic formula: I observe, simplify and only add technology when it clearly helps.</p>
    <a href="#business" class="card-link">See the approach →</a>
  </article>

  <article class="card">
    <h2>Marketing & Content Automation</h2>
    <p>AI systems to help you produce blog posts, social content and video scripts — without burning out.</p>
    <a href="#blog" class="card-link">See examples →</a>
  </article>

  <article class="card">
    <h2>Applied Projects</h2>
    <p>
      Real work on the ground: websites, digital archives, AI workflows,
      documentation systems and lightweight automation.
    </p>
    <a href="#projects" class="card-link">View projects →</a>
  </article>

</section>

<!-- 🔥 Approach -->
<section id="business" class="section">
  <h2>How I work</h2>
  <p class="section-lead">
    I’m not trying to sell a named framework.
    This is mostly a hobby for me: I help local projects and small businesses I genuinely like,
    using simple, realistic and maintainable solutions.
  </p>

  <p>
    Most small businesses don’t need a dozen new tools — they need <strong>clarity</strong>,
    less repetitive work, and better visibility on what truly matters. My work starts from
    what already exists: the shop floor, the inbox, spreadsheets, and customer conversations.
    Then we add just enough structure, automation and AI to create measurable improvement.
  </p>

  <ul>
    <li><strong>Understand reality</strong>: how work actually flows today (not how it “should” work).</li>
    <li><strong>Keep it light</strong>: remove friction before adding new systems.</li>
    <li><strong>Add targeted automation</strong>: only where it saves real time or reduces risk.</li>
    <li><strong>Use AI as an assistant</strong>: for content, documentation and decision support — not to replace people.</li>
    <li><strong>Work with the right people</strong>: local projects and small businesses where the fit is good.</li>
  </ul>

  <p>
    If a project feels like a good fit, we can start with a simple conversation
    and see whether I can be useful.
  </p>
</section>

<!-- 🔥 Projects -->
<section id="projects" class="section">
  <h2>Projects</h2>
  <p class="section-lead">
    Examples of web, AI, automation and local digital projects tied to real people and concrete outcomes.
  </p>

  <section class="projects-grid">

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Local project · Small business</span>
        <h3 class="project-card-title">
          <a href="https://chezgerry1958.com" target="_blank">Chez Gerry 1958</a>
        </h3>
        <p class="project-card-meta">Premium shoe restoration · Gatineau, Québec</p>
      </div>
      <p class="project-card-desc">
        Long-term digital transformation for a high-end cobbler: website, clear service catalog,
        local SEO, before/after content, and backend workflows that simplify mail-in repairs.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Tribute archive · Local heritage</span>
        <h3 class="project-card-title">
          <a href="https://www.guysauriol.ca" target="_blank">guysauriol.ca</a>
        </h3>
        <p class="project-card-meta">Living archive · Outaouais pro wrestling</p>
      </div>
      <p class="project-card-desc">
        Tribute site built as a living archive for Guy Sauriol: biography, timeline, gallery,
        archival material and public contributions that preserve local wrestling history.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">Static site · Food</span>
        <h3 class="project-card-title">
          <a href="https://chucks-casse-croute.com" target="_blank">Chuck’s Casse-Croute</a>
        </h3>
        <p class="project-card-meta">Lightweight restaurant website · GitHub Pages</p>
      </div>
      <p class="project-card-desc">
        Fast, minimal and low-maintenance website for a local restaurant.
        Demonstrates how a small business can look professional online without a heavy CMS.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">E-commerce · Outdoor</span>
        <h3 class="project-card-title">
          <a href="https://web.archive.org/web/20171012223444/https://www.pronatureqc.com/" target="_blank">
            Pronatureqc.com (2015–2018)
          </a>
        </h3>
        <p class="project-card-meta">Full online store · Archived</p>
      </div>
      <p class="project-card-desc">
        Large-catalog e-commerce project: navigation, product content, SEO structure and performance,
        aligned with brand identity.
      </p>
    </article>

    <article class="project-card">
      <div class="project-card-header">
        <span class="project-badge">IT Consulting</span>
        <h3 class="project-card-title">
          <a href="https://web.archive.org/web/20181229095915/https://assystech.com/" target="_blank">
            Assystech SENC (2015–2019)
          </a>
        </h3>
        <p class="project-card-meta">Consulting · Web development</p>
      </div>
      <p class="project-card-desc">
        Co-founded IT consulting and web development firm working with SMEs on infrastructure,
        custom websites and ongoing support.
      </p>
      <p class="project-card-desc">
        This experience shaped how I like to help: long-term relationships, plain language,
        and solutions aligned with real constraints.
      </p>
    </article>

  </section>
</section>

<!-- 🔥 Blog -->
<section id="blog" class="section">
  <h2>Blog</h2>
  <p class="section-lead">Recent English posts.</p>

  <div class="latest-posts-grid">
    {% assign posts_en = site.posts | where: "lang", "en" | sort: "date" | reverse %}
    {% for post in posts_en limit:3 %}
      <article class="post-card">
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p class="post-card-meta">{{ post.date | date: "%Y-%m-%d" }}</p>
        <p class="post-card-excerpt">{{ post.excerpt | strip_html | truncate: 150 }}</p>
      </article>
    {% endfor %}
  </div>

  <p class="section-more"><a href="/en/blog/">View all posts →</a></p>
</section>

<!-- 🔥 Contact -->
<section id="contact" class="section section-contact">
  <h2>Contact</h2>
  <p class="section-lead">
    Do you run a small business or local project and think we might be a good fit?
  </p>
  <p>
    I mostly take on local projects and small businesses I genuinely enjoy helping.
    Whether it’s a website, workflow, documentation or an AI use case, the first step is understanding your reality.
  </p>
  <ul class="contact-methods">
    <li>Email: <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>
    <li>LinkedIn: <a href="{{ site.social.linkedin }}">LinkedIn</a></li>
  </ul>
  <p>
    You don’t need a full brief. A few lines about who you are, what you do and what’s slowing you down is enough to start.
  </p>

  {% include contact-form.html lang="en" %}
</section>
