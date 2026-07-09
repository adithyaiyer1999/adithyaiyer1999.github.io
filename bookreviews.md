---
layout: default
title: Book Reviews
permalink: /bookreviews/
---

<div class="page-header">
  <h1 class="page-title">Book Reviews</h1>
  <p class="page-subtitle">Thoughts on books I've read</p>
</div>

<div class="posts">
  {% for post in site.bookreviews %}
  <a href="{{ site.baseurl }}{{ post.url }}" class="post-card">
    <div class="post-meta">
      <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
    </div>
    <h2 class="post-title">{{ post.title }}</h2>
    <p class="post-excerpt">{{ post.excerpt | strip_html | truncate: 160 }}</p>
  </a>
  {% endfor %}
</div>
