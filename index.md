---
layout: home
title: Christoph Huy
subtitle: Software Security · AI · Fuzzing · System Design
---

<!-- Navigation -->
<nav class="nav-bar">
  <div class="nav-content">
    <a href="/" class="nav-brand">
      <span class="nav-logo">C</span>
      <span class="nav-name">Christoph Huy</span>
    </a>
    <div class="nav-links">
      <a href="/research" class="nav-link">Research</a>
      <a href="/projects" class="nav-link">Projects</a>
      <a href="/cv" class="nav-link">CV</a>
      <a href="https://github.com/Perimora" target="_blank" class="nav-link external">
        <i class="fab fa-github"></i>
      </a>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero-container">
  <div class="hero-content">
    <img src="assets/profile.jpg" alt="Christoph Huy" class="hero-profile" />
    <h1 class="hero-title">Christoph Huy</h1>
    <p class="hero-subtitle">Software Security · AI · Fuzzing · System Design</p>
    <p class="hero-intro">
      I'm a Master's student in Computer Science at TU Berlin focusing on <strong>software security</strong>, 
      <strong>AI-driven fuzzing</strong>, and the design of robust, testable systems. I build tools, frameworks, 
      and pipelines that combine deep technical insight with practical engineering.
    </p>
    <div class="hero-cta">
      <a href="/projects" class="cta-button primary">
        <i class="fas fa-code"></i>
        View Projects
      </a>
      <a href="/research" class="cta-button">
        <i class="fas fa-microscope"></i>
        Research
      </a>
      <a href="/cv" class="cta-button">
        <i class="fas fa-file-alt"></i>
        CV
      </a>
    </div>
  </div>
</section>

<!-- Featured Projects -->
<section class="featured-section">
  <h2 class="section-title">🚀 Featured Projects</h2>
  <div class="projects-grid">
    <div class="project-card">
      <h3 class="project-title">
        <i class="fas fa-shield-alt"></i>
        CVE-2019-5736 PoC
      </h3>
      <p class="project-description">
        Exploit demonstrating container breakout via overwritten <code>runc</code> binaries. 
        A comprehensive proof-of-concept showcasing critical container security vulnerabilities.
      </p>
      <a href="https://github.com/Perimora/cve_2019-5736-PoC" target="_blank" class="project-link">
        <i class="fab fa-github"></i>
        View on GitHub
        <i class="fas fa-external-link-alt"></i>
      </a>
    </div>
    
    <div class="project-card">
      <h3 class="project-title">
        <i class="fas fa-network-wired"></i>
        IDS Lab Framework
      </h3>
      <p class="project-description">
        A modular, Docker-based lab for intrusion detection experiments using Suricata and simulated attacks. 
        Designed for reproducibility in research, teaching, and PoC scenarios.
      </p>
      <a href="https://github.com/Perimora/ids_lab" target="_blank" class="project-link">
        <i class="fab fa-github"></i>
        View on GitHub
        <i class="fas fa-external-link-alt"></i>
      </a>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="site-footer">
  <div class="footer-content">
    <p>&copy; {{ 'now' | date: "%Y" }} Christoph Huy · TU Berlin</p>
    <div class="footer-links">
      <a href="mailto:christoph.huy@campus.tu-berlin.de" title="Email">
        <i class="fas fa-envelope"></i>
      </a>
      <a href="https://github.com/Perimora" target="_blank" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
    </div>
  </div>
</footer>

