---
layout: default
title: Yakir Hadad — Portfolio
---

# Yakir Hadad

**CV/DL Researcher.** I build production-grade computer vision systems (detection, tracking, stereo, multi‑view) and research cross‑spectral registration.  
**Stack:** Python • PyTorch • C++ • Lightning • MLflow • Docker • Multi‑GPU • Realtime.

**Links:** [GitHub](https://github.com/yakirEng) · [LinkedIn](https://www.linkedin.com/in/yakir-hadad/) · <a href="mailto:yakirhadad18@gmail.com">yakirhadad18@gmail.com</a>

## Featured Projects

{% for p in site.data.projects %}
### <a href="{{ p.url }}" target="_blank" rel="noopener">{{ p.title }}</a>
{{ p.description }}

**Tags:** {% for t in p.tags %}`{{ t }}` {% endfor %}

---
{% endfor %}

## About
- M.Sc. research @ Tel Aviv University — first‑author CVPR submission (cross‑spectral registration, Transformer‑based & physics‑informed models).
- Ex‑IAF R&D Lead — deployed multi‑sensor anti‑drone system in live ops, F1 = 0.97.
- Stereo/multi‑view geometry, calibration, depth & 3D perception; end‑to‑end from research to production.
