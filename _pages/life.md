---
layout: archive
permalink: /life/
author_profile: true
---

<style>
/* Life page grid layout */
.life-grid {
  display: grid;
  gap: 40px; /* 間距設定 */
  margin-bottom: 40px;
}

/* Card style */
.life-card {
  background: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  transition: transform 0.2s, box-shadow 0.2s;
}

.life-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

/* Image style */
.life-card img {
  width: 100%;
  height: 300px; /* 配合 2 欄設計，讓圖片高一點比較好看 */
  object-fit: cover;
  display: block;
  border-bottom: 1px solid #f0f0f0;
}

/* Content text style */
.life-content {
  padding: 20px;
}

.life-date {
  display: block;
  color: #888;
  font-size: 0.9rem;
  margin-bottom: 8px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.life-desc {
  margin: 0;
  font-size: 1.1rem;
  color: #333;
  line-height: 1.5;
}

/* Responsive Design */
/* Desktop: 2 columns (你指定的 2 欄設計) */
@media (min-width: 1024px) {
  .life-grid { grid-template-columns: repeat(2, 1fr); }
}
/* Tablet: 2 columns */
@media (max-width: 1023px) and (min-width: 600px) {
  .life-grid { grid-template-columns: repeat(2, 1fr); }
}
/* Mobile: 1 column */
@media (max-width: 599px) {
  .life-grid { grid-template-columns: 1fr; }
}
</style>

Here are some memorable moments from our lab and academic life:

<div class="life-grid">

  <!-- Item 13 -->
  <div class="life-card">
    <img src="/images/life/20251222.jpg" alt="Year-end party">
    <div class="life-content">
      <span class="life-date">2025-12-22</span>
      <p class="life-desc">CVI Lab year-end party.</p>
    </div>
  </div>

  <!-- Item 12 -->
  <div class="life-card">
    <img src="/images/life/20251126.jpg" alt="Prof. Shuai talk">
    <div class="life-content">
      <span class="life-date">2025-11-26</span>
      <p class="life-desc">Prof. Hong-Han Shuai's talk at NTNU.</p>
    </div>
  </div>

  <!-- Item 11 -->
  <div class="life-card">
    <img src="/images/life/20250915.jpg" alt="Group meeting">
    <div class="life-content">
      <span class="life-date">2025-09-15</span>
      <p class="life-desc">Group meeting and prank to Jun-Ting.</p>
    </div>
  </div>

  <!-- Item 10 -->
  <div class="life-card">
    <img src="/images/life/20250507.jpg" alt="Prof. Cheng talk">
    <div class="life-content">
      <span class="life-date">2025-05-07</span>
      <p class="life-desc">Prof. Wen-Huang Cheng's talk at NTNU.</p>
    </div>
  </div>

  <!-- Item 9 -->
  <div class="life-card">
    <img src="/images/life/20250430.jpg" alt="Gathering">
    <div class="life-content">
      <span class="life-date">2025-04-30</span>
      <p class="life-desc">The gathering after Ling Lo's talk at NTNU.</p>
    </div>
  </div>

  <!-- Item 8 -->
  <div class="life-card">
    <img src="/images/life/20250423.jpg" alt="Fred talk">
    <div class="life-content">
      <span class="life-date">2025-04-23</span>
      <p class="life-desc">Fred's talk @NTNU</p>
    </div>
  </div>

  <!-- Item 7 -->
  <div class="life-card">
    <img src="/images/life/20250416.jpg" alt="Prof. Peng talk">
    <div class="life-content">
      <span class="life-date">2025-04-16</span>
      <p class="life-desc">Prof. Yan-Tsung Peng's talk @NTNU</p>
    </div>
  </div>

  <!-- Item 6 -->
  <div class="life-card">
    <img src="/images/life/20250116.jpg" alt="Birthday">
    <div class="life-content">
      <span class="life-date">2025-01-16</span>
      <p class="life-desc">Prof. Wen-Huang Cheng's birthday @NTU</p>
    </div>
  </div>

  <!-- Item 5 -->
  <div class="life-card">
    <img src="/images/life/20250105.jpg" alt="AIMMers gathering">
    <div class="life-content">
      <span class="life-date">2025-01-05</span>
      <p class="life-desc">AIMMers gathering @Gongguan Secondfloor Cafe</p>
    </div>
  </div>

  <!-- Item 4 -->
  <div class="life-card">
    <img src="/images/life/20241012.jpg" alt="Tencent Lab">
    <div class="life-content">
      <span class="life-date">2024-10-12</span>
      <p class="life-desc">Visit Chengjie and Jiangning @Tencent Youtu Lab, Shanghai, China</p>
    </div>
  </div>

  <!-- Item 3 -->
  <div class="life-card">
    <img src="/images/life/20241003.jpg" alt="ECCV 24">
    <div class="life-content">
      <span class="life-date">2024-10-03</span>
      <p class="life-desc">ECCV'24 @Milan, Italy</p>
    </div>
  </div>

  <!-- Item 2 -->
  <div class="life-card">
    <img src="/images/life/20231010.jpg" alt="MICCAI 23">
    <div class="life-content">
      <span class="life-date">2023-10-10</span>
      <p class="life-desc">MICCAI'23 @Vancouver, Canada</p>
    </div>
  </div>

  <!-- Item 1 -->
  <div class="life-card">
    <img src="/images/life/20221025.jpg" alt="ECCV 22">
    <div class="life-content">
      <span class="life-date">2022-10-25</span>
      <p class="life-desc">ECCV'22 @Tel Aviv, Israel</p>
    </div>
  </div>

</div>
