---
layout: archive
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ul>{% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>

# 📚 Publications

<style>
.publication-card {
    background: white;
    border-radius: 8px;
    padding: 1.5rem;
    margin: 1.5rem 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
    border-left: 4px solid #2c3e50;
}

.publication-card:hover {
    transform: translateY(-2px);
}

.badge-group {
    margin-top: 1rem;
    display: flex;
    gap: 0.8rem;
    flex-wrap: wrap;
}

.badge {
    display: inline-flex;
    align-items: center;
    padding: 0.3rem 0.8rem;
    border-radius: 20px;
    font-size: 0.9em;
    text-decoration: none;
    transition: opacity 0.3s;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

.badge:hover {
    opacity: 0.85;
}

.paper-badge { background: #00599c; color: white; }
.code-badge { background: #FF6600; color: white; }
.dataset-badge { background: #CC0000; color: white; }

.impact-factor {
    background: #27ae60;
    color: white;
    padding: 0.2rem 0.5rem;
    border-radius: 3px;
    font-size: 0.8em;
    margin-left: 0.5rem;
    vertical-align: middle;
}

.code_repo {
    background:rgb(22, 24, 165);
    color: white;
    padding: 0.2rem 0.5rem;
    border-radius: 3px;
    font-size: 0.8em;
    margin-left: 0.5rem;
    vertical-align: middle;
}

.dataset {
    background:rgb(174, 39, 93);
    color: white;
    padding: 0.2rem 0.5rem;
    border-radius: 3px;
    font-size: 0.8em;
    margin-left: 0.5rem;
    vertical-align: middle;
}

@media (max-width: 768px) {
    .publication-card {
        padding: 1rem;
        margin: 1rem 0;
    }
    
    .badge {
        font-size: 0.85em;
    }
}
</style>

---

## 🏆 Selected Publications

<div class="publication-card">

<strong>Mou Lei</strong>, Zhao Yitian, Chen Li, et al. <strong>CS-Net: Channel and spatial attention network for curvilinear structure segmentation</strong>  
<i>Medical Image Computing and Computer Assisted Intervention (MICCAI) 2019</i> <br />
<span class="impact-factor" hrf="https://link.springer.com/chapter/10.1007/978-3-030-32239-7_80">Paper</span> <span class="code_repo">Code</span> <span class="dataset">Dataset</span>

<div class="badge-group">
[![](https://img.shields.io/badge/📄_Paper-00599C?style=flat)](https://link.springer.com/chapter/10.1007/978-3-030-32239-7_80){: .badge .paper-badge}
[![](https://img.shields.io/badge/💻_Code-FF6600?style=flat)](https://github.com/iMED-Lab/CS-Net){: .badge .code-badge}
</div>
</div>

<div class="publication-card">

**Mou Lei**, Zhao Yitian, Fu Huazhu, et al. **CS$^2$-Net: Deep learning segmentation of curvilinear structures in medical imaging**  
*Medical Image Analysis 2021*  
<span class="impact-factor">IF: 10.9</span>

<div class="badge-group">
[![](https://img.shields.io/badge/📄_Paper-00599C)](https://www.sciencedirect.com/science/article/abs/pii/S1361841520302383){: .badge .paper-badge}
[![](https://img.shields.io/badge/💻_Code-FF6600)](https://github.com/iMED-Lab/CS-Net){: .badge .code-badge}
[![](https://img.shields.io/badge/📦_Dataset-CORN--1500-red)](https://zenodo.org/records/12776091){: .badge .dataset-badge}
</div>
</div>

<!-- 其他精选文献保持相同结构 -->

---

## 📑 All Publications

<div class="publication-card">

1. **Mou Lei**, et al. CS-Net: Channel and spatial attention network...  
   *MICCAI 2019*  
   <div class="badge-group">
   [Paper](https://link.springer.com/chapter/10.1007/978-3-030-32239-7_80){: .badge .paper-badge}
   [Code](https://github.com/iMED-Lab/CS-Net){: .badge .code-badge}
   </div>
</div>

<div class="publication-card">

2. **Mou Lei**, et al. CS2-Net: Deep learning segmentation...  
   *MedIA 2021*  
   <div class="badge-group">
   [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1361841520302383){: .badge .paper-badge}
   [Dataset](https://zenodo.org/records/12776091){: .badge .dataset-badge}
   </div>
</div>

<!-- 其他文献保持相同结构 -->

