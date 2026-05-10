---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Nuclear Technology and Applications**
  University of Chinese Academy of Sciences / Institute of Modern Physics, CAS
  Beijing / Lanzhou, China | *2019 – 2024*
  Thesis: *Research on electron beam irradiation technology based on microtron accelerator and development of dose calculation algorithm*
  Supervisor: Prof. Youwu Su
  Funded by: CAS-TWAS President's Fellowship Programme

* **M.Sc. in Nuclear Physics**
  Samarkand State University, Samarkand, Uzbekistan | *2017 – 2019*

* **B.Sc. in Physics**
  Samarkand State University, Samarkand, Uzbekistan | *2012 – 2016*

---

## Work Experience

* **Associate Professor** — Samarkand State University
  *Sep 2025 – Present* | Samarkand, Uzbekistan
  - Deliver undergraduate lectures in Interaction of Particles and Radiation with Matter, Fundamentals of Atomic and Nuclear Physics, and Dosimetry
  - Conduct independent research on environmental radioactivity, radionuclide migration, and pollution assessment
  - Contribute to IAEA-based projects and the MIT-Samarkand (MISTI) international collaboration

* **Senior Researcher** — Samarkand State University
  *2024 – 2025* | Samarkand, Uzbekistan
  - Led research on environmental radioactivity including radionuclide spectrometry and elemental composition analysis via neutron activation
  - Collaborated on IAEA-funded and MISTI international projects; presented findings at international conferences
  - Applied activation analysis for nuclear reaction studies and archaeometallurgical investigations

* **Doctoral Researcher** — Institute of Modern Physics, Chinese Academy of Sciences
  *2019 – 2024* | Lanzhou, China
  - Developed analytical dose calculation model for solid-state sample irradiation using microtron-type electron beam accelerator
  - Performed Monte Carlo simulations (FLUKA) for radiation shielding design and induced radioactivity analysis at HIAF and proton therapy facilities
  - Conducted measurements and calculations of leakage neutron spectra from U-238 and Pb targets
  - Co-developed radiation safety assessments for heavy-ion and proton therapy treatment rooms

* **Junior Researcher** — Samarkand State University
  *2021 – 2023* | Samarkand, Uzbekistan
  - Investigated environmental radioactivity through gamma spectrometry and neutron activation analysis
  - Assessed radiological risks in soil and groundwater near former underground nuclear explosion sites
  - Co-authored published studies on natural radionuclide profiles, radon hazards, and heavy metal contamination

---

## Technical Skills

**Simulation & Modeling:** FLUKA Monte Carlo code
**Experimental Techniques:** Gamma spectrometry (HPGe, NaI(Tl)), neutron activation analysis, electron beam irradiation, radiation dosimetry
**Software & Programming:** OriginLab, Python, Wolfram Mathematica, MS Office Suite

---

## Languages

| Language | Level |
|----------|-------|
| Uzbek | Native |
| Tajik | Fluent |
| Russian | Fluent |
| English | Fluent |
| Chinese | Basic |

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Teaching

{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
