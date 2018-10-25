---
title: Posts
layout: splash
permalink: /post-types/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/cle.jpg
  actions:
    - label: #"Download"
      url: #"https://github.com/mmistakes/minimal-mistakes/"
  caption: #"Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Posts sorted by category."
feature_row_l1:
- image_path: /images/code.jpg
  alt: "placeholder image 2"
  title: "Computer Science"
  excerpt: 'Posts about computer science.'
  url: /comp-sci/
  btn_label: "View"
  btn_class: "btn--primary"
feature_row_r1:
- image_path: /images/books.jpg
  alt: "placeholder image 2"
  title: "Creative"
  excerpt: 'Artwork and different pieces of writing.'
  url: /creative/
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

{% include feature_row id="feature_row_l1" type="left" %}

{% include feature_row id="feature_row_r1" type="right" %}
