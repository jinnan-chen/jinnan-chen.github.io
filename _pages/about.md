---
layout: about
title: about
permalink: /
subtitle: # <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: pprofile.png
  image_cicular: false # crops the image to make it circular
  address: # >
    # <p>555 your office number</p>
    # <p>123 your address street</p>
    # <p>Your City, State 12345</p>

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
selected_patents: true # includes a list of patents marked as "selected={true}"
inline_lists:
  - teaching_assistants
  - awards
social: true  # includes social icons at the bottom of the page
---

<style>
body {
  margin: 0;
  padding: 0;
}

.max-width-container {
  max-width: 3000px;
  margin: 0 auto; 
  padding: 0 20px;
}

.publication-item {
  display: flex;
  margin-bottom: 30px;
  align-items: center;
}

.publication-image {
  flex: 0 0 280px;
  margin-right: 30px;
}

.publication-image img, 
.publication-image video {
  width: 100%;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.publication-content {
  flex: 1;
}

@media (max-width: 768px) {
  .publication-item {
    flex-direction: column;
  }
  
  .publication-image {
    flex: 0 0 100%;
    margin-bottom: 15px;
    margin-right: 0;
  }
}

@media (max-width: 576px) {
  .publication-content {
    font-size: 14px;
  }
  
  .section-header {
    font-size: 20px;
  }
  
  .publication-image {
    max-width: 100%;
  }
}

.section-header {
  margin-top: 40px;
  border-bottom: 1px solid #eee;
  padding-bottom: 10px;
}

.news-list, .awards-list, .teaching-list {
  margin-left: 20px;
}

/* Hide the page title if it's duplicating the author name */
.page__title {
  display: none;
}
</style>

<div class="max-width-container">
  <h2 class="section-header">About Me</h2>
  <p>
    I'm currently a Ph.D. candidate at NUS School of Computing, supervised by Prof <a href="https://www.comp.nus.edu.sg/~leegh/">Gim Hee Lee</a>. 
    I received my B.E. degree from Wuhan University and MEng degree from Nanyang Technology University with a GPA of 5.0/5.0. During my master's study, I was supervised by Prof <a href="https://personal.ntu.edu.sg/exdjiang/">Jiang Xudong</a> and Dr <a href="https://person.zju.edu.cn/zq">Qian Zheng</a>.
  </p>
  <p>
    Currently, my research interests are mainly in 3D computer vision, especially in 3D Assets Generation and Human Digitization, including <strong>Reconstruction</strong> (Neural Fields & 3DGS), <strong>Animation</strong> (Skinning & Rigging), and <strong>Generation</strong> (Diffusion & AR).
  </p>
  <p>
    <span style="color: orange; font-weight: bold;">I'm on the job market and looking for a Research Scientist/Engineer position starting in the 2025 Fall. Feel free to reach out if you have any openings!</span>
  </p>
  
  <h2 class="section-header">News</h2>
  <div class="news-list">
    <ul>
      <li><strong>🎉 [04.2025]</strong> Our MAR-3D is selected as <strong>Highlight</strong> in CVPR 2025 (Top 13.5% of accepted papers)</li>
      <li><strong>🎉 [02.2025]</strong> Two papers are accepted in CVPR 2025</li>
      <li><strong>🎉 [01.2025]</strong> One paper is accepted in ICLR 2025</li>
      <li><strong>🎉 [12.2024]</strong> One paper is accepted in AAAI 2025</li>
      <li><strong>🎉 [10.2024]</strong> One paper is accepted in WACV 2025</li>
      <li><strong>🎉 [06.2023]</strong> One paper is accepted in ICCV 2023</li>
      <li><strong>🎉 [02.2021]</strong> One paper is accepted in CVPR 2021</li>
      <li><strong>🎉 [02.2020]</strong> One paper is accepted in CVPR 2020</li>
    </ul>
  </div>
  
  <h2 class="section-header">Publications</h2>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/Teaser_Muma.png" alt="MuMA: 3D PBR Texturing via Multi-Channel Multi-View Generation">
    </div>
    <div class="publication-content">
      <strong>MuMA: 3D PBR Texturing via Multi-Channel Multi-View Generation and Agentic Post-Processing.</strong> <a href="https://arxiv.org/abs/2503.18461">[arXiv]</a><br>
      Lingting Zhu, Jingrui Ye, Runze Zhang, Zeyu Hu, Yingda Yin, Lanjiong Li, <strong>Jinnan Chen</strong>, Shengju Qian, Xin Wang, Qingmin Liao, Lequan Yu<br>
      <em>Arxiv 2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <video width="100%" autoplay loop muted playsinline>
        <source src="/videos/mar-3d.mov" type="video/quicktime">
        <source src="/videos/mar-3d.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div class="publication-content">
      <strong>MAR-3D: Progressive Masked Auto-regressor for High-Resolution 3D Generation.</strong> <a href="https://arxiv.org/abs/2503.20519">[arXiv]</a> <a href="https://jinnan-chen.github.io/projects/MAR-3D/">[page]</a><br>
      <strong>Jinnan Chen</strong>, Lingting Zhu, Zeyu Hu, Shengju Qian, Yugang Chen, Xin Wang, Gim Hee Lee<br>
      <em>IEEE Conference on Computer Vision and Pattern Recognition（<strong>CVPR</strong>）2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <video width="100%" autoplay loop muted playsinline>
        <source src="/videos/close.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div class="publication-content">
      <strong>Reconstructing Close Human Interaction with Appearance and Proxemics Reasoning.</strong> <a href="https://www.buzhenhuang.com/publications/papers/CVPR2025-CloseApp.pdf">[paper]</a> <a href="https://www.buzhenhuang.com/works/CloseApp.html">[page]</a><br>
      Buzhen Huang, Chen Li, Chongyang Xu, Dongyue Lu, <strong>Jinnan Chen</strong>, Yangang Wang, Gim Hee Lee<br>
      <em>IEEE Conference on Computer Vision and Pattern Recognition（<strong>CVPR</strong>）2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <video width="100%" autoplay loop muted playsinline>
        <source src="/videos/hgm.mov" type="video/quicktime">
        <source src="/videos/hgm.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div class="publication-content">
      <strong>Generalizable Human Gaussians from Single-View Image.</strong> <a href="https://arxiv.org/abs/2406.06050">[arXiv]</a> <a href="https://jinnan-chen.github.io/projects/HGM/">[page]</a><br>
      <strong>Jinnan Chen</strong>, Chen Li, Jianfeng Zhang, Lingting Zhu, Buzhen Huang, Hanlin Chen, Gim Hee Lee<br>
      <em>The International Conference on Learning Representations（<strong>ICLR</strong>）2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/teaser-lig.png" alt="Large Images are Gaussians: Levels of 2D Gaussian Splatting">
    </div>
    <div class="publication-content">
      <strong>Large Images are Gaussians: High-quality Large Image Representation with Levels of 2D Gaussian Splatting.</strong> <a href="https://arxiv.org/abs/2502.09039">[arXiv]</a> <a href="https://github.com/HKU-MedAI/LIG">[code]</a><br>
      Lingting Zhu, Guying Lin, <strong>Jinnan Chen</strong>, Xinjie Zhang, Zhenchao Jin, Zhao Wang, Lequan Yu<br>
      <em>The Association for the Advancement of Artificial Intelligence (<strong>AAAI</strong>) 2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <video width="100%" autoplay loop muted playsinline>
        <source src="/videos/dihur.mov" type="video/quicktime">
        <source src="/videos/dihur.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div class="publication-content">
      <strong>DiHuR: Diffusion-Guided Generalizable Human Reconstruction.</strong> <a href="https://arxiv.org/abs/2411.11903">[arXiv]</a><br>
      <strong>Jinnan Chen</strong>, Chen Li, Gim Hee Lee<br>
      <em>IEEE/CVF Winter Conference (<strong>WACV</strong>) 2025</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/ws3dpt.png" alt="Weakly-supervised 3D Pose Transfer with Keypoints">
    </div>
    <div class="publication-content">
      <strong>Weakly-supervised 3D Pose Transfer with Keypoints.</strong> <a href="https://arxiv.org/abs/2307.13459">[arXiv]</a> <a href="https://jinnan-chen.github.io/ws3dpt/">[page]</a> <a href="https://github.com/jinnan-chen/3D-Pose-Transfer">[code]</a><br>
      <strong>Jinnan Chen</strong>, Chen Li, Gim Hee Lee<br>
      <em>IEEE International Conference on Computer Vision (<strong>ICCV</strong>) 2023</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/teaser_absorption.png" alt="Single image reflection removal with absorption effect">
    </div>
    <div class="publication-content">
      <strong>Single image reflection removal with absorption effect.</strong> <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Zheng_Single_Image_Reflection_Removal_With_Absorption_Effect_CVPR_2021_paper.html">[paper]</a> <a href="https://github.com/q-zh/absorption">[code]</a><br>
      Qian Zheng, Boxin Shi, <strong>Jinnan Chen</strong>, Xudong Jiang, Ling-Yu Duan, Alex C. Kot<br>
      <em>IEEE Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>) 2021</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/teaser_distillation.png" alt="Feature distillation with guided adversarial contrastive learning">
    </div>
    <div class="publication-content">
      <strong>Feature distillation with guided adversarial contrastive learning.</strong> <a href="https://arxiv.org/abs/2009.09922">[arXiv]</a><br>
      Tao Bai, <strong>Jinnan Chen</strong>, Jun Zhao, Bihan Wen, Xudong Jiang, Alex Kot<br>
      <em>Arxiv 2020</em>
    </div>
  </article>

  <article class="publication-item">
    <div class="publication-image">
      <img src="/images/teaser_glass.png" alt="What does plate glass reveal about camera calibration?">
    </div>
    <div class="publication-content">
      <strong>What does plate glass reveal about camera calibration?</strong> <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Zheng_What_Does_Plate_Glass_Reveal_About_Camera_Calibration_CVPR_2020_paper.html">[paper]</a> <a href="https://github.com/q-zh/GlassCalibration">[code]</a><br>
      Qian Zheng, <strong>Jinnan Chen</strong>, Zhan Lu, Boxin Shi, Xudong Jiang, Kim-Hui Yap, Ling-Yu Duan, Alex C. Kot<br>
      <em>IEEE Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>) 2020</em>
    </div>
  </article>
  
  <h2 class="section-header">Teaching</h2>
  <div class="teaching-list">
    <ul>
      <li><strong>[2022]</strong> CS5340 Uncertainty Modelling in AI, National University of Singapore</li>
      <li><strong>[2022]</strong> CS5477 3D Computer Vision, National University of Singapore</li>
    </ul>
  </div>
  
  <h2 class="section-header">Reviewer</h2>
  <div class="reviewer-list" style="margin-left: 20px;">
    <p>VF Conference on Computer Vision and Pattern Recognition (CVPR) 2024,2025
          IEEE/CVF International Conference on Computer Vision (ICCV) 2025
          International Conference on Machine Learning (ICML) 2025
          Conference on Neural Information Processing Systems (NeurIPS) 2024,2025
          International Conference on Learning Representations (ICLR) 2025
          International Conference on Artificial Intelligence and Statistics (AISTATS) 2025
    </p>
  </div>
  
  <h2 class="section-header">Awards</h2>
  <div class="awards-list">
    <ul>
      <li>Wuhan University Excellent Student</li>
      <li>NUS Research Scholarship</li>
      <li>NUS Research Achievement</li>
    </ul>
  </div>
</div>

<!-- Add favicon -->
<link rel="icon" type="image/png" href="/images/favicon.png">
