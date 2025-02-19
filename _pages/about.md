---
permalink: /
title: "Homepage of Lei Mou"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
:root {
    --gradient-start: #FF00D4;
    --gradient-end: #00FFEE;
    --accent-color: #2A7FFF;
}

/* 增强导航栏设计 */
.gradient-nav {
    padding: 1.0rem 0;
    position: sticky;
    top: 0;
    z-index: 50;
}

.gradient-nav a {
    font-family: 'Inter', system-ui, sans-serif;
    font-weight: 600;
    font-size: 0.8rem;
    text-decoration: none;
    background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    padding: 0.5rem 0.5rem;
    border-radius: 5px;
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.gradient-nav a:hover {
    transform: translateY(-2px);
    background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
    color: white !important;
    box-shadow: 0 4px 12px rgba(0,103,255,0.15);
}

/* 内容容器优化 */
.container {
    max-width: 880px;
    margin: 0 auto;
    padding: 1rem 1rem;
}


/* 传记段落优化 */
.bio {
    line-height: 1.6;
    padding: 1.2rem;
    border-radius:8px;
    border: 1px solid rgba(0,103,255,0.1);
}

/* 新闻时间线设计 */
.news-item {
    position: relative;
    padding: 0 0 1.0rem 2.0rem;
    border-left: 2px solid rgba(127, 127, 127, 0.1);
    margin-left: 1.0rem;
}

.news-item::before {
    content: "📌";
    position: absolute;
    left: -0.8rem;
    padding: 0px;
}

.news-date {
    color: #666;
    font-size: 0.95rem;
    margin-bottom: 0.2rem;
}

</style>

<div class="gradient-nav" align="left">
    <a>Medical Imaging</a>
    <a>Segmentation</a>
    <a>Diagnosis</a>
    <a>AI in Healthcare</a>
</div>

<div class="container">

<h2>Biography</h2>

<p class="bio">
Dr. Lei Mou received his B.Sc. degree in Information Security from Wuhan University of Science and Technology in 2017, followed by an M.Sc. degree in Software Engineering from the same institution in 2020. He completed his Ph.D. in Mechanical Manufacturing and Automation at the University of Chinese Academy of Sciences in 2024 under the supervision of Prof. <a href="https://ytianzhao.github.io/" style="color: var(--accent-color); text-decoration: underline;">Yitian Zhao</a>. His research interests focus on intelligent medical imaging analysis and the innovative application of artificial intelligence in healthcare. His work primarily encompasses multimodal data analysis and the development of intelligent algorithms based on fundus imaging. By integrating deep learning techniques with radiomics approaches, he aims to identify early biomarkers of cardiovascular and cerebrovascular diseases and to develop clinically applicable disease risk prediction models and computer-aided diagnostic systems.
</p>

# About Me

<div style="background: #f3f9ff; padding: 1.5rem; border-radius: 5px; margin: 1.5rem 0;">
🖋️ <strong>Associate Editor</strong> - IEEE Transactions on Medical Imaging (2024-Present)
</div>

# News

<div class="news-item">
    <div class="news-date">2025/02/15</div>
    One paper has been accepted by <strong>Journal of Biomedical and Health Informatics (JHBI)</strong> <span style="color: #2A7FFF;">[OCT/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/02/08</div>
    One paper has beed accepted by <strong>IEEE Transactions on Medical Imaging (TMI) <span style="color: #2A7FFF;">[DSA/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/02/08</div>
    One paper has beed accepted by <strong>IEEE Transactions on Signal and Information Processing over Networks (TSIPN) <span style="color: #00C853;">[MRI/Diagnosis]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/01/28</div>
    One paper has beed accepted by <strong>Frontiers in Cell and Developmental Biology <span style="color: #2A7FFF;">[OCT/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/01/16</div>
    One paper has beed accepted by <strong>IEEE Transactions on Medical Imaging (TMI) <span style="color: #2A7FFF;">[OCT/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/01/03</div>
    One paper has beed accepted by <strong>IEEE International Symposium on Biomedical Imaging (ISBI2025) <span style="color: #2A7FFF;">[IVCM/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2024/12/04</div>
    One paper has beed accepted by <strong>IEEE Transactions on Medical Imaging (TMI) <span style="color: #2A7FFF;">[TOF-MRA/Segmentation]</span>
</div>

<!-- 其他新闻条目保持相同结构 -->

</div>

