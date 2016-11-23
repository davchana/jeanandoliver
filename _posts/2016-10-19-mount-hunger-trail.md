---
layout: post
title: 'Mount Hunger Trail'
updated: 2016-11-23 14:46
image:
  - src: /images/image-1024x683.png
    alt: test image
  - src: /images/image-1024x1536.png
    alt: vertical test image
  - src: /images/image-1024x1024.png
    alt: square test image
---

<div class="grid">

{% assign image = page.image[0] %}
{% include block/image.html class="grid-image" %}

{% assign image = page.image[0] %}
{% include block/image.html class="grid-image" %}

{% assign image = page.image[2] %}
{% include block/image.html class="grid-image--aspect1x1" %}

</div>

<div class="grid">

{% assign image = page.image[0] %}
{% include block/image.html class="grid-image" %}

{% assign image = page.image[1] %}
{% include block/image.html class="grid-image--aspect2x3" %}

</div>
