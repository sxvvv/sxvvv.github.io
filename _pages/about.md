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

<div id="motto" class="animated-motto"></div>

<style>
/* 创新动画效果替代打字机效果 */
.animated-motto {
    font-style: italic;
    font-size: 24px;
    margin: 20px 0;
    min-height: 36px;
    font-family: 'Georgia', serif;
    font-weight: 500;
    text-align: center;
    position: relative;
    overflow: hidden;
    padding: 15px;
    border-radius: 10px;
    background: linear-gradient(45deg, rgba(142, 68, 173, 0.1), rgba(155, 89, 182, 0.1));
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}

.motto-text {
    background: linear-gradient(45deg, #8e44ad, #9b59b6, #3498db, #1abc9c);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientFlow 8s ease infinite;
}

@keyframes gradientFlow {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

.motto-highlight {
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, 
                transparent 0%, 
                rgba(255, 255, 255, 0.2) 50%, 
                transparent 100%);
    animation: shimmer 3s infinite;
}

@keyframes shimmer {
    0% { left: -100%; }
    100% { left: 100%; }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const mottoElement = document.getElementById('motto');
    const mottoText = "Success is not final, failure is not fatal: It is the courage to continue that counts.";
    
    // 创建文本元素
    const textElement = document.createElement('div');
    textElement.className = 'motto-text';
    textElement.textContent = mottoText;
    
    // 创建高光效果元素
    const highlightElement = document.createElement('div');
    highlightElement.className = 'motto-highlight';
    
    // 添加到DOM
    mottoElement.appendChild(textElement);
    mottoElement.appendChild(highlightElement);
    
    // 添加文本出现动画
    textElement.style.opacity = '0';
    setTimeout(() => {
        textElement.style.transition = 'opacity 1.5s ease-in-out';
        textElement.style.opacity = '1';
    }, 500);
});
</script>

## 🔬 Research Interests
<div class="research-areas">
    My research focuses on the following key areas:

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

<style>
.research-areas {
    background: #f9f4fa;
    padding: 25px;
    border-radius: 12px;
    margin: 20px 0;
    position: relative;
    z-index: 1;
    overflow: hidden;
}

/* 创新:添加动态背景 */
.research-areas::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(circle at 50% 50%, rgba(155, 89, 182, 0.15), transparent 70%);
    z-index: -1;
    animation: pulse 8s ease-in-out infinite alternate;
}

@keyframes pulse {
    0% { transform: scale(1); opacity: 0.7; }
    100% { transform: scale(1.5); opacity: 0.3; }
}

.research-item {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(142, 68, 173, 0.1);
    display: flex;
    align-items: flex-start;
    transition: all 0.5s cubic-bezier(0.165, 0.84, 0.44, 1);
    position: relative;
    overflow: hidden;
    z-index: 1;
}

.research-item::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(135deg, rgba(142, 68, 173, 0.1) 0%, rgba(142, 68, 173, 0) 75%);
    z-index: -1;
    transform: translateY(100%);
    transition: transform 0.5s cubic-bezier(0.165, 0.84, 0.44, 1);
}

.research-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 30px rgba(142, 68, 173, 0.2);
}

.research-item:hover::after {
    transform: translateY(0);
}

.research-icon {
    font-size: 28px;
    margin-right: 20px;
    transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    position: relative;
}

.research-item:hover .research-icon {
    transform: scale(1.2) rotate(10deg);
}

/* 创新:添加图标特效 */
.research-icon::after {
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 0;
    height: 0;
    background: rgba(142, 68, 173, 0.2);
    border-radius: 50%;
    transform: translate(-50%, -50%);
    z-index: -1;
    transition: all 0.5s ease;
}

.research-item:hover .research-icon::after {
    width: 45px;
    height: 45px;
}

.research-content {
    flex: 1;
}

.research-content h3 {
    margin: 0 0 10px 0;
    font-size: 1.2em;
    color: #333;
    transition: all 0.3s ease;
    position: relative;
    display: inline-block;
}

/* 创新:标题下划线动画 */
.research-content h3::after {
    content: '';
    position: absolute;
    bottom: -3px;
    left: 0;
    width: 0;
    height: 2px;
    background: linear-gradient(to right, #8e44ad, #9b59b6);
    transition: width 0.5s ease;
}

.research-item:hover .research-content h3::after {
    width: 100%;
}

.research-content p {
    margin: 0;
    color: #666;
    line-height: 1.5;
    transition: color 0.3s ease;
}

.research-item:hover .research-content p {
    color: #333;
}

/* 创新:提示工具提示样式 */
.research-item {
    position: relative;
}

.research-item::before {
    content: attr(data-tooltip);
    position: absolute;
    bottom: 110%;
    left: 50%;
    padding: 8px 15px;
    background: rgba(142, 68, 173, 0.9);
    color: white;
    font-size: 14px;
    white-space: nowrap;
    border-radius: 6px;
    transform: translateX(-50%) scale(0.5);
    opacity: 0;
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    pointer-events: none;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.research-item:hover::before {
    opacity: 1;
    transform: translateX(-50%) scale(1);
    bottom: calc(100% + 15px);
}
</style>

# 📰 News
- [2025-04] Joining the Advanced Visual Computing Lab at Fuzhou University!
- [2025-03] Successfully passed the research proposal defense.
- [2024-12] Working on a new project in UHD image restoration.
- [2024-09] Started my Master's program at Fuzhou University.

# 📝 Selected Publications
<div class="publications">
    <div class="publication-item">
        <div class="pub-info">
            <div class="pub-title">Working on exciting research - publications coming soon!</div>
            <div class="pub-authors">Stay tuned for updates on my research work and publications.</div>
        </div>
    </div>
</div>

<style>
.publications {
    margin: 20px 0;
}

.publication-item {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
}

.publication-item::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 4px;
    height: 100%;
    background: linear-gradient(to bottom, #8e44ad, #9b59b6);
}

.pub-title {
    font-weight: bold;
    margin-bottom: 8px;
    color: #333;
}

.pub-authors {
    color: #666;
    font-style: italic;
}
</style>

# 💬 Academic Services
- Peer reviewer for undergraduate research projects at Jimei University
- Student representative for academic affairs, Fuzhou University
- Volunteer at the International Conference on Computer Vision (ICCV) 2023

# 📖 Education & Experience
- Aug'2023-Present: Master Student, Fuzhou University, Fuzhou.  
- Sep'2019-Jul'2023: B.Eng (Telecommunication Engineering), Jimei University, Xiamen.

# 🏆 Honors & Awards
- Outstanding Graduate, Jimei University, 2023
- First Prize, College Students' Innovation and Entrepreneurship Competition, 2022
- Second Prize, National College Students' Electronics Design Contest, 2021
- Excellent Student Scholarship, Jimei University, 2019-2023

<style>
/* 创新:背景动画效果 */
body {
    position: relative;
    background: #f8f9fa;
    overflow-x: hidden;
}

body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: 
        radial-gradient(circle at 5% 15%, rgba(142, 68, 173, 0.05) 0%, transparent 25%),
        radial-gradient(circle at 95% 85%, rgba(155, 89, 182, 0.05) 0%, transparent 25%),
        radial-gradient(circle at 90% 10%, rgba(41, 128, 185, 0.05) 0%, transparent 25%),
        radial-gradient(circle at 10% 90%, rgba(26, 188, 156, 0.05) 0%, transparent 25%);
    z-index: -1;
}

/* 创新:添加浮动元素 */
body::after {
    content: '';
    position: fixed;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="50" cy="50" r="1.5" fill="%238e44ad" opacity="0.2"/></svg>') repeat;
    animation: backgroundMovement 150s linear infinite;
    z-index: -1;
    pointer-events: none;
}

@keyframes backgroundMovement {
    0% { transform: translate(0, 0) scale(1); }
    25% { transform: translate(50px, -30px) scale(1.05); }
    50% { transform: translate(0, -60px) scale(1); }
    75% { transform: translate(-50px, -30px) scale(0.95); }
    100% { transform: translate(0, 0) scale(1); }
}

/* 整体动画效果 */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

h2, h1, section, .research-areas {
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 0;
}

h2 { animation-delay: 0.2s; }
section:nth-of-type(1) { animation-delay: 0.3s; }
.research-areas { animation-delay: 0.5s; }
section:nth-of-type(2) { animation-delay: 0.7s; }
section:nth-of-type(3) { animation-delay: 0.9s; }
section:nth-of-type(4) { animation-delay: 1.1s; }

/* 鼠标悬停效果增强 */
h2 {
    position: relative;
    display: inline-block;
    margin-bottom: 15px;
}

h2::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 3px;
    background: linear-gradient(to right, #8e44ad, #9b59b6);
    transition: width 0.4s ease;
}

h2:hover::after {
    width: 100%;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    // 背景鼠标跟踪效果
    document.addEventListener('mousemove', function(e) {
        const mouseX = e.clientX / window.innerWidth;
        const mouseY = e.clientY / window.innerHeight;
        
        document.documentElement.style.setProperty('--mouse-x', mouseX);
        document.documentElement.style.setProperty('--mouse-y', mouseY);
        
        const researchAreas = document.querySelector('.research-areas');
        if (researchAreas) {
            const moveX = (mouseX - 0.5) * 10;
            const moveY = (mouseY - 0.5) * 10;
            researchAreas.style.backgroundPosition = `${50 + moveX}% ${50 + moveY}%`;
        }
    });
    
    // 在滚动时添加动画
    const animateOnScroll = function() {
        const elements = document.querySelectorAll('.research-item, .publication-item');
        elements.forEach(element => {
            const elementTop = element.getBoundingClientRect().top;
            const elementVisible = 150;
            
            if (elementTop < window.innerHeight - elementVisible) {
                element.style.opacity = "1";
                element.style.transform = "translateY(0)";
            } else {
                element.style.opacity = "0";
                element.style.transform = "translateY(30px)";
            }
        });
    };
    
    // 初始状态
    const items = document.querySelectorAll('.research-item, .publication-item');
    items.forEach(item => {
        item.style.opacity = "0";
        item.style.transform = "translateY(30px)";
        item.style.transition = "all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1)";
    });
    
    // 监听滚动事件
    window.addEventListener('scroll', animateOnScroll);
    // 初始触发一次以显示首屏元素
    setTimeout(animateOnScroll, 300);
});
</script>
