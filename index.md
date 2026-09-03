---
layout: home
title: Tooc’s Space
description: My projects, my passions, and things I find interesting.

# EDIT YOUR LINKS HERE
resume_url: "/resume.html"
github_url: "https://github.com/toocmafinh"
projects_url: "/projects/"
chinese_url: "https://drive.google.com/drive/folders/13XSfSfHZnP5MevjA1Y_aWyw1VfoD3qhw?usp=sharing"
academic_url: "https://drive.google.com/drive/folders/17cZZsaq1obDaZgnxnSfROfphtXgekphQ?usp=drive_link"
travel_url: "https://airtable.com/appbVQsPNpk8cOgaa/shrQB4p9XEsWwyLFk/tblqQIOoB6bDiC8aG/viwQKRJW2tzv8sTYB"
blog_url: "https://write.as/phuong"
thread_url: "https://www.threads.com/@tooc.space"
instagram_url: "https://instagram.com/tooc.space"
youtube_url: "https://youtu.be/Sv52Uy5hcas"
---

<header class="page-intro">
  <a class="name-link" href="{{ "/" | relative_url }}">Tooc</a>
  <p>Things around my life, my passion and things I find interesting.</p>
</header>

<main id="links-to-edit" class="space-map" aria-label="Tooc’s portfolio space">
  <h1 class="space-hub">
    <a href="{{ page.youtube_url }}" aria-label="Watch Tooc’s video on YouTube">tooc’s <strong>space</strong></a>
  </h1>

  <div class="link-groups">
    <nav class="link-group work-group" aria-label="Work and profile links">
      <a class="space-link link-about" href="{{ "/about.html" | relative_url }}">About</a>
      <a class="space-link link-resume" href="{{ page.resume_url | relative_url }}">Résumé</a>
      <a class="space-link link-projects" href="{{ page.projects_url | relative_url }}">Projects</a>
    </nav>

    <nav class="link-group interests-group" aria-label="Interests and writing links">
      <a class="space-link link-chinese" href="{{ page.chinese_url }}" lang="zh">中文</a>
      <a class="space-link link-academic" href="{{ page.academic_url }}">Academic<br>writing</a>
      <a class="space-link link-travel" href="{{ page.travel_url | relative_url }}">Travel plans<br>&amp; tips</a>
    </nav>

    <nav class="link-group social-group" aria-label="Social and personal links">
      <a class="space-link link-blog" href="{{ page.blog_url }}">Blog</a>
      <a class="space-link link-instagram" href="{{ page.instagram_url }}">Instagram</a>
      <a class="space-link link-thread" href="{{ page.thread_url }}">Threads</a>
      <a class="space-link link-github" href="{{ page.github_url }}">GitHub</a>
    </nav>
  </div>
</main>
