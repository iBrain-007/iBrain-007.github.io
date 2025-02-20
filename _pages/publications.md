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
    border-radius: 10px;
    padding: 0.8rem;
    margin: 0.5rem 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
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
    padding: 0.2rem 0.8rem;
    border-radius: 20px;
    font-size: 0.8em;
    text-decoration: none;
    transition: opacity 0.3s;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

.badge:hover {
    opacity: 0.95;
}

.paper-badge { background: #00599c; color: white; }
.code-badge { background: #FF7F00; color: white; }
.dataset-badge { background: #CC0000; color: white; }

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
<strong>Mou Lei</strong>, Zhao Yitian, Chen Li, et al. <strong>CS-Net: Channel and spatial attention network for curvilinear structure segmentation.</strong> <i>Medical Image Computing and Computer Assisted Intervention (MICCAI) 2019</i>

<div class="badge-group">
    <a href="https://link.springer.com/chapter/10.1007/978-3-030-32239-7_80" style="text-decoration: none;" class="badge paper-badge">
      Paper
    </a>
    <a href="https://github.com/iMED-Lab/CS-Net" style="text-decoration: none;" class="badge code-badge">
      Code
    </a>
    <a href="https://zenodo.org/records/12776091" style="text-decoration: none;" class="badge dataset-badge">
      Dataset
    </a>
</div>
</div>



<div class="publication-card">
<strong>Mou Lei</strong>, Zhao Yitian, Fu Huazhu, et al. <strong>CS2-Net: Deep learning segmentation of curvilinear structures in medical imaging.</strong> <i>Medical Image Analysis</i>

<div class="badge-group">
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S1361841520302383" style="text-decoration: none;" class="badge paper-badge">
      Paper
    </a>
    <a href="https://github.com/iMED-Lab/CS-Net" style="text-decoration: none;" class="badge code-badge">
      Code
    </a>
    <a href="https://zenodo.org/records/12776091" style="text-decoration: none;" class="badge dataset-badge">
      Dataset
    </a>
</div>
</div>


<div class="publication-card">
<strong>Mou Lei</strong>, Qi Hong, Liu Yonghuai, et al. <strong>DeepGrading: deep learning grading of corneal nerve tortuosity.</strong> <i>IEEE Transactions on Medical Imaging</i>

<div class="badge-group">
    <a href="https://ieeexplore.ieee.org/document/9729201" style="text-decoration: none;" class="badge paper-badge">
      Paper
    </a>
    <a href="https://github.com/iMED-Lab/TortuosityGrading" style="text-decoration: none;" class="badge code-badge">
      Code
    </a>
    <a href="https://zenodo.org/records/12776091" style="text-decoration: none;" class="badge dataset-badge">
      Dataset
    </a>
</div>
</div>


<div class="publication-card">
<strong>Mou Lei</strong>, Lin Jinghui, Zhao Yifan, et al. <strong>COSTA: A Multi-center TOF-MRA Dataset and A Style Self-Consistency Network for Cerebrovascular Segmentation.</strong> <i>IEEE Transactions on Medical Imaging</i>

<div class="badge-group">
    <a href="https://ieeexplore.ieee.org/document/10599360" style="text-decoration: none;" class="badge paper-badge">
      Paper
    </a>
    <a href="https://github.com/iMED-Lab/COSTA" style="text-decoration: none;" class="badge code-badge">
      Code
    </a>
    <a href="https://zenodo.org/records/11025761" style="text-decoration: none;" class="badge dataset-badge">
      Dataset
    </a>
</div>
</div>

---

# 📑 Full Publication List

1. **Mou Lei**, Zhao Yitian, Chen Li, Cheng Jun, Gu Zaiwang, Hao Huaying, Qi Hong, Zheng Yalin, Frangi Alejandro, Liu Jiang. CS-Net: Channel and spatial attention network for curvilinear structure segmentation; proceedings of the Medical Image Computing and Computer Assisted Intervention–MICCAI, 2019 [C]. Springer.
2. **Mou Lei**, Zhao Yitian, Fu Huazhu, Liu Yonghuai, Cheng Jun, Zheng Yalin, Su Pan, Yang Jianlong, Chen Li, Frangi Alejandro F. CS2-Net: Deep learning segmentation of curvilinear structures in medical imaging [J]. Medical Image Analysis, 2021, 67: 101874.
3. **Mou Lei**, Chen Li, Cheng Jun, Gu Zaiwang, Zhao Yitian, Liu Jiang. Dense dilated network with probability regularized walk for vessel detection [J]. IEEE Transactions on Medical Imaging, 2019, 39(5): 1392-1403.
4. **Mou Lei**, Qi Hong, Liu Yonghuai, Zheng Yalin, Matthew Peter, Su Pan, Liu Jiang, Zhang Jiong, Zhao Yitian. DeepGrading: deep learning grading of corneal nerve tortuosity [J]. IEEE Transactions on Medical Imaging, 2022, 41(8): 2079-2091.
5. **Mou Lei**, Lin Jinghui, Zhao Yifan, Liu Yonghuai, Ma Shaodong, Zhang Jiong, Lv Wenhao, Zhou Tao, Frangi Alejandro F, Zhao Yitian. COSTA: A Multi-center TOF-MRA Dataset and A Style Self-Consistency Network for Cerebrovascular Segmentation [J]. IEEE Transactions on Medical Imaging, 2024, 43(12): 4442-4456.
6. Gu Yuanyuan, Fang Lixin, **Mou Lei** *, Ma Shaodong, Yan Qifeng, Zhang Jiong, Liu Fang, Liu Jiang, Zhao Yitian. A ranking-based multi-scale feature calibration network for nuclear cataract grading in AS-OCT images [J]. Biomedical Signal Processing and Control, 2024, 90: 105836.
7. Fang Lixin, **Mou Lei**, Gu Yuanyuan, Hu Yan, Chen Bang, Chen Xu, Wang Yang, Liu Jiang, Zhao Yitian. Global–local multi-stage temporal convolutional network for cataract surgery phase recognition [J]. BioMedical Engineering OnLine, 2022, 21(1): 82.
8. Lin Jinghui, **Mou Lei**, Yan Qifeng, Ma Shaodong, Yue Xingyu, Zhou Shengjun, Lin Zhiqing, Zhang Jiong, Liu Jiang, Zhao Yitian. Automated segmentation of trigeminal nerve and cerebrovasculature in MR-angiography images by deep learning [J]. Frontiers in Neuroscience, 2021, 15: 744967.
9. Xia Likun, Zhang Hao, Wu Yufei, Song Ran, Ma Yuhui, **Mou Lei**, Liu Jiang, Xie Yixuan, Ma Ming, Zhao Yitian. 3D vessel-like structure segmentation in medical images by an edge-reinforced network [J]. Medical Image Analysis, 2022, 82: 102581.
10. Hu Jingfei, Wang Hua, Wu Guang, Cao Zhaohui, **Mou Lei**, Zhao Yitian, Zhang Jicong. Multi-scale interactive network with artery/vein discriminator for retinal vessel classification [J]. IEEE Journal of Biomedical and Health Informatics, 2022, 26(8): 3896-3905.
11. Tian Yuntong, Hu Yan, Ma Yuhui, Hao Huaying, **Mou Lei**, Yang Jianlong, Zhao Yitian, Liu Jiang. Multi-scale u-net with edge guidance for multimodal retinal image deformable registration; proceedings of the 2020 42nd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC), F, 2020 [C]. IEEE.
12. Chen Tao, Zhao Yitian, **Mou Lei**, Zhang Dan, Xu Xiayu, Liu Mengting, Fu Huazhu, Zhang Jiong. RBGNet: Reliable Boundary-Guided Segmentation of Choroidal Neovascularization; proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, F, 2023 [C]. Springer.
13. Xie Qihang, Zhang Dan, **Mou Lei**, Wang Shanshan, Zhao Yitian, Guo Mengguo, Zhang Jiong. DSNet: A Spatio-Temporal Consistency Network for Cerebrovascular Segmentation in Digital Subtraction Angiography Sequences; proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, F, 2024 [C]. Springer.
14. Chen Jiayu, **Mou Lei**, Ma Shaodong, Fu Huazhu, Guo Lijun, Zheng Yalin, Zhang Jiong, Zhao Yitian. NerveFormer: A Cross-Sample Aggregation Network for Corneal Nerve Segmentation; proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, F, 2022 [C]. Springer.

