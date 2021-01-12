---
title: "Dongjin's Dev-blog"
layout: splash
permalink: /

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/20201017_152953.jpg
  actions:
    - label: "Contact now <i class='fas fa-bolt'></i>"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "안녕하세요 개발자 임동진입니다."
intro: 
  - excerpt: '주로 백엔드 개발을 하며 데이터사이언스 분야에 관심이 많습니다. '
feature_row:
  - image_path: assets/images/f_1.png
    alt: "placeholder image 1"
    title: "Back-end"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/f_2.png
    alt: "placeholder image 2"
    title: "AWS/DOCKER"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/f_3.png
    title: "Data Science"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}