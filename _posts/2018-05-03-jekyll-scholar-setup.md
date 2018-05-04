---
published: false
title: jekyll-scholar setup
classes: wide
categories:
  - Tools
tags:
  - ROS
  - Programming
---


md setup for book chapters and manuscripts
```liquid
## Book Chapters

{% bibliography -q @inbook %}

## Manuscripts

{% bibliography -q @phdthesis %}
```
