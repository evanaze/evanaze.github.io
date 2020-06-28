---
title: "Welcome"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.3" 
  overlay_image: /assets/images/unsplashed_bridge.jpg
  actions:
    - label: "<i class='fas fa-folder-open'></i> My Resume"
      url: "https://github.com/evanaze/evanaze.github.io/raw/master/assets/documents/2020_AzevedoEvan.pdf"
excerpt: "My online portfolio of work in data science and technical writing."
intro: 
  - excerpt: “'Optimism,' said Cacambo, 'What is that?' 'Alas!' replied Candide, 'It is the obstinacy of maintaining that everything is best when it is worst.'" ― Voltaire, Candide
feature_row:
  - image_path: assets/images/captcha_sample.png
    title: "Captcha Project"
    excerpt: "Building an ML model to count the number of squares in a noisy image."
    url: "https://evanaze.github.io/projects/captcha/"
    btn_label: "View"
    btn_class: "btn--primary"
  - image_path: /assets/images/spongebob.png
    title: "Sitcom NLP"
    excerpt: "Simulating dialogue of popular sitcoms."
    url: "https://evanaze.github.io/projects/sitcom-nlp/"
    btn_label: "View"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplashed_swirl.jpg
    title: "Other"
    excerpt: "Check out some of my other work in the portfolio tab"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
