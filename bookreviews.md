---
layout: default
title: Book Reviews
permalink: /bookreviews/
---

<div class="blog-header">
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

<style>
.blog-header {
  margin-bottom: 1.5rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #3c3c3c;
}

.page-title {
  font-family: 'Outfit', sans-serif;
  font-size: 1.25rem;
  font-weight: 600;
  color: #d4d4d4;
  margin-bottom: 0.25rem;
}

.page-subtitle {
  font-size: 0.8rem;
  color: #858585;
  margin: 0;
}

.posts {
  display: flex;
  flex-direction: column;
}

.post-card {
  display: block;
  padding: 1rem 0;
  border-bottom: 1px solid #3c3c3c;
  text-decoration: none;
  transition: background 0.15s ease;
}

.post-card:hover {
  background: #252526;
  margin: 0 -1rem;
  padding: 1rem;
}

.post-card:hover .post-title {
  color: #4fc1ff;
}

.post-meta {
  margin-bottom: 0.35rem;
  font-size: 0.7rem;
  color: #858585;
}

.post-title {
  font-family: 'Outfit', sans-serif;
  font-size: 0.95rem;
  font-weight: 500;
  color: #d4d4d4;
  margin-bottom: 0.35rem;
  transition: color 0.15s ease;
}

.post-excerpt {
  color: #858585;
  font-size: 0.8rem;
  line-height: 1.5;
  margin: 0;
}

@media screen and (max-width: 768px) {
  .post-card:hover {
    margin: 0;
    padding: 1rem 0;
  }
}
</style>
