<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jinnan Chen - 个人学术网站</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }

    .main-container {
      display: flex;
      flex-wrap: wrap;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    .profile-container {
      flex: 0 0 30%;
      padding: 20px;
      background-color: #f8f9fa;
      border-radius: 5px;
      margin-right: 20px;
      margin-bottom: 20px;
    }

    .profile-image {
      width: 100%;
      max-width: 250px;
      margin-bottom: 15px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .profile-address {
      margin-top: 15px;
      font-size: 14px;
    }

    .content-container {
      flex: 1;
      min-width: 60%;
    }

    .max-width-container {
      max-width: 900px;
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
      .main-container {
        flex-direction: column;
      }
      
      .profile-container {
        flex: 0 0 100%;
        margin-right: 0;
      }
      
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

    .news-list, .awards-list, .teaching-list, .reviewer-list {
      margin-left: 20px;
    }

    /* 确保社交图标可见 */
    .social {
      display: block !important;
      margin-top: 30px;
    }

    .social-icons {
      display: flex !important;
      justify-content: center;
      margin-top: 20px;
    }

    .social-icons a {
      margin: 0 10px;
      font-size: 1.5rem;
    }

    .contact-note {
      display: block !important;
      text-align: center;
      margin-top: 10px;
    }
    
    /* 添加导航栏 */
    .navbar {
      background-color: #333;
      overflow: hidden;
      display: flex;
      justify-content: center;
    }

    .navbar a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }

    .navbar a:hover {
      background-color: #ddd;
      color: black;
    }
    
    /* 强调求职信息 */
    .job-market {
      background-color: #fff3e0;
      padding: 15px;
      border-radius: 5px;
      margin: 20px 0;
      border-left: 5px solid orange;
    }
  </style>
</head>
<body>
  <!-- 导航栏 -->
  <div class="navbar">
    <a href="#about">关于我</a>
    <a href="#news">最新消息</a>
    <a href="#publications">发表作品</a>
    <a href="#teaching">教学经历</a>
    <a href="#service">学术服务</a>
    <a href="#awards">获奖情况</a>
  </div>

  <div class="main-container">
    <!-- 个人资料部分 -->
    <div class="profile-container">
      <img src="profile.png" alt="Jinnan Chen 个人照片" class="profile-image">
      <div class="profile-address">
        <p>School of Computing</p>
        <p>National University of Singapore</p>
        <p>Singapore</p>
      </div>
      
      <!-- 社交媒体图标可以在这里添加 -->
      <div class="social-icons">
        <!-- 示例：添加更多社交媒体图标 -->
        <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="#" title="Google Scholar"><i class="fab fa-google"></i></a>
        <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
      </div>
    </div>

    <!-- 内容部分 -->
    <div class="content-container">
      <div class="max-width-container">
        <h2 class="section-header" id="about">关于我</h2>
        <p>
          I'm currently a Ph.D. candidate at NUS School of Computing, supervised by Prof <a href="https://www.comp.nus.edu.sg/~leegh/">Gim Hee Lee</a>. 
          I received my B.E. degree from Wuhan University and MEng degree from Nanyang Technology University with a GPA of 5.0/5.0. During my master's study, I was supervised by Prof <a href="https://personal.ntu.edu.sg/exdjiang/">Jiang Xudong</a> and Dr <a href="https://person.zju.edu.cn/zq">Qian Zheng</a>.
        </p>
        <p>
          Currently, my research interests are mainly in 3D computer vision, especially in 3D Assets Generation and Human Digitization, including <strong>Reconstruction</strong> (Neural Fields & 3DGS), <strong>Animation</strong> (Skinning & Rigging), and <strong>Generation</strong> (Diffusion & AR).
        </p>
        
        <div class="job-market">
          <span style="font-weight: bold;">I'm on the job market and looking for a Research Scientist/Engineer position starting in the 2025 Fall. Feel free to reach out if you have any openings!</span>
        </div>
        
        <h2 class="section-header" id="news">最新消息</h2>
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
        
        <h2 class="section-header" id="publications">发表作品</h2>

        <article class="publication-item">
          <div class="publication-image">
            <img src="images/Teaser_Muma.png" alt="MuMA: 3D PBR Texturing via Multi-Channel Multi-View Generation">
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
              <source src="videos/mar-3d.mov" type="video/mp4">
              您的浏览器不支持视频标签。
            </video>
          </div>
          <div class="publication-content">
            <strong>MAR-3D: Progressive Masked Auto-regressor for High-Resolution 3D Generation.</strong> <a href="https://arxiv.org/abs/2503.20519">[arXiv]</a> <a href="https://jinnan-chen.github.io/projects/MAR-3D/">[page]</a><br>
            <strong>Jinnan Chen</strong>, Lingting Zhu, Zeyu Hu, Shengju Qian, Yugang Chen, Xin Wang, Gim Hee Lee<br>
            <em>IEEE Conference on Computer Vision and Pattern Recognition（<strong>CVPR</strong>）2025 Highlight</em>
          </div>
        </article>

        <article class="publication-item">
          <div class="publication-image">
            <video width="100%" autoplay loop muted playsinline>
              <source src="videos/close.mp4" type="video/mp4">
              您的浏览器不支持视频标签。
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
              <source src="videos/hgm.mov" type="video/mp4">
              您的浏览器不支持视频标签。
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
            <img src="images/teaser-lig.png" alt="Large Images are Gaussians: Levels of 2D Gaussian Splatting">
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
              <source src="videos/dihur.mov" type="video/mp4">
              您的浏览器不支持视频标签。
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
            <img src="images/ws3dpt.png" alt="Weakly-supervised 3D Pose Transfer with Keypoints">
          </div>
          <div class="publication-content">
            <strong>Weakly-supervised 3D Pose Transfer with Keypoints.</strong> <a href="https://arxiv.org/abs/2307.13459">[arXiv]</a> <a href="https://jinnan-chen.github.io/ws3dpt/">[page]</a> <a href="https://github.com/jinnan-chen/3D-Pose-Transfer">[code]</a><br>
            <strong>Jinnan Chen</strong>, Chen Li, Gim Hee Lee<br>
            <em>IEEE International Conference on Computer Vision (<strong>ICCV</strong>) 2023</em>
          </div>
        </article>

        <article class="publication-item">
          <div class="publication-image">
            <img src="images/teaser_absorption.png" alt="Single image reflection removal with absorption effect">
          </div>
          <div class="publication-content">
            <strong>Single image reflection removal with absorption effect.</strong> <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Zheng_Single_Image_Reflection_Removal_With_Absorption_Effect_CVPR_2021_paper.html">[paper]</a> <a href="https://github.com/q-zh/absorption">[code]</a><br>
            Qian Zheng, Boxin Shi, <strong>Jinnan Chen</strong>, Xudong Jiang, Ling-Yu Duan, Alex C. Kot<br>
            <em>IEEE Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>) 2021</em>
          </div>
        </article>

        <article class="publication-item">
          <div class="publication-image">
            <img src="images/teaser_distillation.png" alt="Feature distillation with guided adversarial contrastive learning">
          </div>
          <div class="publication-content">
            <strong>Feature distillation with guided adversarial contrastive learning.</strong> <a href="https://arxiv.org/abs/2009.09922">[arXiv]</a><br>
            Tao Bai, <strong>Jinnan Chen</strong>, Jun Zhao, Bihan Wen, Xudong Jiang, Alex Kot<br>
            <em>Arxiv 2020</em>
          </div>
        </article>

        <article class="publication-item">
          <div class="publication-image">
            <img src="images/teaser_glass.png" alt="What does plate glass reveal about camera calibration?">
          </div>
          <div class="publication-content">
            <strong>What does plate glass reveal about camera calibration?</strong> <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Zheng_What_Does_Plate_Glass_Reveal_About_Camera_Calibration_CVPR_2020_paper.html">[paper]</a> <a href="https://github.com/q-zh/GlassCalibration">[code]</a><br>
            Qian Zheng, <strong>Jinnan Chen</strong>, Zhan Lu, Boxin Shi, Xudong Jiang, Kim-Hui Yap, Ling-Yu Duan, Alex C. Kot<br>
            <em>IEEE Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>) 2020</em>
          </div>
        </article>
        
        <h2 class="section-header" id="teaching">教学经历</h2>
        <div class="teaching-list">
          <ul>
            <li><strong>[2022]</strong> CS5340 Uncertainty Modelling in AI, National University of Singapore</li>
            <li><strong>[2022]</strong> CS5477 3D Computer Vision, National University of Singapore</li>
          </ul>
        </div>
        
        <h2 class="section-header" id="service">学术服务（审稿人）</h2>
        <div class="reviewer-list">
          <ul>
            <li>Conference on Computer Vision and Pattern Recognition (CVPR) 2024, 2025</li>
            <li>IEEE/CVF International Conference on Computer Vision (ICCV) 2025</li>
            <li>International Conference on Machine Learning (ICML) 2025</li>
            <li>Conference on Neural Information Processing Systems (NeurIPS) 2024, 2025</li>
            <li>International Conference on Learning Representations (ICLR) 2025</li>
            <li>International Conference on Artificial Intelligence and Statistics (AISTATS) 2025</li>
          </ul>
        </div>
        
        <h2 class="section-header" id="awards">获奖情况</h2>
        <div class="awards-list">
          <ul>
            <li>Wuhan University Excellent Student</li>
            <li>NUS Research Scholarship</li>
            <li>NUS Research Achievement</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- 如果需要添加字体图标支持，可以添加 Font Awesome -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
