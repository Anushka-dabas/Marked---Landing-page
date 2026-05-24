# Marked — Landing Page

> Marketing and product showcase site for [Marked](https://marked-main.streamlit.app/), an AI-powered attendance system.

🔗 [Live Site](https://marked-landing-page-theta.vercel.app/)

---

## Overview

A fully responsive product landing page built from scratch — no templates, no UI libraries. Showcases Marked's features, user workflows, and tech stack, and directs teachers and students to the live app.

---

## Built With

| Layer | Technology |
|---|---|
| Backend / Routing | Flask + Gunicorn |
| Frontend | Semantic HTML5, CSS3, Vanilla JavaScript |
| Animations | IntersectionObserver API (scroll-driven, no libraries) |
| Typography | Playfair Display + Nunito (Google Fonts) |
| Deployment | Vercel Serverless |

---

## Features

- **Scroll animations** — feature cards and workflow steps animate in on scroll using a lightweight native `IntersectionObserver` implementation; no GSAP, no AOS
- **Fully responsive** — custom media queries at 1200px, 1024px, 768px, and 480px; tested across desktop, tablet, and mobile
- **CSS variable system** — all colors, spacing, and typography controlled via `:root` variables for consistency
- **SaaS-style design** — Playfair Display + Nunito pairing, clean card layouts, and a professional product aesthetic built without any CSS framework

---

## Project Structure

```
├── static/
│   ├── css/
│   │   └── style.css       # Layout, variables, responsive breakpoints
│   ├── js/
│   │   └── scripts.js      # Scroll animation via IntersectionObserver
│   └── img/
│       ├── logo.png
│       └── demo/           # App screenshots used in the walkthrough section
├── templates/
│   └── index.html          # Main page (Jinja2)
├── app.py                  # Flask router
├── requirements.txt
└── vercel.json             # Vercel deployment config
```

---

## Run Locally

```bash
git clone <repo-url>
cd <repo-folder>
pip install -r requirements.txt
python app.py
```

---

## Built by

**Anushka Dabas** — [GitHub](https://github.com/Anushka-dabas)
