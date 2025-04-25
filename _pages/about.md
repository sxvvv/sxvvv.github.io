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

<div id="motto" class="epic-motto">
    <div class="motto-bg"></div>
    <div class="motto-container">
        <div class="motto-icon">⚡</div>
        <div class="motto-text">
            <span class="motto-highlight">Vision without execution is hallucination.</span>
            <span class="motto-author">— Edison</span>
        </div>
    </div>
</div>
<style>
  
.epic-motto {
    position: relative;
    margin: 40px auto;
    max-width: 90%;
    min-height: 120px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(142, 68, 173, 0.2);
}

.motto-bg {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(135deg, #8e44ad, #9b59b6, #3498db);
    background-size: 300% 300%;
    animation: gradientBG 10s ease infinite;
    z-index: 1;
    opacity: 0.9;
}

.motto-bg::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: 
        radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 40%),
        radial-gradient(circle at 80% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 40%);
}

.motto-container {
    position: relative;
    z-index: 2;
    display: flex;
    align-items: center;
    padding: 25px 30px;
    color: white;
}

.motto-icon {
    font-size: 40px;
    margin-right: 25px;
    text-shadow: 0 0 15px rgba(255, 255, 255, 0.7);
    animation: pulseIcon 2s ease-in-out infinite alternate;
}

.motto-text {
    flex: 1;
    display: flex;
    flex-direction: column;
}

.motto-highlight {
    font-family: 'Georgia', serif;
    font-style: italic;
    font-size: 24px;
    font-weight: 500;
    line-height: 1.4;
    margin-bottom: 8px;
    text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 1s ease forwards 0.3s;
}

.motto-author {
    align-self: flex-end;
    font-size: 16px;
    opacity: 0.8;
    font-style: italic;
    opacity: 0;
    transform: translateX(20px);
    animation: fadeInLeft 1s ease forwards 1s;
}

@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

@keyframes pulseIcon {
    0% { transform: scale(1); text-shadow: 0 0 10px rgba(255, 255, 255, 0.5); }
    100% { transform: scale(1.15); text-shadow: 0 0 20px rgba(255, 255, 255, 0.8), 0 0 30px rgba(255, 255, 255, 0.4); }
}

@keyframes fadeInUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeInLeft {
    from { opacity: 0; transform: translateX(20px); }
    to { opacity: 1; transform: translateX(0); }
}

/* 添加闪光效果 */
.motto-bg::after {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: linear-gradient(
        to right,
        rgba(255, 255, 255, 0) 0%,
        rgba(255, 255, 255, 0) 40%,
        rgba(255, 255, 255, 0.3) 50%,
        rgba(255, 255, 255, 0) 60%,
        rgba(255, 255, 255, 0) 100%
    );
    transform: rotate(30deg);
    animation: shimmerEffect 7s infinite;
}

@keyframes shimmerEffect {
    0% { transform: rotate(30deg) translateX(-100%); }
    100% { transform: rotate(30deg) translateX(100%); }
}
</style>

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
<div class="news-section animated-section">
    <ul>
        <li>[2025-03] My first paper Accepted by Neurocomputing.</li>
        <li>[2024-04] Working on a new project in UHD image restoration.</li>
        <li>[2024-02] Working on a new project in medical image enhancement.</li>
    </ul>
</div>

# 📖 Education & Experience
<div class="education-section animated-section">
    <ul>
        <li>Aug'2023-Present: Master Student, Fuzhou University, Fuzhou.</li>  
        <li>Sep'2019-Jul'2023: B.Eng (Telecommunication Engineering), Jimei University, Xiamen.</li>
    </ul>
</div>

# 🏆 Honors & Awards
<div class="awards-section animated-section">
    <div class="award-item">
        <div class="award-icon">🎓</div>
        <div class="award-content">
            <h3>Outstanding Graduate</h3>
            <p>Jimei University, 2023</p>
        </div>
    </div>
    <div class="award-item">
        <div class="award-icon">🏆</div>
        <div class="award-content">
            <h3>First Prize</h3>
            <p>National College Students' Electronics Design Contest, 2021</p>
        </div>
    </div>
    <div class="award-item">
        <div class="award-icon">🥉</div>
        <div class="award-content">
            <h3>National Third Prize</h3>
            <p>Team Leader: Mathorcup Mathematical Contest in Modeling, 2021</p>
        </div>
    </div>
    <div class="award-item">
        <div class="award-icon">🎯</div>
        <div class="award-content">
            <h3>Excellent Student Scholarship</h3>
            <p>Jimei University, 2019-2023</p>
        </div>
    </div>
</div>

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

/* 新的奖项样式和动画 */
.animated-section {
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 1; /* 确保初始可见 */
}

.award-item {
    background: white;
    padding: 15px 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(142, 68, 173, 0.1);
    display: flex;
    align-items: center;
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
}

.award-item::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 3px;
    height: 100%;
    background: linear-gradient(to bottom, #8e44ad, #9b59b6);
}

.award-item:hover {
    transform: translateX(5px);
    box-shadow: 0 5px 15px rgba(142, 68, 173, 0.2);
}

.award-icon {
    font-size: 28px;
    margin-right: 20px;
    transition: all 0.3s ease;
}

.award-item:hover .award-icon {
    transform: scale(1.2);
}

.award-content {
    flex: 1;
}

.award-content h3 {
    margin: 0 0 5px 0;
    font-size: 1.1em;
    color: #333;
}

.award-content p {
    margin: 0;
    color: #666;
}

/* 标题样式 */
h2 {
    position: relative;
    display: inline-block;
    margin-bottom: 15px;
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 1; /* 确保初始可见 */
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

/* 确保所有列表样式一致 */
.news-section ul, .education-section ul {
    padding-left: 20px;
    list-style-type: none;
}

.news-section li, .education-section li {
    position: relative;
    padding: 10px 0;
    padding-left: 15px;
}

.news-section li::before, .education-section li::before {
    content: '';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #8e44ad;
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
    
    // 为Award Items添加进入动画
    const awardItems = document.querySelectorAll('.award-item');
    awardItems.forEach((item, index) => {
        item.style.opacity = '0';
        item.style.transform = 'translateY(20px)';
        setTimeout(() => {
            item.style.transition = 'all 0.5s ease';
            item.style.opacity = '1';
            item.style.transform = 'translateY(0)';
        }, 200 + (index * 150)); // 错开时间，产生连续出现效果
    });
    
    // 为悬停添加光效
    const allItems = document.querySelectorAll('.research-item, .award-item');
    allItems.forEach(item => {
        item.addEventListener('mousemove', function(e) {
            const rect = this.getBoundingClientRect();
            const x = e.clientX - rect.left;
            const y = e.clientY - rect.top;
            
            this.style.setProperty('--x', x + 'px');
            this.style.setProperty('--y', y + 'px');
        });
    });
});
</script>
