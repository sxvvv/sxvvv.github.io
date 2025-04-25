---
permalink: /
title: ""
excerpt: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## 👋 About Me
I am Xin Su, a Master's student at Fuzhou University. I am fortunate to be supervised by [Dr. Zhuoran Zheng](https://scholar.google.com/citations?user=pXzPL-sAAAAJ&hl=zh-CN&oi=ao).
<div id="motto" class="simple-motto">"Success is not final, failure is not fatal: It is the courage to continue that counts." </div>

<style>
.simple-motto {
    font-style: italic;
    font-size: 22px;
    color: #333;
    margin: 20px 0;
    text-align: center;
    font-family: 'Georgia', serif;
    font-weight: 500;
    max-width: 80%;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.6;
    background: linear-gradient(to right, #1772d0, #6c5ce7);
    padding: 10px;
    border-radius: 10px;
    color: white;
    text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.2);
}
</style>
## 🔬 Research Interests
<div class="research-areas">
    My research focuses on the following key areas:

<div class="research-areas">
    <div class="research-item" data-tooltip="UHD Image Restoration, All-in-one Image Restoration, Advanced Restoration Models">
        <div class="research-icon">🖼️</div>
        <div class="research-content">
            <h3>UHD & All-in-one Image Restoration</h3>
            <p>Focusing on developing innovative solutions for ultra-high-definition (UHD) image restoration and comprehensive image restoration models.</p>
        </div>
    </div>

    <div class="research-item" data-tooltip="AIGC, Visual Quality, Content Creation">
        <div class="research-icon">🤖</div> 
        <div class="research-content">
            <h3>AIGC Technology</h3>
            <p>Exploring how artificial intelligence generates content, enhancing the creation process in various artistic fields.</p>
        </div>
    </div>

</div>
# 📰 News
<!-- <div class="news-container"> -->


<!-- </div> -->
# 💬 Academic Services
-

# 📖 Educations&Experience
- Aug'2023-Present: Master Student, Fuzhou University, Fuzhou.  
- Sep'2019-Jul'2023: B.Eng (Telecommunication Engineering), Jimei University, Xiamen.


<style>
.research-areas {
    background: #f9f4fa;
    padding: 25px;
    border-radius: 12px;
    margin: 20px 0;
}

.research-item {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 1px 3px rgba(142, 68, 173, 0.1);
    display: flex;
    align-items: flex-start;
}

.research-icon {
    font-size: 24px;
    margin-right: 15px;
    color: #9b59b6;
}

.research-content h3 {
    margin: 0 0 10px 0;
    font-size: 1.2em;
    color: #333;
}

.research-content p {
    margin: 0;
    color: #666;
    line-height: 1.5;
}

/* 添加页面加载动画 */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* 为主要内容块添加动画 */
.research-areas,
.news-section,
.papers-section,
h1, h2, h3 {
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 0;
}

/* 为不同部分设置不同的动画延迟 */
h1 { animation-delay: 0.2s; }
.research-areas { animation-delay: 0.4s; }
.news-section { animation-delay: 0.6s; }
.papers-section { animation-delay: 0.8s; }

/* 增强研究领域卡片的动画效果 */
.research-item {
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    position: relative;
    overflow: hidden;
}

.research-item::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(120deg, transparent 0%, transparent 50%, rgba(213, 184, 255, 0.3) 50%, transparent 51%, transparent 100%);
    transform: translateX(-100%);
    transition: all 0.6s;
}

.research-item:hover::before {
    transform: translateX(100%);
}

.research-item:hover {
    transform: translateY(-5px) scale(1.02);
    box-shadow: 0 10px 20px rgba(142, 68, 173, 0.1);
}

/* 为图标添加旋转动画 */
.research-icon {
    transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
}

.research-item:hover .research-icon {
    transform: rotate(360deg) scale(1.2);
}

/* 为标题添加渐变色效果 */
.research-content h3 {
    background: linear-gradient(120deg, #8e44ad, #9b59b6);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: all 0.3s ease;
}

/* 添加鼠标跟随效果 */
.research-item:hover::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: radial-gradient(circle at var(--x) var(--y), 
                               rgba(213, 184, 255, 0.3) 0%,
                               transparent 50%);
    pointer-events: none;
}

/* 添加粒子背景的容器 */
#particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    background: linear-gradient(45deg, #f9f4fa 0%, #fff 100%);
}

/* 确保内容在粒子之上 */
.wrapper {
    position: relative;
    z-index: 1;
}

/* 为内容添加玻璃态效果 */
.research-areas,
.news-section,
.papers-section {
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(213, 184, 255, 0.3);
    border-radius: 15px;
    padding: 25px;
    margin: 20px 0;
    box-shadow: 0 8px 32px 0 rgba(142, 68, 173, 0.1);
}

/* 添加炫酷的渐变边框效果 */
.research-item {
    position: relative;
    background: rgba(255, 255, 255, 0.9);
    border-radius: 10px;
    padding: 20px;
    margin: 15px 0;
    overflow: hidden;
}

.research-item::before {
    content: '';
    position: absolute;
    top: -2px;
    left: -2px;
    right: -2px;
    bottom: -2px;
    background: linear-gradient(45deg, #9b59b6, #c39bd3, #8e44ad);
    z-index: -1;
    border-radius: 12px;
    animation: borderGradient 4s ease infinite;
    opacity: 0;
    transition: opacity 0.3s ease;
}

.research-item:hover::before {
    opacity: 1;
}

@keyframes borderGradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

/* 添加霓虹光效果 */
.research-icon {
    text-shadow: 0 0 10px rgba(142, 68, 173, 0.5);
    animation: glowing 2s ease-in-out infinite;
}

@keyframes glowing {
    0% { filter: drop-shadow(0 0 2px rgba(142, 68, 173, 0.5)); }
    50% { filter: drop-shadow(0 0 8px rgba(142, 68, 173, 0.8)); }
    100% { filter: drop-shadow(0 0 2px rgba(142, 68, 173, 0.5)); }
}

/* 优化标题动画效果 */
.research-content h3 {
    background: linear-gradient(120deg, #8e44ad, #9b59b6, #8e44ad);
    background-size: 200% auto;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientText 3s linear infinite;
}

@keyframes gradientText {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}
</style>

<!-- 添加粒子背景容器 -->
<div id="particles-js"></div>

<!-- 添加粒子效果的脚本 -->
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
document.addEventListener('DOMContentLoaded', () => {
    particlesJS('particles-js', {
        particles: {
            number: {
                value: 80,
                density: {
                    enable: true,
                    value_area: 800
                }
            },
            color: {
                value: '#9b59b6'
            },
            shape: {
                type: 'circle'
            },
            opacity: {
                value: 0.5,
                random: false
            },
            size: {
                value: 3,
                random: true
            },
            line_linked: {
                enable: true,
                distance: 150,
                color: '#9b59b6',
                opacity: 0.4,
                width: 1
            },
            move: {
                enable: true,
                speed: 2,
                direction: 'none',
                random: false,
                straight: false,
                out_mode: 'out',
                bounce: false
            }
        },
        interactivity: {
            detect_on: 'canvas',
            events: {
                onhover: {
                    enable: true,
                    mode: 'repulse'
                },
                onclick: {
                    enable: true,
                    mode: 'push'
                },
                resize: true
            }
        },
        retina_detect: true
    });
});
</script>
