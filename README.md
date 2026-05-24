# Marked: AI-Powered Attendance Platform (Landing Page Frontend)

This repository hosts the public landing page and web frontend for **Marked**—an advanced multi-modal attendance system built with computer vision and voice biometrics. This website acts as the primary marketing layer, detailing the platform's features, tech stack, and user workflows while directing educators and students to the live application layer.

🔗 **Live Production Link:** [https://marked-landing-page-theta.vercel.app/](https://marked-landing-page-theta.vercel.app/)

---

## 🎨 Frontend & UI Architecture

* **Modern Layout System:** Crafted using custom CSS3 variables, fluid spacing rules, and sleek typography pairs (*Playfair Display* and *Nunito*) to establish a professional, SaaS-style product aesthetic.
* **Scroll-Driven Animation Engine:** Leverages a native, high-performance `IntersectionObserver` script engine in Vanilla JavaScript to progressively animate feature cards and workflow phases into view.
* **Fully Responsive Design:** Features a custom CSS media-query framework tailored across 1200px, 1024px, 768px, and 480px thresholds to ensure seamless rendering on screens of all sizes.
* **Production Deployment:** Configured for serverless hosting on Vercel with structured application routing for fast loading times and global accessibility.

---

## 🛠️ Core Web Stack

* **Web Framework:** Flask (Python micro-framework utilized for simple, efficient web routing)
* **Frontend Modules:** Semantic HTML5, Custom CSS3, and Vanilla ECMAScript (JavaScript)
* **Production Server:** Gunicorn (WSGI server wrapper for secure deployment handling)
* **Deployment Platform:** Vercel Serverless Edge Cloud

---

## 📁 Repository Structural Blueprint

```text
├── static/                     # Web assets and static distribution layers
│   ├── css/
│   │   └── style.css           # Global layout parameters, UI variables, and responsive design
│   ├── img/
│   │   ├── logo.png            # Main platform brand graphic
│   │   └── demo/               # High-resolution application preview screenshots
│   │       ├── marked-landing.png
│   │       ├── marked-student-flow-1-login.png
│   │       ├── marked-student-flow-2-enroll.png
│   │       ├── marked-student-flow-3-dashboard.png
│   │       ├── marked-teacher-flow-1-login.png
│   │       ├── marked-teacher-flow-2-dashboard.png
│   │       ├── marked-teacher-flow-3-create-course.png
│   │       ├── marked-teacher-flow-5-see-stored-records.png
│   │       ├── marked-teacher-flow-5.1-voice-attendance.png
│   │       └── marked-teacher-flow-5.2-photo-attendance.png
│   └── js/
│       └── scripts.js          # Viewport interaction and viewport intersection script
├── templates/
│   └── index.html              # Core HTML structure compiled via Jinja2 templates
├── app.py                      # Flask backend router script
├── requirements.txt            # Operational python dependencies list
└── vercel.json                 # Vercel deployment configuration manifest
