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
    background: rgba(255,255,255,0);
    box-shadow: 0 4px 20px rgba(0,103,255,0.08);
    position: sticky;
    top: 0;
    z-index: 100;
}

.gradient-nav a {
    font-family: 'Inter', system-ui, sans-serif;
    font-weight: 600;
    text-decoration: none;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    border-radius: 8px;
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.gradient-nav a:hover {
    transform: translateY(-2px);
    background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
    color: white !important;
    box-shadow: 0 4px 12px rgba(0,103,255,0.15);
}

.gradient-nav a:not(:last-child)::after {
    content: "|";
    color: rgba(0,103,255,0.2);
    transform: scale(1.2);
}

/* 内容容器优化 */
.container {
    max-width: 880px;
    margin: 0 auto;
    padding: 1rem 1rem;
}

/* 标题样式增强 */
h1, h2 {
    font-family: 'Inter', system-ui, sans-serif;
    margin: 2rem 0 1.5rem;
}

/* 传记段落优化 */
.bio {
    line-height: 1.6;
    font-size: 1.05rem;
    padding: 1.5rem;
    border-radius: 5px;
    border: 1px solid rgba(0,103,255,0.1);
}

/* 新闻时间线设计 */
.news-item {
    position: relative;
    padding: 1.1rem 0 1.1rem 2rem;
    border-left: 2px solid rgba(0, 8, 247, 0.25);
    margin-left: 1rem;
}

.news-item::before {
    content: "📌";
    position: absolute;
    left: -1.1rem;
    top: 1.4rem;
    padding: 2px;
}

.news-date {
    color: #666;
    font-size: 0.95rem;
    margin-bottom: 0.5rem;
}

</style>

<div class="gradient-nav" align="center">
    <a>Medical Imaging</a>
    <a>Segmentation</a>
    <a>Diagnosis</a>
    <a>AI in Healthcare</a>
    <a>Multi-modal</a>
</div>

<div class="container">

# Biography

<p class="bio">
Dr. Lei Mou received his B.Sc. degree in Information Security from Wuhan University of Science and Technology in 2017, followed by an M.Sc. degree in Software Engineering from the same institution in 2020. He completed his Ph.D. in Mechanical Manufacturing and Automation at the University of Chinese Academy of Sciences in 2024 under the supervision of Prof. <a href="https://ytianzhao.github.io/" style="color: var(--accent-color); text-decoration: underline;">Yitian Zhao</a>. His research interests focus on intelligent medical imaging analysis and the innovative application of artificial intelligence in healthcare. His work primarily encompasses multimodal data analysis and the development of intelligent algorithms based on fundus imaging. By integrating deep learning techniques with radiomics approaches, he aims to identify early biomarkers of cardiovascular and cerebrovascular diseases and to develop clinically applicable disease risk prediction models and computer-aided diagnostic systems.
</p>

# About me

<div style="background: #f3f9ff; padding: 1.5rem; border-radius: 8px; margin: 1.5rem 0;">
- 🖋️ **Associate Editor** - *IEEE Transactions on Medical Imaging* (2024-Present)
</div>

# News

<div class="news-item">
    <div class="news-date">2025/02/15</div>
    One paper has been accepted by <strong>Journal of Biomedical and Health Informatics (JHBI)</strong> <span style="color: #2A7FFF;">[OCT/Segmentation]</span>
</div>

<div class="news-item">
    <div class="news-date">2025/02/08</div>
    Two papers accepted by <strong>IEEE TMI 2025</strong> and <strong>TSIPN 2025</strong> <span style="color: #2A7FFF;">[DSA/Segmentation]</span> <span style="color: #00C853;">[MRI/Diagnosis]</span>
</div>

<!-- 其他新闻条目保持相同结构 -->

</div>

---

# News

- 2025/02/15: One paper has been accepted by **Journal of Biomedical and Health Informatics** (**JHBI**) [<font color=blue>OCT / Segmenation</font>]
- 2025/02/08: One paper has been accepted by **IEEE Transactions on Medical Imaging** (**TMI 2025**) <font color=blue>[DSA / Segmentation]</font>
- 2025/02/08: One paper has been accepted by **IEEE Transactions on Signal and Information Processing over Networks** (**TSIPN 2025**) <font color=green>[MRI / Diagnosis]</font>
- 2025/01/28: One paper has been accepted by **Frontiers in Cell and Developmental Biology** <font color=blue>[OCT / Segmentation]</font>
- 2025/01/16: One paper has been accepted by **IEEE Transactions on Medical Imaging** (**TMI 2025**) <font color=blue>[OCT / Segmentation]</font>
- 2025/01/03: One paper has been accepted by **IEEE International Symposium on Biomedical Imaging** (**ISBI 2025**) <font color=blue>[IVCM / Segmentation]</font>
- 2024/12/04: One paper has been accepted by **IEEE Transactions on Medical Imaging** (**TMI 2024**) <font color=blue>[TOF-MRA / Segmentation]</font>
