# nwkus-landing-page — Nicole Kus Personal Professional Landing Page

## Overview
A static personal professional landing page for Nicole Kus, a Business Analytics and Information Systems (BAIS) student at the University of Iowa. Built for BAIS 3300 Digital Product Management. The site is a curated professional presence targeting recruiters and hiring managers in data analytics and business intelligence.

## Project Structure
```
/
├── index.html            # Single-page site (Hero, About, Skills, Projects, Contact)
├── css/
│   └── stylesheet.css    # All styles — no inline styles anywhere
├── js/
│   └── scripts.js        # Minimal JS: smooth scroll, mobile nav toggle
├── images/
│   └── headshot.jpg      # Professional headshot
├── PRD.md                # Product Requirements Document
├── STANDARDS.md          # Technical and design standards
```

## Tech Stack
- Vanilla HTML5, CSS3, JavaScript (no frameworks)
- Inter font via Google Fonts
- Python's built-in HTTP server for local dev

## Design System
- **Colors:** Navy nav (#1A2E3B), teal accent (#0D6E6E), light background (#F8F9FA), secondary bg (#E9ECEF), dark text (#212529)
- **Font:** Inter (Google Fonts), 16px/1.6
- **Max width:** 960px centered
- **Sections:** Hero, About, Skills, Projects, Contact

## Running the Project
**Workflow:** "Start application" runs `python3 -m http.server 5000`

## Standards
- WCAG 2.2 Level AA accessibility throughout
- Fully responsive from 320px wide
- No resume linked anywhere on the site
- All external links open in new tab with `rel="noopener noreferrer"`
- Semantic HTML5 throughout
