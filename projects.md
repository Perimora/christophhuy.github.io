---
layout: default
title: Projects
---

<section>
  <h1>🧪 Projects</h1>
  <p>Here's a showcase of my key projects in software security, container technology, and intrusion detection systems.</p>
</section>

<section class="project-item">
  <div class="project-header">
    <span class="project-icon">🛡️</span>
    <h2>CVE-2019-5736 PoC</h2>
  </div>
  
  <p>
    A comprehensive proof-of-concept exploit for <strong>CVE-2019-5736</strong>, demonstrating a critical container 
    breakout vulnerability in <code>runc</code> via overwritten symlink <code>/proc/self/exe</code>. This project 
    showcases deep understanding of container internals and security boundaries.
  </p>
  
  <div class="tech-stack">
    <span class="tech-tag">C</span>
    <span class="tech-tag">Docker</span>
    <span class="tech-tag">Shell</span>
    <span class="tech-tag">Container Security</span>
  </div>
  
  <p style="margin-top: 1rem;">
    <a href="https://github.com/Perimora/cve_2019-5736-PoC" target="_blank" class="btn">
      <i class="fab fa-github"></i>
      View on GitHub
      <i class="fas fa-external-link-alt"></i>
    </a>
  </p>
</section>

<section class="project-item">
  <div class="project-header">
    <span class="project-icon">🧠</span>
    <h2>IDS Lab Framework</h2>
  </div>
  
  <p>
    A modular, Docker-based laboratory environment designed for intrusion detection and security evaluation. 
    This framework provides a controlled, reproducible environment for testing and developing IDS solutions.
  </p>
  
  <h3>🎯 Key Features</h3>
  <ul>
    <li>Simulated network architecture with attacker, target, gateway, and monitoring nodes</li>
    <li>Suricata integration as the current IDS backend</li>
    <li>Modular design for easy extension and customization</li>
    <li>Docker-based deployment for consistent environments</li>
  </ul>
  
  <h3>🚀 Use Cases</h3>
  <ul>
    <li>Research baseline for IDS evaluation</li>
    <li>Educational environment for cybersecurity training</li>
    <li>Proof-of-concept scenarios and testing</li>
    <li>Template for building complex IDS architectures</li>
  </ul>
  
  <div class="tech-stack">
    <span class="tech-tag">Docker</span>
    <span class="tech-tag">Suricata</span>
    <span class="tech-tag">Shell</span>
    <span class="tech-tag">Network Security</span>
    <span class="tech-tag">IDS</span>
  </div>
  
  <p style="margin-top: 1rem;">
    <a href="https://github.com/Perimora/ids_lab" target="_blank" class="btn">
      <i class="fab fa-github"></i>
      View on GitHub
      <i class="fas fa-external-link-alt"></i>
    </a>
  </p>
  
  <div style="background: #f8f9fa; padding: 1rem; border-radius: 0.5rem; margin-top: 1rem; border-left: 4px solid #fbbf24;">
    <h4 style="margin-bottom: 0.5rem; color: #d97706; font-weight: 600;">🔄 Future Roadmap</h4>
    <p style="margin-bottom: 0.5rem; color: #374151; font-weight: 500; line-height: 1.5;">
      Currently supports rule-based detection. Planned enhancements include ML-based detection capabilities, 
      advanced orchestration features, and integration with modern SIEM platforms.
    </p>
    <p style="margin-bottom: 0; color: #374151; font-weight: 500; line-height: 1.5;">
      <strong>🚀 K3s Migration:</strong> Planned migration from Docker Compose to K3s (lightweight Kubernetes) 
      to enable easy on-demand scaling of the lab environment and better resource management for large-scale security testing scenarios.
    </p>
  </div>
</section>

<section class="return-home">
  <a href="/">
    <i class="fas fa-arrow-left"></i>
    Return to home
  </a>
</section>
