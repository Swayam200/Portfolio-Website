---
layout: default
title: Swayam Prakash Panda - Portfolio
---

<div class="glass-card" data-aos="fade-up">

# 🚀 Swayam Prakash Panda
{: .glow}

**Data Analyst | AI/ML Enthusiast | B.Tech CSE (AIML) Student**

Welcome to my portfolio! I'm passionate about leveraging data to drive insights and building intelligent solutions.

</div>

<div class="glass-card skills-section" data-aos="fade-up" data-aos-delay="200">

## 🛠️ Skills & Expertise

### Programming Languages
<div class="skill-bar">
    <div class="skill-progress" data-width="90">Python - 90%</div>
</div>
<div class="skill-bar">
    <div class="skill-progress" data-width="75">C++ - 75%</div>
</div>
<div class="skill-bar">
    <div class="skill-progress" data-width="80">SQL - 80%</div>
</div>

### Technologies & Tools
- **Machine Learning**: Scikit-learn, TensorFlow, PyTorch
- **Data Analysis**: Pandas, NumPy, Matplotlib, Seaborn
- **Databases**: MySQL, PostgreSQL, MongoDB
- **Visualization**: Tableau, Power BI, Plotly
- **Version Control**: Git, GitHub

</div>

<div class="glass-card" data-aos="fade-up" data-aos-delay="400">

## 🎓 Education
**B.Tech in Computer Science & Engineering (AI/ML)**  
*Current Student*

</div>

<div class="glass-card" data-aos="fade-up" data-aos-delay="600">

## 📊 Skills Visualization
<div class="chart-container">
    <canvas id="skillChart" width="400" height="200"></canvas>
</div>

</div>

<div class="text-center" data-aos="zoom-in">
    <a href="mailto:swayam.panda200@gmail.com" class="btn-animated">
        <i class="fas fa-envelope"></i> Get In Touch
    </a>
    <a href="https://github.com/swayam200" class="btn-animated">
        <i class="fab fa-github"></i> View My Work
    </a>
</div>

<div class="glass-card" data-aos="fade-up">
    <h3>📧 Contact Me</h3>
    <form id="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
        <div class="form-group">
            <input type="text" name="name" placeholder="Your Name" required>
        </div>
        <div class="form-group">
            <input type="email" name="email" placeholder="Your Email" required>
        </div>
        <div class="form-group">
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        </div>
        <button type="submit" class="btn-animated">Send Message</button>
    </form>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
document.addEventListener('DOMContentLoaded', function() {
    const ctx = document.getElementById('skillChart');
    if (ctx) {
        const skillChart = new Chart(ctx.getContext('2d'), {
            type: 'radar',
            data: {
                labels: ['Python', 'Machine Learning', 'Data Analysis', 'SQL', 'Tableau', 'Git'],
                datasets: [{
                    label: 'Skill Level',
                    data: [90, 85, 90, 80, 75, 85],
                    backgroundColor: 'rgba(54, 188, 247, 0.2)',
                    borderColor: '#36BCF7',
                    borderWidth: 2,
                    pointBackgroundColor: '#36BCF7',
                    pointBorderColor: '#fff',
                    pointHoverBackgroundColor: '#fff',
                    pointHoverBorderColor: '#36BCF7'
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    r: {
                        beginAtZero: true,
                        max: 100,
                        ticks: {
                            color: 'rgba(255, 255, 255, 0.8)'
                        },
                        grid: {
                            color: 'rgba(255, 255, 255, 0.2)'
                        },
                        angleLines: {
                            color: 'rgba(255, 255, 255, 0.2)'
                        }
                    }
                },
                plugins: {
                    legend: {
                        labels: {
                            color: 'rgba(255, 255, 255, 0.8)'
                        }
                    }
                }
            }
        });
    }
});
</script>