# CyberNews — Threat Intelligence Portal

A responsive, dark cyberpunk-themed threat intelligence portal built for cybersecurity students and professionals.

Features
- Home page with animated cyber background and breaking news ticker
- Threat Feed with filters and timeline
- CVE search with CVSS badges
- Reports, About, Contact pages
- Dark mode toggle, glassmorphism UI, neon accents

Tech
- HTML, CSS, JavaScript (vanilla)
- Fonts: Orbitron & Share Tech Mono
- Icons: Font Awesome

Getting started
1. Clone or copy the project folder.
2. Open `index.html` in a browser (development) or serve via a static server for proper file loading.

APIs & Configuration
- NewsAPI: To fetch real-time news, obtain a free API key from https://newsapi.org and set it in `assets/js/news.js` as `NEWSAPI_KEY`.
- NVD API (optional): For CVE searches, you can set `NVD_API_KEY` in `assets/js/cve.js`. The NVD API supports unauthenticated queries but has rate limits.
- Contact form: The contact form uses Formspree placeholder. Replace the `action` attribute in `contact.html` with your form endpoint.

Files
- `index.html` — Home
- `threat-feed.html` — Threat feed and timeline
- `cve.html` — CVE search
- `reports.html`, `about.html`, `contact.html`
- `assets/css/styles.css` — Main styles
- `assets/js/main.js` — UI helpers and theme toggle
- `assets/js/news.js` — News fetching & feed population
- `assets/js/cve.js` — CVE search
- `assets/data/sample_news.json` — fallback sample data

Customization & Deployment
- Replace sample data or wire up backend (Firebase/Flask) for saved reports and contact handling.
- To deploy: host as static site (GitHub Pages, Netlify, Vercel) or on any static CDN.

Notes & Security
- This project is intended for educational/portfolio use. If you plan to use in production, secure API keys on the server-side and avoid exposing keys in front-end code.

License
- Use in your portfolio and adapt as needed. No warranty.
