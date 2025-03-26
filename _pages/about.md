---
permalink: /
title: ""
excerpt: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- bundle exec jekyll serve -->
<div id="particles-js" style="position: absolute; width: 100%; height: 100%; z-index: -1;"></div>

<div class="typewriter">
  <h1>👋 About Me</h1>
</div>

<ul class="nav-menu scroll-fade-in">
  <li class="nav-item active"><a href="#about-me">About</a></li>
  <li class="nav-item"><a href="#research-interests">Research</a></li>
  <li class="nav-item"><a href="#news">News</a></li>
  <li class="nav-item"><a href="#selected-papers">Papers</a></li>
  <li class="nav-item"><a href="#mentoring">Mentoring</a></li>
  <span class="nav-indicator"></span>
</ul>

# 👋 About Me
I am Tian Ye, a PhD student at HKUST's [ROAS Thrust](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/systems-hub/robotics-and-autonomous-systems/) and Co-founder of [MeissonFlow Research](https://huggingface.co/MeissonFlow). I am fortunate to be supervised by [Prof. Lei Zhu](https://sites.google.com/site/indexlzhu/home) and [Prof. Kan, Ge Lin](https://repository.hkust.edu.hk/ir/AuthorProfile/kan-ge-lin). During my undergraduate studies, I had the honor of being supervised by and collaborating with **Prof. Erkang Chen** and **Prof. Yun Liu**. Currently, I am working closely with [Dr. Hongwei Yi](https://xyyhw.top/) (Founding Scientist at [Hedra](https://www.hedra.com/)) to explore and develop Foundational Video Generation Models (e.g., [Magic 1-For-1](https://magic-141.github.io/Magic-141/), [MagicInfinite](https://magicinfinite.github.io)).

## 🔬 Research Interests
<div class="research-areas">
    My research focuses on two key areas:

    <div class="research-item tilt-card" data-tooltip="ICLR'25 Meissonic, IJCAI'24, Magic 1-For-1, MagicInfinite">
        <div class="tilt-card-inner">
            <div class="research-icon">🎨</div>
            <div class="research-content">
                <h3>AIGC Technology</h3>
                <p>Supporting the art creation industry and digital asset generation through advances in AIGC technology</p>
            </div>
        </div>
    </div>

    <div class="research-item" data-tooltip="ECCV'22&24,ICCV'23,CVPR'24,AAAI'23&25,IJCV'24,NeurIPS'24">
        <div class="research-icon">📸</div>
        <div class="research-content">
            <h3>Visual Quality</h3>
            <p>Exploring visual challenges in photography to create images with superior quality.</p>
        </div>
    </div>
</div>

<h2 class="animated-underline scroll-fade-in">🔬 Research Interests</h2>

# 📰 News
- [2025-03] We are pleased to announce the release of [MagicInfinite](https://magicinfinite.github.io) (Character-3 Model of Hedra Inc.). Now you can fastly generate infinite talking videos with your words and voice!
- [2025-02] 3 Papers are accepted by CVPR 2025.
- [2025-02] We are pleased to announce the release [Magic 1-For-1](https://magic-141.github.io/Magic-141/), a SOTA, *4-step image-to-video diffusion model*, along with our technical report.
- [2025-01] I am honored to be selected as a speaker at [KAUST Rising Stars in AI Symposium 2025](https://www.kaust.edu.sa/en/news/rising-stars-in-ai-symposium-2025)!! Thank you KAUST for the opportunity!
- [2025-01] [Meissonic](https://sites.google.com/view/meissonic/home?authuser=0) is accepted by ICLR 2025🎉.
- [2024-12] 4 Papers are accepted by AAAI 2025.
- [2024-11] I am honored to be selected as a Outstanding Reviewer for BMVC 2024！
- [2024-11] We release Meissonic on HuggingFace🎉, Meissonic-1B is the first SDXL level, high-resolution non-AR T2I model!!
- [2024-09] 2 Papers are accepted by ECCV 2024.
- [2024-06] 2 Papers are accepted by MICCAI 2024, and Segmamba is selected as a Spotlight presentation paper.

# 📝 Selected Papers
<!-- <p style='text-align: justify;'> My research revolves around three key areas: <strong>(I)</strong> Supporting the art creation industry and digital asset generation through advances in AIGC (Artificial Intelligence Generated Content) technology. <strong>(II)</strong> Exploring visual challenges in photography to create images with superior quality. <strong>(III)</strong> Addressing real-world image restoration and enhancement by identifying and overcoming the limitations of existing methods.
</p> -->

<style type="text/css">
    /* Color scheme stolen from Sergey Karayev */
    a {
        color: #1772d0;
        text-decoration:none !important;
    }
    a:focus, a:hover {
    color: #f09228;
    text-decoration:none !important;
    }
    table,td,th,tr{
    	border:none !important;
    }
    body,td,th,tr,p,a {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px
    }
    strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    }
    heading {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
    }
    papertitle {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700
    }
    papertitle_just {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700;
    text-align: justify
    }
    name {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 32px;
    }
    .one
    {
    width: 160px;
    height: 160px;
    position: relative;
    }
    .two
    {
    width: 160px;
    height: 160px;
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }

  .research-areas {
      background: #f8f9fa;
      padding: 25px;
      border-radius: 12px;
      margin: 20px 0;
  }

  .research-item {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: flex;
      align-items: flex-start;
      transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
      overflow: hidden;
      position: relative;
  }

  /* 鼠标悬停效果 */
  .research-item:hover {
      transform: scale(1.03);
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      background: #fafafa;
  }

  .research-icon {
      font-size: 24px;
      margin-right: 15px;
      transition: transform 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  }

  /* 图标动画效果 */
  .research-item:hover .research-icon {
      transform: scale(1.5) rotate(10deg);
  }

  .research-content {
      flex: 1;
  }

  .research-content h3 {
      margin: 0 0 10px 0;
      font-size: 1.2em;
      color: #333;
      transition: color 0.3s ease;
  }

  /* 标题颜色变化效果 */
  .research-item:hover .research-content h3 {
      color: #1772d0;
  }

  .research-content p {
      margin: 0;
      color: #666;
      line-height: 1.5;
      transition: color 0.3s ease;
  }

  /* 文字颜色变化效果 */
  .research-item:hover .research-content p {
      color: #333;
  }

  /* 添加tooltip样式 */
  .research-item {
      position: relative;
  }

  .research-item::after {
      content: attr(data-tooltip);
      position: absolute;
      bottom: 100%;
      left: 50%;
      transform: translateX(-50%);
      padding: 8px;
      background-color: rgba(0, 0, 0, 0.8);
      color: white;
      border-radius: 6px;
      font-size: 14px;
      white-space: nowrap;
      opacity: 0;
      visibility: hidden;
      transition: all 0.3s ease;
      z-index: 1000;
  }

  .research-item:hover::after {
    opacity: 1;
    visibility: visible;
    bottom: calc(100% + 10px);
  }

  /* 添加箭头 */
  .research-item::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 5px;
      background: linear-gradient(90deg, #1772d0, #f09228);
      transform: translateX(-100%);
      transition: transform 0.5s ease;
  }

  .research-item:hover::before {
      transform: translateX(0);
  }

  /* 添加到您现有的样式部分 */
  .scroll-fade-in {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }

  .scroll-fade-in.visible {
    opacity: 1;
    transform: translateY(0);
  }

  .staggered-item {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.5s ease, transform 0.5s ease;
  }

  .staggered-item.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* 打字机效果样式 */
  .typewriter h1 {
    overflow: hidden;
    border-right: .15em solid #1772d0;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: .05em;
    animation: 
      typing 3.5s steps(40, end),
      blink-caret .75s step-end infinite;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: #1772d0 }
  }

  /* 标题下划线动画 */
  .animated-underline {
    position: relative;
    display: inline-block;
  }

  .animated-underline::after {
    content: '';
    position: absolute;
    width: 0;
    height: 3px;
    bottom: 0;
    left: 0;
    background-color: #1772d0;
    transition: width 0.5s ease;
  }

  .animated-underline.visible::after {
    width: 100%;
  }

  /* 添加3D卡片效果 */
  .tilt-card {
    transform-style: preserve-3d;
    perspective: 1000px;
  }

  .tilt-card-inner {
    transition: transform 0.5s;
    transform: rotateY(0) rotateX(0);
  }

  /* 论文卡片悬停效果 */
  .paper-item {
    transition: all 0.3s ease;
    border-radius: 8px;
    padding: 10px;
    margin-bottom: 15px;
  }

  .paper-item:hover {
    background-color: rgba(23, 114, 208, 0.05);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  }

  .paper-badge {
    display: inline-block;
    font-size: 12px;
    padding: 3px 8px;
    border-radius: 12px;
    margin: 2px;
    background-color: rgba(23, 114, 208, 0.1);
    color: #1772d0;
    transition: all 0.3s ease;
  }

  .paper-badge:hover {
    background-color: rgba(23, 114, 208, 0.2);
    transform: translateY(-2px);
  }

  .paper-links a {
    margin-right: 10px;
    position: relative;
    display: inline-block;
    transition: transform 0.2s ease;
  }

  .paper-links a:hover {
    transform: translateY(-2px);
  }

  .paper-links a::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 2px;
    bottom: -2px;
    left: 0;
    background-color: #f09228;
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s ease;
  }

  .paper-links a:hover::after {
    transform: scaleX(1);
  }

  /* 导航菜单动画 */
  .nav-menu {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 30px 0;
    padding: 0;
    list-style: none;
  }

  .nav-item {
    position: relative;
  }

  .nav-item a {
    display: inline-block;
    padding: 8px 15px;
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
  }

  .nav-item a:hover {
    color: #1772d0;
  }

  .nav-item::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #1772d0;
    transform: scaleX(0);
    transform-origin: center;
    transition: transform 0.3s ease;
  }

  .nav-item:hover::after,
  .nav-item.active::after {
    transform: scaleX(1);
  }

  .nav-indicator {
    position: absolute;
    bottom: -3px;
    height: 3px;
    background-color: #1772d0;
    transition: all 0.3s ease;
  }

  /* 页面过渡动画 */
  body {
    opacity: 0;
    transition: opacity 0.8s ease;
  }

  body.loaded {
    opacity: 1;
  }

  .page-transition {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #fff;
    z-index: 9999;
    pointer-events: none;
    transform: translateY(100%);
  }

  .page-transition.active {
    animation: page-reveal 1s cubic-bezier(0.77, 0, 0.175, 1) forwards;
  }

  @keyframes page-reveal {
    0% { transform: translateY(100%); }
    100% { transform: translateY(0%); }
  }
</style>

<tbody>
<!-- 您的论文列表部分 (保留原有内容) -->
<td width="20%"></td>
<td valign="top" width="80%" class="staggered-item paper-item">
  <a href="https://www.hedra.com/">
   <papertitle_just>🔥MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice</papertitle_just>     
  </a>
  <br>
  Hongwei Yi*, <strong>Tian Ye*</strong>, Shitong Shao*, Xuancheng Yang*, Jiantong Zhao*, Hanzhong Guo*, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou
  <br>
  <span class="paper-badge">Arxiv 2025</span>
  <span class="paper-badge">Talking Avatar</span>
  <div class="paper-links">
    <a href="https://arxiv.org/abs/2503.05978">PDF</a>
    |
    <a href="https://magicinfinite.github.io/">Project</a>
    |
    <a href=""><em>Character-3 Model of Hedra Inc.</em></a>
  </div>
</td>

<!-- 其他论文部分省略 -->
</tbody>

# Mentoring
I am very lucky to work with the following talented students:
- [Heming Li], RA@HKUST(GZ), B.S.@CUHK
- [Song Fei], Mphil Student@HKUST(GZ).
- [Haoxuan Feng], Mphil Student@HKUST(GZ).
- [Chenghao Xue], Now MSc Student@UC Davis.
- [Jingxia Jiang], Now PhD Student@NC State.

# 🎖 Competitions & Awards & Presentations
- [KAUST AI Rising Star, 2025](https://www.kaust.edu.sa/en/news/rising-stars-in-ai-symposium-2025)
- [Outstanding Reviewer](https://bmvc2024.org/people/reviewers/), BMVC 2024.
- PG scholarship of HKUST(GZ), 2024.
- 2022 CVPR NAS Competition Supernet Track: Third Place Solution of Track 1 
- 2022 JMU Student Star Award  (20/19000)

# 💬 Academic Services
- Conference Reviewer: ACCV 2022&2024, WACV 2023&2024, BMVC 2023&2024, AAAI 2022&2023&2024&2025, ICCV 2023, CVPR 2024, ECCV 2024, ACM MM 2024, NeurIPS 2024, ICLR 2025, ICML 2025.

- Workshop Competition Organizer: [LOVEU@CVPR 2024](https://sites.google.com/view/loveucvpr24/track1)
  
- Journal Reviewer: 
  International Journal of Computer Vision
  IEEE Signal Processing Letter
  IEEE Journal of Oceanic Engineering

# 📖 Educations&Experience
- Aug'2024-Present: PhD Student, The Hong Kong University of Science and Technology, Guangzhou.
- Jun'2023-Jul'2024: Research Assistant, The Hong Kong University of Science and Technology, Guangzhou.
- Sep'2019-Jul'2023: B.Eng (Telecommunication Engineering), Jimei University, Xiamen.

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=KKPhQ-LXT8mek63h4Oa8BltFlbFsTTwZkLrrWb3wFEs&cl=ffffff&w=a"></script>

<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
// 基本动画效果
document.addEventListener('DOMContentLoaded', function() {
  // 滚动触发动画
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  
  document.querySelectorAll('.scroll-fade-in, .staggered-item').forEach(el => {
    observer.observe(el);
  });
  
  // 页面加载完成后显示
  document.body.classList.add('loaded');
  
  // 3D卡片效果
  document.querySelectorAll('.tilt-card').forEach(card => {
    const inner = card.querySelector('.tilt-card-inner');
    if (!inner) return;
    
    card.addEventListener('mousemove', e => {
      const rect = card.getBoundingClientRect();
      const x = e.clientX - rect.left;
      const y = e.clientY - rect.top;
      const centerX = rect.width / 2;
      const centerY = rect.height / 2;
      const angleX = (y - centerY) / 20;
      const angleY = (centerX - x) / 20;
      inner.style.transform = `rotateX(${angleX}deg) rotateY(${angleY}deg)`;
    });
    
    card.addEventListener('mouseleave', () => {
      inner.style.transform = 'rotateX(0) rotateY(0)';
    });
  });
  
  // 粒子效果
  if (typeof particlesJS !== 'undefined') {
    particlesJS('particles-js', {
      particles: {
        number: { value: 50, density: { enable: true, value_area: 800 } },
        color: { value: "#1772d0" },
        opacity: { value: 0.3, random: true },
        size: { value: 3, random: true },
        line_linked: {
          enable: true,
          distance: 150,
          color: "#1772d0",
          opacity: 0.2,
          width: 1
        },
        move: {
          enable: true,
          speed: 1,
          direction: "none",
          random: true,
          out_mode: "out"
        }
      },
      interactivity: {
        detect_on: "canvas",
        events: {
          onhover: { enable: true, mode: "grab" },
          resize: true
        },
        modes: {
          grab: { distance: 140, line_linked: { opacity: 0.5 } }
        }
      }
    });
  }
});
</script>