---
layout: default
title: Yakir Hadad — Portfolio
---

<div class="hero">
  <h1>Yakir Hadad</h1>
  <p class="subtitle">CV/DL Researcher — production-grade vision systems (detection, tracking, stereo & multi‑view) and cross‑spectral registration.</p>
  <div class="btns">
    <a class="btn primary" href="https://github.com/yakirEng" target="_blank" rel="noopener">GitHub</a>
    <a class="btn" href="https://www.linkedin.com/in/yakir-hadad/" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn ghost" href="mailto:yakirhadad18@gmail.com">Email</a>
    <a class="btn" href="/assets/Yakir_Hadad_CV.pdf">CV (PDF)</a>
  </div>
</div>

## Featured Projects

<div class="grid">
{% for p in site.data.projects %}
  <a class="card" href="{{ p.url }}" target="_blank" rel="noopener">
    <h3>{{ p.title }}</h3>
    <p>{{ p.description }}</p>
    <div class="meta">
      {% if p.repo %}
      <img alt="stars" src="https://img.shields.io/github/stars/{{ p.repo }}?style=social" />
      <img alt="forks" src="https://img.shields.io/github/forks/{{ p.repo }}?style=social" />
      {% endif %}
    </div>
    <div class="tags">
      {% for t in p.tags %}<span class="tag">{{ t }}</span>{% endfor %}
    </div>
  </a>
{% endfor %}
</div>

## About
- M.Sc. research @ Tel Aviv University — first‑author CVPR submission (cross‑spectral registration, Transformer‑based & physics‑informed models).
- Ex‑IAF R&D Lead — deployed multi‑sensor anti‑drone system in live ops, F1 = 0.97.
- Stereo/multi‑view geometry, calibration, depth & 3D perception; end‑to‑end from research to production.

<p class="footer-note">© {{ site.time | date: "%Y" }} Yakir Hadad. Built with Jekyll.</p>
