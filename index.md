---
layout: home
title: Tooc’s Space
description: Phuong Le’s personal space for projects, writing and interests.

# EDIT YOUR LINKS HERE
honeyguide_url: "#links-to-edit"
resume_url: "/resume.html"
github_url: "https://github.com/toocmafinh"
projects_url: "/2023/12/28/las-vegas-hotels.html"
chinese_url: "#links-to-edit"
academic_url: "#links-to-edit"
blog_url: "/2023/12/28/airbnb-review.html"
thread_url: "#links-to-edit"
instagram_url: "#links-to-edit"
imdb_url: "#links-to-edit"
---

<header class="page-intro">
  <a class="name-link" href="{{ "/" | relative_url }}">Phuong Le</a>
  <p>Data, writing and things I find interesting.</p>
  <a href="{{ "/about.html" | relative_url }}">About</a>
</header>

<main id="links-to-edit" class="orbit-stage" aria-label="Tooc’s portfolio space">
  <div class="orbit orbit-inner" aria-hidden="true"></div>
  <div class="orbit orbit-middle" aria-hidden="true"></div>
  <div class="orbit orbit-outer" aria-hidden="true"></div>

  <div class="sun">
    <span>tooc’s</span>
    <strong>space</strong>
  </div>

  <!-- Closest orbit -->
  <a class="node node-honeyguide node-stripes" href="{{ page.honeyguide_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Honeyguide</strong>
    <small>app · AI</small>
  </a>

  <a class="node node-resume node-stripes" href="{{ page.resume_url | relative_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Résumé</strong>
    <small>CV · one-pager</small>
  </a>

  <a class="node node-github node-stripes" href="{{ page.github_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>GitHub</strong>
    <small>code</small>
  </a>

  <a class="node node-projects node-stripes" href="{{ page.projects_url | relative_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Projects</strong>
    <small>work &amp; case studies</small>
  </a>

  <!-- Middle orbit -->
  <a class="node node-chinese node-rings" href="{{ page.chinese_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Chinese</strong>
    <small>language</small>
  </a>

  <a class="node node-academic node-rings" href="{{ page.academic_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Academic writing</strong>
    <small>writing &amp; research</small>
  </a>

  <!-- Outer orbit: edit the URLs in the front matter above -->
  <a class="node outer-node button-blog node-dots" href="{{ page.blog_url | relative_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Blog</strong>
  </a>
  <a class="node outer-node button-thread node-dots" href="{{ page.thread_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Thread</strong>
  </a>
  <a class="node outer-node button-instagram node-dots" href="{{ page.instagram_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>Instagram</strong>
  </a>
  <a class="node outer-node button-imdb node-dots" href="{{ page.imdb_url }}">
    <span class="node-circle" aria-hidden="true"></span>
    <strong>IMDb</strong>
  </a>
</main>
