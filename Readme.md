# MD Adnan Qamar | Portfolio Website

## README.md

```markdown
# MD Adnan Qamar — Data Analyst & SQL Developer Portfolio

A modern, responsive personal portfolio website built with 
vanilla HTML, CSS, and JavaScript. Features a dark glassmorphism 
design with animated gradients, interactive charts, and smooth 
scroll animations.

---

## 🌐 Live Demo
> Deploy on GitHub Pages, Netlify, or Vercel for free hosting.

---

## ✨ Features

- **Glassmorphism UI** — Frosted glass cards with gradient borders
- **Animated Hero** — Typewriter SQL code animation
- **Skills Radar Chart** — Interactive Chart.js visualization
- **Scroll Animations** — IntersectionObserver fade-in effects
- **Progress Bar** — Reading progress indicator
- **Contact Form** — Formspree-powered (no backend required)
- **Responsive Design** — Mobile-first with hamburger menu
- **Smart Header** — Auto-hides on scroll down, reappears on scroll up
- **Ambient Gradients** — Animated color glows (orange, cyan, green)

---

## 🛠️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| HTML5          | Structure & semantics            |
| CSS3           | Glassmorphism, animations        |
| Tailwind CSS   | Utility-first responsive layout  |
| JavaScript ES6 | Interactivity & DOM manipulation |
| Chart.js       | Skills radar visualization       |
| Formspree      | Contact form backend             |
| Google Fonts   | Inter typeface                   |

---

## 📁 Project Structure

```
portfolio/
│
├── index.html                    # Main portfolio file (single-page)
├── Md.Adnan_QAMAR_Resume.pdf     # Downloadable resume
└── README.md                     # This file
```

---

## 🚀 Getting Started

### Option 1: Open Locally
```bash
# Clone or download the repository
git clone https://github.com/yourusername/portfolio.git

# Open directly in browser — no build step needed!
open index.html
```

### Option 2: Deploy to GitHub Pages
```bash
# 1. Create a new GitHub repository
# 2. Push your files
git init
git add .
git commit -m "Initial portfolio deploy"
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main

# 3. Go to Settings → Pages → Deploy from main branch
```

### Option 3: Deploy to Netlify
```bash
# Drag and drop your project folder at netlify.com/drop
# Live in 30 seconds — no configuration needed
```

---

## ⚙️ Configuration & Customization

### 1. Update Personal Information
Edit `index.html` and replace:
```html
<!-- Name -->
<a href="#">MD Adnan Qamar</a>

<!-- Email -->
adnanqamar.dev@gmail.com

<!-- LinkedIn -->
https://linkedin.com/in/MdAdnanQamar

<!-- Telegram -->
Md_Adnan_Qamar
```

### 2. Update Formspree Endpoint
```html
<!-- Replace with your own Formspree form ID -->
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```
> Sign up free at [formspree.io](https://formspree.io)

### 3. Change Theme Colors
Edit CSS variables in `:root`:
```css
:root {
    --accent-primary: #F2AD62;   /* Orange — goldfish */
    --accent-secondary: #00BCD4; /* Cyan — chameleon  */
    --accent-tertiary: #8BC34A;  /* Green — growth    */
}
```

### 4. Update Skills Radar Chart
```javascript
data: {
    labels: ['SQL', 'Python', 'C++', 
             'Database Design', 
             'Query Optimization', 
             'Data Analysis'],
    datasets: [{
        data: [60, 90, 75, 85, 85, 70], // Adjust values (0-100)
    }]
}
```

### 5. Replace Resume File
```
Drop your PDF as: Md.Adnan_QAMAR_Resume.pdf
(or update the filename in the download link)
```

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full  |
| Firefox | ✅ Full  |
| Safari  | ✅ Full  |
| Edge    | ✅ Full  |
| IE 11   | ❌ None  |

> **Note:** Backdrop-filter (glassmorphism) requires 
> a modern browser. Graceful degradation included.

---

## 🎨 Design System

### Color Palette — Chameleon & Goldfish Theme

```
#F2AD62  →  Goldfish Orange  (primary actions, highlights)
#00BCD4  →  Chameleon Cyan   (experience, secondary info)
#8BC34A  →  Growth Green     (skills, achievements)
#0d1117  →  Deep Dark        (background base)
```

### Typography
```
Font: Inter (Google Fonts)
Weights: 300 (light), 400 (regular), 500 (medium), 600 (semibold)
```

### Spacing System
```
Follows Tailwind CSS default spacing scale (4px base unit)
Section padding: py-20 (80px vertical)
Container: max-w-6xl with px-6 horizontal padding
```

---

## 🔧 Known Limitations & Improvements

### Current Limitations
- Single HTML file (no component separation)
- Tailwind loaded via CDN (not optimized for production)
- No dark/light mode toggle
- Chart.js loaded twice (duplicate script tag)

### Suggested Improvements
```
□ Remove duplicate Chart.js CDN script tag
□ Add GitHub profile/repo links to projects
□ Implement dark/light theme toggle
□ Add loading skeleton screens
□ Migrate to Vite + Tailwind CLI for production build
□ Add meta Open Graph tags for social sharing
□ Compress and optimize background gradients for mobile
□ Add ARIA labels for better accessibility
```

---

## 📊 Performance Notes

- **No build process** — pure HTML/CSS/JS
- **CDN dependencies** — Chart.js, Tailwind, Google Fonts
- **Lazy animations** — IntersectionObserver (no scroll jank)
- **Throttled scroll** — requestAnimationFrame for header behavior

---

## 📄 License
MIT License — Free to use and modify for personal portfolios.

---

## 🤝 Contact
**MD Adnan Qamar**  
📧 adnanqamar.dev@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/MdAdnanQamar)  
💬 Telegram: @Md_Adnan_Qamar
```

---

## 📝 Site Description

### Short Description (for GitHub repo)
```
Personal portfolio of MD Adnan Qamar — Data Analyst & SQL Developer. 
Built with HTML, Tailwind CSS, and Chart.js. Features glassmorphism 
design, animated gradients, skills radar chart, and Formspree contact form.
```

### Meta Description (already in HTML)
```
Data analyst with proven SQL optimization skills. 
View projects showing 40% efficiency improvements.
```

### LinkedIn/Bio Description
```
🔗 Portfolio Website — mdadnanqamar.dev

Dark-themed personal portfolio showcasing data analysis projects, 
SQL optimization work, and technical skills. Built from scratch 
with glassmorphism UI, animated code blocks, and an interactive 
skills radar chart.

Key highlights:
• Library Management System (40% query efficiency gain)
• COVID-19 Spread Analysis with Tableau dashboards  
• Student Database Query Engine with PostgreSQL
• Vaccination Impact predictive modeling

Tech: HTML · CSS · JavaScript · Chart.js · Tailwind CSS
```

### Open Graph / Social Share Tags (add to `<head>`)
```html
<meta property="og:title" 
      content="MD Adnan Qamar | Data Analyst Portfolio" />
<meta property="og:description" 
      content="SQL optimization specialist with 40% efficiency 
               improvements. View my data analysis projects." />
<meta property="og:type" content="website" />
<meta property="og:url" 
      content="https://yourusername.github.io/portfolio" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" 
      content="MD Adnan Qamar | Data Analyst Portfolio" />
```
