<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jinnan Chen - Academic Profile</title>
  <style>
    :root {
      --primary-color: #3498db;
      --secondary-color: #2c3e50;
      --accent-color: #FF8000;
      --background-color: #ffffff;
      --card-bg-color: #f8f9fa;
      --text-color: #333333;
      --link-color: #3498db;
      --link-hover-bg: #d2e9f7;
      --link-bg: #e8f4fc;
      --border-radius: 8px;
      --box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      --transition: all 0.2s ease;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: var(--text-color);
      background-color: var(--background-color);
      padding: 0;
      margin: 0;
    }

    .container {
      max-width: 1200px;
      margin: 20px auto 40px;
      padding: 30px;
      background-color: var(--background-color);
      box-shadow: var(--box-shadow);
      border-radius: var(--border-radius);
    }

    .section-header {
      margin-top: 40px;
      margin-bottom: 20px;
      border-bottom: 2px solid var(--primary-color);
      padding-bottom: 10px;
      color: var(--secondary-color);
      font-size: 28px;
    }

    .section-header:first-of-type {
      margin-top: 0;
    }

    p {
      margin-bottom: 20px;
    }

    a {
      color: var(--link-color);
      text-decoration: none;
      transition: var(--transition);
    }

    a:hover {
      text-decoration: underline;
    }

    strong {
      font-weight: bold;
      color: var(--secondary-color);
    }

    .job-market {
      color: var(--accent-color);
      font-weight: bold;
      font-size: 18px;
      background-color: #fff7ed;
      padding: 10px 15px;
      border-radius: var(--border-radius);
      border-left: 4px solid var(--accent-color);
      display: inline-block;
      margin-top: 15px;
      margin-bottom: 15px;
    }

    .list-container {
      margin-left: 20px;
    }

    .list-container li {
      margin-bottom: 8px;
      list-style-type: none;
      position: relative;
      padding-left: 5px;
    }

    .list-container li:before {
      content: "•";
      position: absolute;
      left: -15px;
      color: var(--primary-color);
    }

    .publication-item {
      display: flex;
      margin-bottom: 40px;
      align-items: flex-start;
      background-color: var(--card-bg-color);
      border-radius: var(--border-radius);
      padding: 20px;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .publication-item:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    }

    .publication-image {
      flex: 0 0 300px;
      margin-right: 30px;
    }

    .publication-image img,
    .publication-image video {
      width: 100%;
      border-radius: 6px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
      background-color: #f0f0f0;
    }

    .publication-content {
      flex: 1;
    }

    .publication-content strong {
      font-size: 18px;
      color: var(--secondary-color);
      display: block;
      margin-bottom: 8px;
    }

    .publication-links {
      margin: 8px 0;
    }

    .publication-links a {
      color: var(--link-color);
      text-decoration: none;
      margin-right: 8px;
      padding: 2px 6px;
      border-radius: 4px;
      background-color: var(--link-bg);
      transition: background-color 0.2s;
      display: inline-block;
      margin-bottom: 5px;
    }

    .publication-links a:hover {
      background-color: var(--link-hover-bg);
      text-decoration: underline;
    }

    .publication-venue {
      font-style: italic;
      margin-top: 8px;
    }

    .video-placeholder {
      position: relative;
      background-color: #eee;
      height: 0;
      padding-bottom: 56.25%; /* 16:9 aspect ratio */
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 6px;
      overflow: hidden;
    }

    .video-placeholder .placeholder-text {
      position: absolute;
      text-align: center;
      color: #555;
      padding: 20px;
    }

    @media (max-width: 768px) {
      .container {
        padding: 15px;
        margin: 10px;
      }
      
      .publication-item {
        flex-direction: column;
      }
      
      .publication-image {
        flex: 0 0 100%;
        margin-bottom: 20px;
        margin-right: 0;
      }
      
      .job-market {
        display: block;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h2 class="section-header">About Me</h2>
    <p>
      I'm currently a Ph.D. candidate at NUS School of Computing, supervised by Prof <a href="#">Gim hee Lee</a>. 
      I received my B.E. degree from Wuhan University and MEng degree from Nanyang Technology University with a GPA of 5.0/5.0. During my master's study, I was supervised by Prof <a href="https://personal.ntu.edu.sg/exdjiang/">Jiang Xudong</a> and Dr <a href="https://person.zju.edu.cn/zq">Qian Zheng</a>.
    </p>
    <p>
      Currently, my research interests are mainly in 3D computer vision, especially in 3D Assets Generation and Human Digitization, including <strong>Reconstruction</strong> (Neural Fields & 3DGS), <strong>Animation</strong> (Skinning & Rigging), and <strong>Generation</strong> (Diffusion & AR).
    </p>
    <div class="job-market">I'm on the job market and looking for a Research Scientist/Engineer position starting in the 2025 Fall. Feel free to reach out if you have any openings!</div>
    
    <h2 class="section-header">News</h2>
    <div class="list-container">
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

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="MuMA Teaser">
      </div>
      <div class="publication-content">
        <strong>MuMA: 3D PBR Texturing via Multi-Channel Multi-View Generation and Agentic Post-Processing</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2503.18461">[arXiv]</a>
        </div>
        <div>Lingting Zhu, Jingrui Ye, Runze Zhang, Zeyu Hu, Yingda Yin, Lanjiong Li, <strong>Jinnan Chen</strong>, Shengju Qian, Xin Wang, Qingmin Liao, Lequan Yu</div>
        <div class="publication-venue">Arxiv 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <div class="video-placeholder">
          <div class="placeholder-text">MAR-3D Demo Video</div>
        </div>
      </div>
      <div class="publication-content">
        <strong>MAR-3D: Progressive Masked Auto-regressor for High-Resolution 3D Generation</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2503.20519">[arXiv]</a>
          <a href="https://jinnan-chen.github.io/projects/MAR-3D/">[project page]</a>
        </div>
        <div><strong>Jinnan Chen</strong>, Lingting Zhu, Zeyu Hu, Shengju Qian, Yugang Chen, Xin Wang, Gim Hee Lee</div>
        <div class="publication-venue">IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <div class="video-placeholder">
          <div class="placeholder-text">Close Human Interaction Demo Video</div>
        </div>
      </div>
      <div class="publication-content">
        <strong>Reconstructing Close Human Interaction with Appearance and Proxemics Reasoning</strong>
        <div class="publication-links">
          <a href="https://www.buzhenhuang.com/publications/papers/CVPR2025-CloseApp.pdf">[paper]</a>
          <a href="https://www.buzhenhuang.com/works/CloseApp.html">[project page]</a>
        </div>
        <div>Buzhen Huang, Chen Li, Chongyang Xu, Dongyue Lu, <strong>Jinnan Chen</strong>, Yangang Wang, Gim Hee Lee</div>
        <div class="publication-venue">IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <div class="video-placeholder">
          <div class="placeholder-text">HGM Demo Video</div>
        </div>
      </div>
      <div class="publication-content">
        <strong>Generalizable Human Gaussians from Single-View Image</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2406.06050">[arXiv]</a>
          <a href="https://jinnan-chen.github.io/projects/HGM/">[project page]</a>
        </div>
        <div><strong>Jinnan Chen</strong>, Chen Li, Jianfeng Zhang, Lingting Zhu, Buzhen Huang, Hanlin Chen, Gim Hee Lee</div>
        <div class="publication-venue">The International Conference on Learning Representations (ICLR) 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="LIG Teaser">
      </div>
      <div class="publication-content">
        <strong>Large Images are Gaussians: High-quality Large Image Representation with Levels of 2D Gaussian Splatting</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2502.09039">[arXiv]</a>
          <a href="https://github.com/HKU-MedAI/LIG">[code]</a>
        </div>
        <div>Lingting Zhu, Guying Lin, <strong>Jinnan Chen</strong>, Xinjie Zhang, Zhenchao Jin, Zhao Wang, Lequan Yu</div>
        <div class="publication-venue">The Association for the Advancement of Artificial Intelligence (AAAI) 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <div class="video-placeholder">
          <div class="placeholder-text">DiHuR Demo Video</div>
        </div>
      </div>
      <div class="publication-content">
        <strong>DiHuR: Diffusion-Guided Generalizable Human Reconstruction</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2411.11903">[arXiv]</a>
        </div>
        <div><strong>Jinnan Chen</strong>, Chen Li, Gim Hee Lee</div>
        <div class="publication-venue">IEEE/CVF Winter Conference (WACV) 2025</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="WS3DPT Teaser">
      </div>
      <div class="publication-content">
        <strong>Weakly-supervised 3D Pose Transfer with Keypoints</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2307.13459">[arXiv]</a>
          <a href="https://jinnan-chen.github.io/ws3dpt/">[project page]</a>
          <a href="https://github.com/jinnan-chen/3D-Pose-Transfer">[code]</a>
        </div>
        <div><strong>Jinnan Chen</strong>, Chen Li, Gim Hee Lee</div>
        <div class="publication-venue">IEEE International Conference on Computer Vision (ICCV) 2023</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="Absorption Teaser">
      </div>
      <div class="publication-content">
        <strong>Single image reflection removal with absorption effect</strong>
        <div class="publication-links">
          <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Zheng_Single_Image_Reflection_Removal_With_Absorption_Effect_CVPR_2021_paper.html">[paper]</a>
          <a href="https://github.com/q-zh/absorption">[code]</a>
        </div>
        <div>Qian Zheng, Boxin Shi, <strong>Jinnan Chen</strong>, Xudong Jiang, Ling-Yu Duan, Alex C. Kot</div>
        <div class="publication-venue">IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2021</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="Feature Distillation Teaser">
      </div>
      <div class="publication-content">
        <strong>Feature distillation with guided adversarial contrastive learning</strong>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2009.09922">[arXiv]</a>
        </div>
        <div>Tao Bai, <strong>Jinnan Chen</strong>, Jun Zhao, Bihan Wen, Xudong Jiang, Alex Kot</div>
        <div class="publication-venue">Arxiv 2020</div>
      </div>
    </div>

    <div class="publication-item">
      <div class="publication-image">
        <img src="/api/placeholder/400/320" alt="Glass Calibration Teaser">
      </div>
      <div class="publication-content">
        <strong>What does plate glass reveal about camera calibration?</strong>
        <div class="publication-links">
          <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Zheng_What_Does_Plate_Glass_Reveal_About_Camera_Calibration_CVPR_2020_paper.html">[paper]</a>
          <a href="https://github.com/q-zh/GlassCalibration">[code]</a>
        </div>
        <div>Qian Zheng, <strong>Jinnan Chen</strong>, Zhan Lu, Boxin Shi, Xudong Jiang, Kim-Hui Yap, Ling-Yu Duan, Alex C. Kot</div>
        <div class="publication-venue">IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2020</div>
      </div>
    </div>
    
    <h2 class="section-header">Teaching</h2>
    <div class="list-container">
      <ul>
        <li><strong>[2022]</strong> CS5340 Uncertainty Modelling in AI, National University of Singapore</li>
        <li><strong>[2022]</strong> CS5477 3D Computer Vision, National University of Singapore</li>
      </ul>
    </div>
    
    <h2 class="section-header">Reviewer</h2>
    <div class="list-container">
      <ul>
        <li>CVPR 2024, 2025</li>
        <li>ICCV 2025</li>
        <li>NeurIPS 2024, 2025</li>
        <li>ICLR 2025</li>
        <li>ICML 2025</li>
        <li>AISTATS 2025</li>
      </ul>
    </div>
    
    <h2 class="section-header">Awards</h2>
    <div class="list-container">
      <ul>
        <li>Wuhan University Excellent Student</li>
        <li>NUS Research Scholarship</li>
        <li>NUS Research Achievement</li>
      </ul>
    </div>
  </div>
</body>
</html>
