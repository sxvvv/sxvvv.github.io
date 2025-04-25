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

/* Import a modern, clean font (optional, replace with your preferred font) */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap');

/* Define root variables for easy color theming */
:root {
    --primary-color: #7C3AED; /* Vibrant Purple */
    --secondary-color: #EC4899; /* Bright Pink */
    --accent-color: #10B981; /* Emerald Green */
    --background-start: #F3E8FF; /* Light Lavender */
    --background-end: #FFF7ED; /* Pale Peach */
    --text-dark: #1F2937; /* Dark Gray */
    --text-light: #6B7280; /* Medium Gray */
    --glass-bg: rgba(255, 255, 255, 0.65);
    --glass-border: rgba(255, 255, 255, 0.4);
    --shadow-light: rgba(107, 114, 128, 0.1);
    --shadow-medium: rgba(107, 114, 128, 0.15);
}

body {
    font-family: 'Poppins', sans-serif; /* Apply the clean font */
    color: var(--text-dark);
    line-height: 1.6;
}

/* --- Particle Background Container --- */
#particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    /* Soft gradient background behind particles */
    background: linear-gradient(45deg, var(--background-start) 0%, var(--background-end) 100%);
}

/* --- Main Content Wrapper --- */
.wrapper {
    position: relative;
    z-index: 1;
    max-width: 1100px; /* Control max width for readability */
    margin: 0 auto; /* Center the content */
    padding: 20px;
}

/* --- Glassmorphism Sections --- */
.research-areas,
.news-section,
.papers-section { /* Apply to all major content blocks */
    background: var(--glass-bg);
    backdrop-filter: blur(12px);
    -webkit-backdrop-filter: blur(12px);
    border: 1px solid var(--glass-border);
    border-radius: 18px; /* Softer corners */
    padding: 30px 35px; /* More padding */
    margin: 30px 0;
    box-shadow: 0 6px 25px var(--shadow-light);
    transition: all 0.4s ease-in-out;
}

/* --- Page Load Animation --- */
@keyframes fadeInUp {
    from { opacity: 0; transform: translateY(25px); }
    to { opacity: 1; transform: translateY(0); }
}

.research-areas,
.news-section,
.papers-section,
h1, h2, h3 { /* Apply animation */
    animation: fadeInUp 0.9s ease-out forwards;
    opacity: 0;
}

/* Stagger the animation */
h1 { animation-delay: 0.2s; }
h2 { animation-delay: 0.3s; }
.research-areas { animation-delay: 0.4s; }
.news-section { animation-delay: 0.6s; }
.papers-section { animation-delay: 0.8s; }
.research-item { animation-delay: calc(0.5s + var(--item-index, 0) * 0.1s); /* Stagger items */ }


/* --- Research Item Styling --- */
.research-item {
    background: rgba(255, 255, 255, 0.85); /* Slightly more opaque than section */
    padding: 25px;
    margin: 20px 0;
    border-radius: 12px;
    box-shadow: 0 3px 8px var(--shadow-light);
    display: flex;
    align-items: center; /* Center icon vertically */
    position: relative;
    overflow: hidden; /* Important for pseudo-elements */
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    border: 1px solid transparent; /* Placeholder for border */
}

/* Subtle Hover Effect */
.research-item:hover {
    transform: translateY(-5px) scale(1.01); /* Less dramatic scale */
    box-shadow: 0 8px 20px var(--shadow-medium);
    border-color: var(--glass-border); /* Show subtle border on hover */
}

/* Refined Gradient Border Animation (Subtler) */
.research-item::before {
    content: '';
    position: absolute;
    top: -1px; left: -1px; right: -1px; bottom: -1px; /* Adjust for border width */
    background: linear-gradient(120deg, var(--primary-color), var(--secondary-color), var(--accent-color), var(--primary-color));
    background-size: 300% 300%; /* Larger size for smoother animation */
    z-index: -1;
    border-radius: 13px; /* Slightly larger than item radius */
    opacity: 0; /* Hidden initially */
    transition: opacity 0.5s ease;
    animation: subtleBorderSpin 6s linear infinite paused; /* Paused initially */
}

.research-item:hover::before {
    opacity: 0.8; /* Reveal on hover */
    animation-play-state: running; /* Start animation on hover */
}

@keyframes subtleBorderSpin {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

/* Elegant Icon Styling */
.research-icon {
    font-size: 26px;
    margin-right: 20px;
    color: var(--primary-color); /* Use primary color */
    transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
    text-shadow: 0 0 8px rgba(124, 58, 237, 0.3); /* Softer shadow */
}

.research-item:hover .research-icon {
    transform: rotateY(360deg); /* Different rotation axis */
    color: var(--secondary-color); /* Change color on hover */
    text-shadow: 0 0 12px rgba(236, 72, 153, 0.5); /* Pinkish shadow */
}

/* Content Styling */
.research-content h3 {
    margin: 0 0 8px 0;
    font-size: 1.25em; /* Slightly larger */
    font-weight: 500; /* Medium weight */
    /* Elegant Gradient Text */
    background: linear-gradient(110deg, var(--primary-color), var(--secondary-color));
    background-size: 100% auto;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: background-position 0.6s ease;
}

.research-item:hover .research-content h3 {
    background-position: -100% center; /* Shift gradient on hover */
}

.research-content p {
    margin: 0;
    color: var(--text-light);
    line-height: 1.6;
    font-size: 0.95em;
}

/* Optional: Mouse Follow Aura (Subtle) */
.research-item::after {
    content: '';
    position: absolute;
    width: 200px; /* Smaller aura */
    height: 200px;
    top: var(--y, 50%); /* Use CSS variables for position */
    left: var(--x, 50%);
    transform: translate(-50%, -50%);
    background: radial-gradient(circle,
                               rgba(167, 139, 250, 0.15) 0%, /* Soft purple */
                               transparent 60%);
    opacity: 0;
    transition: opacity 0.5s ease;
    pointer-events: none;
    border-radius: 50%;
}

.research-item:hover::after {
    opacity: 1;
}

/* --- Header/Motto Styling (If you bring back Typed.js or similar) --- */
.motto-container { /* Example container */
    text-align: center;
    margin: 40px 0;
    padding: 20px;
    background: rgba(255, 255, 255, 0.1); /* Very subtle background */
    border-radius: 10px;
}

.typed-motto { /* Style for the typed text */
    font-style: normal; /* Less italic */
    font-size: 1.5em; /* Adjust as needed */
    font-weight: 400;
    min-height: 2.5em; /* Ensure space */
    background: linear-gradient(110deg, var(--text-dark), var(--primary-color));
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    font-family: 'Poppins', sans-serif; /* Consistent font */
    text-shadow: 1px 1px 3px rgba(0,0,0,0.05);
}

.typed-cursor {
    color: var(--primary-color); /* Match accent */
    font-weight: 300;
    animation: blink 0.7s infinite;
}

@keyframes blink {
    50% { opacity: 0; }
}

</style>

<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
document.addEventListener('DOMContentLoaded', () => {
    // Initialize Particles.js
    particlesJS('particles-js', {
        particles: {
            number: { value: 60, density: { enable: true, value_area: 800 } },
            color: { value: ["#7C3AED", "#EC4899", "#10B981"] }, // Array of colors
            shape: { type: "circle" }, // Simple shape
            opacity: { value: 0.4, random: true }, // Add randomness
            size: { value: 3, random: true },
            line_linked: { enable: true, distance: 130, color: "#A78BFA", opacity: 0.3, width: 1 }, // Softer links
            move: { enable: true, speed: 1.5, direction: "none", random: true, straight: false, out_mode: "out", bounce: false } // Slower, random movement
        },
        interactivity: {
            detect_on: "canvas",
            events: {
                onhover: { enable: true, mode: "bubble" }, // Bubble effect instead of repulse
                onclick: { enable: true, mode: "push" },
                resize: true
            },
             modes: { // Configure bubble effect
                bubble: {
                  distance: 150,
                  size: 5,
                  duration: 2,
                  opacity: 0.6,
                  speed: 3
                }
              }
        },
        retina_detect: true
    });

    // Add item index for staggered animation (if items are dynamically added, do this differently)
    const researchItems = document.querySelectorAll('.research-item');
    researchItems.forEach((item, index) => {
        item.style.setProperty('--item-index', index);
    });


    // Add mouse position tracking for the aura effect
    const itemsWithAura = document.querySelectorAll('.research-item');
    itemsWithAura.forEach(item => {
        item.addEventListener('mousemove', (e) => {
            const rect = item.getBoundingClientRect();
            const x = e.clientX - rect.left;
            const y = e.clientY - rect.top;
            item.style.setProperty('--x', `${x}px`);
            item.style.setProperty('--y', `${y}px`);
        });
    });
});
</script>


