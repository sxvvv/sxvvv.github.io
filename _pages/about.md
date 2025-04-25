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


.research-areas {
    background: rgba(255, 255, 255, 0.95);
    padding: 30px;
    border-radius: 16px;
    margin: 25px 0;
    box-shadow: 0 4px 12px rgba(158, 118, 180, 0.1);
    border: 1px solid rgba(199, 160, 227, 0.2);
}

.research-item {
    background: rgba(255, 255, 255, 0.95);
    padding: 25px;
    margin: 20px 0;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(158, 118, 180, 0.05);
    transition: all 0.3s ease;
    border: 1px solid rgba(199, 160, 227, 0.1);
}

/* 更新配色方案 - 科技紫色调 */
:root {
    --primary-color: #8e44ad;
    --secondary-color: #9b59b6;
    --accent-color: #d6a8e6;
    --light-accent: #f0e6f5;
    --dark-text: #2c3e50;
}

/* 更新动画效果 */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(15px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* 优雅的悬停效果 */
.research-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 15px rgba(158, 118, 180, 0.15);
    border-color: rgba(158, 118, 180, 0.3);
    background: linear-gradient(135deg, #fff 0%, var(--light-accent) 100%);
}

/* 更新标题样式 */
.research-content h3 {
    font-size: 1.3em;
    font-weight: 600;
    margin-bottom: 12px;
    background: linear-gradient(120deg, var(--primary-color), var(--secondary-color));
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    letter-spacing: 0.3px;
}

/* 文本样式 */
.research-content p {
    color: #555;
    line-height: 1.6;
    font-size: 0.95em;
}

/* 更新粒子背景 */
#particles-js {
    background: linear-gradient(135deg, #f9f4fc 0%, #eee6f3 100%);
}

/* 更新玻璃态效果 */
.research-areas,
.news-section,
.papers-section {
    background: rgba(255, 255, 255, 0.92);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(199, 160, 227, 0.25);
    box-shadow: 0 4px 15px rgba(158, 118, 180, 0.08);
}

/* 更新图标样式 */
.research-icon {
    color: var(--primary-color);
    font-size: 26px;
    transition: all 0.4s ease;
}

.research-item:hover .research-icon {
    transform: scale(1.1) rotate(5deg);
    color: var(--secondary-color);
}

/* 添加精致的装饰元素 */
.research-item::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 30%;
    height: 2px;
    background: linear-gradient(90deg, var(--primary-color), transparent);
    opacity: 0;
    transition: all 0.3s ease;
}

.research-item:hover::after {
    opacity: 0.6;
    width: 80%;
}

/* 添加更细腻的动画效果 */
.research-areas,
.news-section,
.papers-section,
h1, h2, h3 {
    animation: fadeInUp 0.7s ease-out forwards;
    animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    opacity: 0;
}

/* 更多优雅的阴影效果 */
h1, h2 {
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.05);
    color: var(--dark-text);
}

particlesJS('particles-js', {
    particles: {
        number: {
            value: 50,
            density: {
                enable: true,
                value_area: 1000
            }
        },
        color: {
            value: ['#9b59b6', '#8e44ad', '#c39bd3', '#af7ac5']
        },
        opacity: {
            value: 0.3,
            random: true,
            anim: {
                enable: true,
                speed: 1,
                opacity_min: 0.1,
                sync: false
            }
        },
        size: {
            value: 3,
            random: true,
            anim: {
                enable: true,
                speed: 2,
                size_min: 0.3,
                sync: false
            }
        },
        line_linked: {
            enable: true,
            distance: 150,
            color: '#8e44ad',
            opacity: 0.2,
            width: 1
        },
        move: {
            enable: true,
            speed: 1.2,
            direction: 'none',
            random: true,
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
                mode: 'bubble'
            },
            onclick: {
                enable: true,
                mode: 'push'
            },
            resize: true
        },
        modes: {
            bubble: {
                distance: 150,
                size: 6,
                duration: 2,
                opacity: 0.6,
                speed: 3
            },
            push: {
                particles_nb: 3
            }
        }
    }
});
