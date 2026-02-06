---
layout: default
title: CV
permalink: /cv/
---

<div class="cv-page">
  <div class="cv-header">
    <h1 class="page-title">
      <span class="title-prefix">~/curriculum-vitae</span>
      <span class="cursor">_</span>
    </h1>
    <p class="page-subtitle">My professional journey and qualifications</p>
  </div>
  
  <div class="cv-content">
    <div class="cv-card">
      <div class="cv-icon">📄</div>
      <div class="cv-info">
        <h2>Download CV</h2>
        <p>Get my full curriculum vitae in PDF format</p>
        <a href="{{ site.baseurl }}/Adithya_CV_2025_Updated.pdf" target="_blank" class="cv-button">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          <span>Download PDF</span>
        </a>
      </div>
    </div>
  </div>
</div>

<style>
.cv-page {
  max-width: 600px;
  margin: 0 auto;
}

.cv-header {
  text-align: center;
  margin-bottom: 3rem;
}

.page-title {
  font-family: 'JetBrains Mono', monospace;
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  display: inline-flex;
  align-items: center;
}

.title-prefix {
  background: linear-gradient(135deg, #22d3ee, #a855f7);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.cursor {
  color: #22d3ee;
  animation: blink 1s step-end infinite;
}

@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0; }
}

.page-subtitle {
  font-size: 1rem;
  color: #71717a;
  margin: 0;
}

.cv-card {
  display: flex;
  align-items: center;
  gap: 2rem;
  padding: 2rem;
  background: #16161e;
  border: 1px solid #27272a;
  border-radius: 16px;
}

.cv-icon {
  font-size: 4rem;
}

.cv-info h2 {
  font-family: 'Outfit', sans-serif;
  font-size: 1.5rem;
  color: #e4e4e7;
  margin-bottom: 0.5rem;
  background: none;
  -webkit-text-fill-color: #e4e4e7;
}

.cv-info p {
  color: #71717a;
  margin-bottom: 1.5rem;
}

.cv-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.875rem 1.5rem;
  background: linear-gradient(135deg, #22d3ee, #a855f7);
  color: #0a0a0f;
  font-family: 'JetBrains Mono', monospace;
  font-weight: 600;
  font-size: 0.875rem;
  border-radius: 8px;
  text-decoration: none;
  transition: all 0.25s ease;
}

.cv-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 30px -10px rgba(34, 211, 238, 0.5);
  color: #0a0a0f;
  text-shadow: none;
}

@media screen and (max-width: 768px) {
  .cv-card {
    flex-direction: column;
    text-align: center;
  }
  
  .page-title {
    font-size: 1.5rem;
  }
}
</style>
