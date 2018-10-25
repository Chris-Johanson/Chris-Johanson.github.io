---
title: "Showcase"
layout: splash
permalink: /showcase/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/library.jpg
  actions:
    - label: #"Download"
      url: #"https://github.com/mmistakes/minimal-mistakes/"
  caption: #"Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Always improving."
intro:
  - excerpt: 'A selection of works that I believe showcase my abilities and interests.'
feature_row_l1:
- image_path: /images/desk2.jpg
  alt: "placeholder image 2"
  title: "Computer Science"
  excerpt: 'A collection of projects and studies in computer science.'
  url: /comp-sci-portfolio/
  btn_label: "View"
  btn_class: "btn--primary"
feature_row_r1:
- image_path: /images/blank.jpg
  alt: "placeholder image 2"
  title: "Writing"
  excerpt: 'Prose and poetry written by me.'
  url: /creative-portfolio/
  btn_label: "View"
  btn_class: "btn--primary"
feature_row_l2:
- image_path: /images/canvas.jpg
  alt: "placeholder image 2"
  title: "Artwork"
  excerpt: 'A collection of drawing and other artwork created by me.'
  url: /artwork-portfolio/
  btn_label: "View"
  btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_l1" type="left" %}

{% include feature_row id="feature_row_r1" type="right" %}

{% include feature_row id="feature_row_l2" type="left" %}
