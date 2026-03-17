---
layout: page
permalink: /publications/
title: publications
description: publications by lab members
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <div class="pub-section" style="margin-bottom: 50px;">
    <h2 class="category-title">First / Corresponding Author</h2>
    <div class="pub-list">
      {% bibliography -f {{ site.scholar.bibliography }} -q @*[category=main]* %}
    </div>
  </div>

  <hr style="margin: 40px 0; border: 0; border-top: 1px solid #ddd;">

  <div class="pub-section">
    <h2 class="category-title" style="color: #666;">Co-author</h2>
    <div class="pub-list">
      {% bibliography -f {{ site.scholar.bibliography }} -q @*[category=co]* %}
    </div>
  </div>

</div>

<style>
  /* 카테고리 제목 스타일 */
  .category-title {
    font-size: 1.8rem !important;
    font-weight: 800 !important;
    margin-bottom: 25px !important;
    padding-left: 15px;
    border-left: 6px solid var(--global-theme-color);
  }
  
  /* 공저자 제목은 색상을 조금 차분하게 */
  .pub-section:last-of-type .category-title {
    border-left-color: #ccc;
  }

  /* 논문 리스트 사이 여백 */
  ol.bibliography li {
    margin-bottom: 1.5rem !important;
  }
</style>