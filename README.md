# Dhanush B M — Portfolio Website

A premium, single-page personal portfolio built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies (besides Google Fonts).

🔗 **Live Demo:** _add your deployed link here (e.g. GitHub Pages / Vercel / Netlify)_

---

## ✨ Overview

This is the personal portfolio of **Dhanush B M**, a Software Engineer based in Bengaluru, India. It showcases my background, technical skills, work experience, projects, and education, along with a working contact section.

## 🎨 Design

- Editorial, luxury-inspired aesthetic with **Cormorant Garamond** (display) + **Manrope** (body) typography
- Deep navy & gold color palette with an animated gradient mesh background
- Light / Dark mode toggle
- Smooth scroll-triggered reveal animations
- Sticky, blurred navigation bar with active-section highlighting
- Fully responsive across mobile, tablet, and desktop

## 🧩 Sections

| Section | Description |
|---|---|
| **Hero** | Introduction, role, key stats, and profile summary card |
| **About** | Bio and quick facts (location, education, stack, etc.) |
| **Skills** | Categorized technical skills — Frontend, Backend, Databases, QA/Testing, Tools, Soft Skills |
| **Experience** | Work history with role, company, duration, and achievements |
| **Projects** | Featured GitHub repositories with direct links |
| **Education** | Academic background and qualifications |
| **Contact** | Direct contact links + a message form that opens a pre-filled email via `mailto:` |

## 🛠 Tech Stack

- **HTML5** — semantic single-file structure
- **CSS3** — custom properties (CSS variables), Grid & Flexbox, animations
- **Vanilla JavaScript** — no frameworks or libraries
- **IndexedDB** — lightweight browser-side storage that silently logs submitted contact messages locally (for the site owner's reference only; not displayed publicly)
- **Google Fonts** — only external dependency

## 📂 Project Structure

```
.
├── index.html      # Single-file site (HTML + CSS + JS inline)
└── README.md       # This file
```

## 🚀 Getting Started

No build steps or installations required.

1. Clone this repository
   ```bash
   git clone https://github.com/Dhanushmysr/portfolio.git
   cd portfolio
   ```
2. Open `index.html` directly in any modern browser, **or**
3. Serve it locally:
   ```bash
   python -m http.server 8000
   ```
   then visit `http://localhost:8000`

## 🌐 Deployment

This site is a single static HTML file, so it can be deployed anywhere instantly:

- **GitHub Pages:** Settings → Pages → Deploy from branch (`main` / root)
- **Vercel:** Import repo → deploy (zero config)
- **Netlify:** Drag and drop `index.html` into Netlify Drop

## 📬 Contact Form

The contact form does not require any backend or third-party service. On submit, it:
1. Validates the name, email, and message fields
2. Opens the visitor's default email client with the message pre-filled, addressed to `dhanumysr14@gmail.com`
3. Saves a local copy of the message in the browser's IndexedDB for reference

## 📇 Connect with Me

- **Email:** dhanumysr14@gmail.com
- **LinkedIn:** [linkedin.com/in/dhanush-bm-797b22262](https://linkedin.com/in/dhanush-bm-797b22262)
- **GitHub:** [github.com/Dhanushmysr](https://github.com/Dhanushmysr)

---

⭐ If you found this portfolio template helpful, feel free to star the repo!
