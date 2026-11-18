---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Data Science, University of Virginia, 2028 (expected)
* B.Sc. in Data Science, College of William & Mary, 2023
* B.Sc. in Neuroscience, College of William & Mary, 2023

Research
======
* **2024–present:** Digital Organoid: A Biologically Inspired Neural Network for Image Classification (with J. D. Van Horn), University of Virginia
* **2022:** Undergraduate Research Assistant, Mathematics, College of William & Mary (Advisor: Charles R. Johnson)
* **2021:** Undergraduate Research Assistant, Data Science, College of William & Mary (Advisor: Tyler J. Frazier)

Selected awards
======
* **2025:** The Raven Society, Elected Member
* **2025:** 1st Prize, Frontiers in Network Physiology Poster Competition, ISINP 2025
* **2024:** Best Oral Presentation, UVA Data Science Summer Research Symposium
* **2023:** Summa cum laude, College of William & Mary

Talks and posters
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
