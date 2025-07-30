---
layout: default
title: Swayam Prakash Panda - Portfolio
---

<div class="glass-card" data-aos="fade-up">

# 🚀 Swayam Prakash Panda
{: .glow}

<!-- Your existing content with added classes -->

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

</div>

<!-- Add animated buttons -->
<div class="text-center" data-aos="zoom-in">
    <a href="mailto:swayam.panda200@gmail.com" class="btn-animated">
        <i class="fas fa-envelope"></i> Get In Touch
    </a>
    <a href="https://github.com/swayam200" class="btn-animated">
        <i class="fab fa-github"></i> View My Work
    </a>
</div>

<div class="glass-card">
    <canvas id="skillChart" width="400" height="200"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('skillChart').getContext('2d');
const skillChart = new Chart(ctx, {
    type: 'radar',
    data: {
        labels: ['Python', 'Machine Learning', 'Data Analysis', 'SQL', 'Tableau', 'Git'],
        datasets: [{
            label: 'Skill Level',
            data: [90, 85, 90, 80, 75, 85],
            backgroundColor: 'rgba(54, 188, 247, 0.2)',
            borderColor: '#36BCF7',
            borderWidth: 2
        }]
    },
    options: {
        responsive: true,
        maintainAspectRatio: false
    }
});
</script>

<!-- Add this to your markdown where you want interactive code -->
<iframe height="400" style="width: 100%;" scrolling="no" title="Your Project Demo" 
        src="https://codepen.io/your-username/embed/your-pen-id?default-tab=html%2Cresult" 
        frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
</iframe>

<div class="glass-card" data-aos="fade-up">
    <h3>📧 Get In Touch</h3>
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