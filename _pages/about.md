---
layout: about
title: about
permalink: /
subtitle: <strong><a href='#'>Principal Investigator:</a></strong> <strong>Soon Sang Park, MD., PhD.</strong>

profile:
  align: right
  image: PI.png
  image_circular: false 
  more_info: >
    <div style="text-align: left; font-size: 0.85rem; line-height: 1.5; margin-top: 10px;">
      <p style="margin-bottom: 5px;"><strong>Songjae Building, Room 309</strong><br>Ajou University School of Medicine</p>
      <p style="margin-bottom: 5px;"><i class="fas fa-envelope"></i> sspark9395@ajou.ac.kr</p>
      <p><i class="fas fa-phone"></i> +82-31-219-5057</p>
    </div>
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<div style="text-align: justify;">
  <p style="margin-bottom: 1em;">Welcome to the website of the Ajou Translational Medicine (ATM) Lab.</p>

  <p style="margin-bottom: 1em;">Our laboratory conducts translational research centered on aging, cellular senescence, and skin diseases. We study patient phenotypes, including real-world symptoms and clinical manifestations, and investigate the underlying molecular mechanisms.</p>

  <p style="margin-bottom: 1em;">We pursue integrated research across multiple modalities, including cell-based experiments, animal studies, human-derived sample research, bioinformatics, and deep learning. We aim to build a multidisciplinary research environment and welcome researchers from diverse backgrounds as long as they bring strong expertise in their field.</p>

  <p>We always welcome students and researchers who are interested in our lab. Please feel free to contact us via the email address on the right. We also welcome collaborations with principal investigators and researchers from a wide range of disciplines, so please do not hesitate to reach out.</p>
</div>

<style>
  /* 1. 프로필 영역(사진 + 연락처) 전체를 위로 끌어올림 */
  .profile {
    /* ★ 핵심: 음수 마진을 주어 위로 올립니다. 제목 높이에 딱 맞게 조정했습니다 ★ */
    margin-top: -3.0rem !important; 
    margin-left: 40px !important; /* 이전의 간격 유지 */
    width: 32% !important; /* 사진 컬럼 비율 */
    min-width: 250px !important; /* 최소 너비 제한 */
    margin-bottom: 20px !important; /* 아래쪽 여백 */
    float: right; /* 우측 정렬 유지 */
  }

  /* 2. 사진 크기 및 스타일 (깔끔하게 유지) */
  .profile img {
    width: 100% !important;
    max-width: 280px !important; /* 사진 자체의 최대 너비 */
    border-radius: 10px; /* 좀 더 부드러운 라운드 */
    border: 1px solid rgba(0,0,0,0.05);
    box-shadow: 0 4px 15px rgba(0,0,0,0.03); /* 은은한 그림자 */
  }

  /* 3. 사진 아래 연락처(more_info) 정렬 */
  .profile .more-info {
    margin-top: 15px !important;
    font-size: 0.85rem !important;
    line-height: 1.6 !important;
    color: #444 !important;
    text-align: left !important; /* 연락처는 왼쪽 정렬 */
  }

  /* 4. [보완] 본문 첫 문장의 위쪽 여백을 없애서 사진과 높이를 맞춥니다 */
  .post-content > p:first-of-type {
    margin-top: 0 !important;
    padding-top: 0 !important;
    margin-bottom: 1.5rem !important; /* 첫 문장과 아래 문장 사이 간격 */
    text-align: justify;
    line-height: 1.8 !important;
  }

  /* 5. [보완] 모바일 환경 대응 - 반드시 필요 (위로 올린 사진을 다시 제자리로) */
  @media (max-width: 576px) {
    .profile {
      margin-top: 0 !important; /* 모바일에서는 위로 올리지 않음 */
      margin-left: 0 !important;
      width: 80% !important;
      float: none !important;
      margin: 0 auto 2rem auto !important;
      text-align: center !important;
    }
  }
</style>
