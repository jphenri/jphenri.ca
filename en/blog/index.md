---
layout: page
title: "Blog"
subtitle: "Notes, tests and write-ups"
nav_key: blog
lang: en
fr_url: /blog/
---

<div class="blog-banner blog-header-animated">

<h2>📝 Welcome to the Blog (EN)</h2>

<p>
Here I share notes, experiments and lessons learned around:
</p>

<ul>
  <li><strong>Applied AI</strong> (for small businesses, automation, practical tools)</li>
  <li><strong>DevOps / IT</strong> (Intune, Linux, security)</li>
  <li><strong>Home Lab</strong> (lab tests, Plex, gaming, distros)</li>
  <li><strong>Small businesses & local projects</strong> (web presence, useful tools, real cases)</li>
</ul>

<p>
Everything here is based on <strong>real-world work and lab experiments</strong> – not theory.
</p>

</div>


<section class="latest-posts">
  <h2>Latest posts</h2>

  {% assign posts_en = site.posts | where: "lang", "en" | sort: "date" | reverse %}

  {% if posts_en.size == 0 %}
    <p class="latest-posts-empty">
      No English posts yet. First one is coming soon.
    </p>
  {% else %}
    <div class="latest-posts-grid">
      {% for post in posts_en limit:5 %}
      <article class="post-card">
        <h3>
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </h3>
        <p class="post-card-meta">
          {{ post.date | date: "%Y-%m-%d" }}
        </p>
        {% if post.excerpt %}
          <p class="post-card-excerpt">
            {{ post.excerpt | strip_html | truncate: 150 }}
          </p>
        {% endif %}
        <a class="post-card-link" href="{{ post.url | relative_url }}">
          Read more →
        </a>
      </article>
      {% endfor %}
    </div>
  {% endif %}
</section>

---
