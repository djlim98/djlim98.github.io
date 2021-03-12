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
      url: "https://github.com/djlim98/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "안녕하세요 개발자 임동진입니다."
intro: 
  - excerpt: '아래와 같은 관심사를 가지고 있습니다'
feature_row:
  - image_path: assets/images/f_1.png
    alt: "placeholder image 1"
    title: "Back-end"
    excerpt: "첫 업무로 **Node.js**로 웹서버 구현을 맡으면서 자연스럽게 백엔드에 관심을 가지게 되었습니다. **Express**를 주로 사용해보았고 최근 **Flask**와 **Django**, **Spring**으로 개인 프로젝트를 진행해보기 위해 공부하고 있습니다."
  - image_path: /assets/images/f_2.png
    alt: "placeholder image 2"
    title: "AWS/DOCKER"
    excerpt: "Cloud를 이용한 배포를 경험해보면서 aws의 장점을 많이 체감할 수 있었습니다. 그래서 aws를 최대한 활용해보려는 생각을 가지고 프로젝트를 진행하며 효율적인 IT 인프라 구조가 무엇인지 계속 고민하며 답을 찾고 있습니다."
  - image_path: /assets/images/f_3.png
    title: "Data Science"
    excerpt: "미래인테리젼스 연구실에서 학부생 인턴을 통해 특허데이터 간 유사도를 분석, kaggle 문제풀이 세미나를 하며 데이터 사이언스의 매력을 알 수 있었습니다. 자연어 분석에 특히 관심을 가지고 공부를 이어가고 있습니다. "
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