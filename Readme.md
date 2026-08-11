# 🚀 Adnan Qamar — AI Engineer Portfolio

A single-file, dependency-free portfolio website for **MD Adnan Qamar** — AI Engineer / Generative AI Engineer / Agentic AI Engineer.

Built as one self-contained `index.html` (embedded CSS + vanilla JS). No frameworks, no build step, no external libraries — it works offline and can be deployed anywhere.

---

## ✨ Features

- **Dark, glassmorphic AI-engineer aesthetic** — animated gradient blobs, subtle grid overlay, terminal-style hero widget
- **Typed hero** cycling through roles (AI Engineer → Generative AI → Agentic AI)
- **Animated stat counters** — 300K+ records processed, 95% JSON success, 15 API endpoints, 16 repos
- **8 numbered sections** with smooth-scroll navigation, active-link highlighting, and scroll-reveal animations
- **Working contact form** — validates input and opens the visitor's email app pre-filled (no backend required)
- **Download Resume** buttons linked to the hosted PDF (hero + contact card)
- **Scroll progress bar** + back-to-top button
- **Fully responsive** — hamburger menu on mobile
- **`prefers-reduced-motion` support** for accessibility
- Zero external requests — fonts, icons, and styles are all inline

## 🗂 Section Structure

| # | Section | Contents |
|---|---------|----------|
| 01 | About | Professional summary + highlight cards |
| 02 | Experience | IBM SkillsBuild & CodSoft internships (timeline) |
| 03 | Education | B.Tech CSE @ RTU, CGPA 7.64, Class of 2026 |
| 04 | Skills | Languages, AI/LLMs, Backend, Frontend, Databases, Tools |
| 05 | Projects | ArziWala, UsTogether, AURA & CO + outcome metrics |
| 06 | Achievements | GitHub badges: Pull Shark, Quickdraw, YOLO |
| 07 | GitHub | Live links to all public repositories |
| 08 | Contact | Contact links + message form |

## 🛠 Tech Stack

- **Markup/Styles:** HTML5, CSS3 (custom properties, CSS grid, flexbox)
- **Scripting:** Vanilla JavaScript (IntersectionObserver, typed effect, count-up)
- **No build tools, no CDNs, no dependencies**

## 🔧 Customization

All content lives in `index.html` — no config file needed.

**Contact details** — search and replace:

| Search | Replace with |
|--------|-------------|
| `adnanqamar.dev@gmail.com` | your email |
| `+91 77638 67498` | your phone |
| `adnanqamardev-source` | your GitHub username |

**Resume link** — the Download Resume buttons point to:

```
https://raw.githubusercontent.com/adnanqamardev-source/Portfolio/main/Md.Adnan_QAMAR_Resume.pdf
```

If your resume lives elsewhere (Drive, repo, S3), update the `href` in these places:
1. Hero actions (`#home` section)
2. Contact card (`#contact` section)

**Projects** — edit the cards inside the `#projects` section (icon, title, description, metric chips, tags, live/GitHub links). Add or remove repository cards in the `#repos` section.

**Colors** — the palette is defined once in the `:root` block:

```css
--violet: #8b5cf6;
--cyan:   #22d3ee;
--grad:   linear-gradient(90deg, #8b5cf6, #22d3ee);
```

**Spacing** — a consistent 8px rhythm is used everywhere via `--s1` … `--s7` tokens (`8px → 96px`).

## 🚀 Deployment

The file is fully static — pick any host:

**GitHub Pages**
1. Push `index.html` (and `README.md`) to your repo
2. Go to **Settings → Pages**
3. Deploy from branch `main` / root folder
4. Live at `https://<username>.github.io/<repo>`

**Vercel**
1. `vercel` in the project folder, or import the repo at vercel.com
2. Framework preset: *Other* — zero config needed

**Netlify / Cloudflare Pages**
Drag-and-drop `index.html`, or connect the repo. Done.

> 💡 Note: the resume download button relies on the browser's native download behavior — works on any real deployed host (the embedded sandbox preview may block it).

## 🗃 Project Structure

```
portfolio/
├── index.html   # the entire site (styles + markup + JS)
└── README.md
```

## 📝 License

Portfolio content © 2026 MD Adnan Qamar. The code is free to reuse for your own portfolio — just swap in your own details and resume.

---

<div align="center">
  Made with ❤️ and Python · React · Gemini vibes 🚀
</div>
