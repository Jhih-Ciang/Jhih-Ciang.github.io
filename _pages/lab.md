---
layout: archive
permalink: /lab/
author_profile: true
---

<style>
/* 實驗室成員網格佈局樣式 */
.lab-grid {
  display: grid;
  gap: 30px; /* 卡片之間的間距 */
  margin-bottom: 40px;
}

/* 成員卡片樣式 */
.lab-member {
  background: #fff;
  /* border: 1px solid #e0e0e0; 若不想要邊框可以註解掉 */
  border-radius: 8px;
  padding: 10px;
  text-align: center;
  /* box-shadow: 0 2px 5px rgba(0,0,0,0.05); 若想要平面一點可以註解掉陰影 */
  transition: transform 0.2s;
}

.lab-member:hover {
  transform: translateY(-5px); /* 滑鼠移過去會浮起來 */
}

/* 成員名字樣式 */
.lab-member h3 {
  margin: 10px 0 0 0;
  font-size: 1rem;
  font-weight: 600;
}

/* 圖片樣式 */
.lab-member img {
  width: 150px;       /* 設定圖片寬度 */
  height: 150px;      /* 設定圖片高度，保持正方形 */
  object-fit: cover;  /* 確保圖片填滿且不變形 */
  border-radius: 50%; /* 圓形頭像 */
  border: 3px solid #f0f0f0;
  display: block;
  margin: 0 auto;     /* 圖片置中 */
}

/* 響應式設計 (RWD) */
/* 電腦版: 4欄 */
@media (min-width: 1024px) {
  .lab-grid { grid-template-columns: repeat(4, 1fr); }
}
/* 平板: 2欄 */
@media (max-width: 1023px) and (min-width: 600px) {
  .lab-grid { grid-template-columns: repeat(2, 1fr); }
}
/* 手機: 1欄 */
@media (max-width: 599px) {
  .lab-grid { grid-template-columns: 1fr; }
}
</style>

Welcome to the Computer Vision and Intelligence lab! Here are the amazing individuals who make up our team:

## Principal Investigator

**Jhih-Ciang Wu**

---

## MS Students

<div class="lab-grid">
  <div class="lab-member">
    <img src="/images/lab/005.jpg" alt="Yo-Chen Lin">
    <h3>Yo-Chen Lin</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/006.jpg" alt="Devansh Saxena">
    <h3>Devansh Saxena</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/007.jpg" alt="Ting-Wei Lai">
    <h3>Ting-Wei Lai</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/008.jpg" alt="Shih-Yao Su">
    <h3>Shih-Yao Su</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/004.jpg" alt="Ting-Kai Chou">
    <h3>Ting-Kai Chou</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/017.jpg" alt="Kristy Lan">
    <h3>Kristy Lan</h3>
  </div>
</div>

---

## BS Students

<div class="lab-grid">
  <div class="lab-member">
    <img src="/images/lab/001.jpg" alt="I-Han Cho">
    <h3>I-Han Cho</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/003.jpg" alt="Yu-Chiao Cheng">
    <h3>Yu-Chiao Cheng</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/009.jpg" alt="Jun-Ting Wu">
    <h3>Jun-Ting Wu</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/010.jpg" alt="Tzu-Chien Huang">
    <h3>Tzu-Chien Huang</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/011.jpg" alt="Kuan-Hung Chen">
    <h3>Kuan-Hung Chen</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/012.jpg" alt="Chia-Hsin Chang">
    <h3>Chia-Hsin Chang</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/013.jpg" alt="Jethro Lo">
    <h3>Jethro Lo</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/014.jpg" alt="Chao-Yu Chen">
    <h3>Chao-Yu Chen</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/015.jpg" alt="Chao-Hung Cheng">
    <h3>Chao-Hung Cheng</h3>
  </div>
  <div class="lab-member">
    <img src="/images/lab/016.jpg" alt="Yueh-Hsi Chung">
    <h3>Yueh-Hsi Chung</h3>
  </div>
</div>

---
