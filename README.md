# KLE Society's College of BCA, Gokak - Official Web Platform

A modern, high-contrast monochrome (Black & White) official web portal developed for **KLE Society's College of Bachelor of Computer Applications (BCA), Gokak**, affiliated with **Rani Channamma University, Belagavi (RCUB)**.

---

## ✦ Design System: Premium Monochrome (Black & White)
- **Primary Aesthetic**: Obsidian Black (`#08080a`), Stark Pure White (`#ffffff`), and subtle platinum slate accents.
- **Dynamic Dual Modes**:
  - **Obsidian Dark Mode** (Default): High-contrast dark luxury with glassmorphism, crisp white typography, and subtle ambient glows.
  - **Minimalist White Mode**: High-contrast pure white canvas with rich black typography and crisp borders.
  - Seamless toggle with persistent state via `localStorage`.
- **Typography**:
  - Headings: `Space Grotesk` (Tech forward & bold)
  - UI & Body: `Plus Jakarta Sans` (Clean, legible, modern)
  - Badges & Codes: `JetBrains Mono` (High-tech precision)

---

## ✦ Core Features & Modules

1. **Top Announcement & Quick Helpline Bar**:
   - Live updates for Admissions 2026–2030, direct contact helpline, student portal, and prospectus links.
2. **Sticky Glassmorphic Header & Mobile Drawer**:
   - Institutional KLE emblem crest, quick navigation, theme switcher, and instant admission CTA button.
3. **Hero Section with Animated Counter Metrics**:
   - Dynamic counter animations for Placement Assistance (100%), University Ranks (15+), MNC Recruiters (35+), and Alumni Network (1000+).
4. **Infinite Marquee Ticker**:
   - Smooth continuous scrolling marquee showcasing technology tracks and recruiter partners.
5. **Institutional Heritage & About KLE Society**:
   - Legacy of KLE Society (founded in 1916 by the *Saptarshis*), accreditation, and Gokak campus mission.
6. **NEP 2020 BCA Curriculum Blueprint**:
   - Interactive semester tabs (Sem I to Sem VI) with course codes, credits, and descriptions dynamically rendered from `data.js`.
   - Specialization tracks: AI & Data Science, Full-Stack Cloud Engineering (MERN), Cyber Defense, and AWS Cloud Architecture.
7. **Interactive Admission Eligibility & Scholarship Calculator**:
   - Calculates candidate eligibility under Rani Channamma University rules.
   - Computes KLE Saptarshi scholarship discounts based on 10+2 / PUC percentages and enables 1-click application autofill.
8. **Smart Campus & High-Tech Facilities**:
   - Showcase of Advanced Computing Centers (Core i7/i9 Linux/Windows labs), E-Library with DELNET/IEEE access, Seminar Hall, Hack Zone, Residential Hostels, and Sports Arena.
9. **Placements & Career Alliances**:
   - Placement packages (Highest: ₹9.6 LPA, Average: ₹4.8 LPA), recruiter partner directory (TCS, Infosys, Wipro, Cognizant, Accenture, Capgemini, etc.), and alumni testimonials.
10. **Faculty Mentorship Directory**:
    - Faculty profiles with qualifications (Ph.D., M.Tech, MCA), experience, and research domains.
11. **Live Notice Board with Category Filters**:
    - Filter announcements by Admissions, Exams, Events, or Placements with modal popups and PDF download simulations.
12. **Student Services & RCUB Result Verification Portal**:
    - Interactive simulation for students to look up semester marks cards by University Register Number (e.g. `U15EK23S001`, `U15EK23S002`, `U15EK24S015`) with internal/external marks breakdown, grade calculations, and printable statements.
13. **Multi-Step Online Admission Application Modal**:
    - 3-step structured form (Personal Details → Academic Records → Specialization Preferences) with real-time validation and reference ID generation.
14. **Contact & Campus Navigation**:
    - Gokak campus address, direct phone/email, stylized coordinate map card, and inquiry form with instant toast notification feedback.
15. **Frequently Asked Questions (FAQ)**:
    - Clean accordion answering common prospective student inquiries.

---

## ✦ File Structure
```
project/
├── index.html          # Semantic HTML5 page structure
├── css/
│   └── style.css       # High-contrast Black & White CSS styling & glassmorphism
├── js/
│   ├── data.js         # Structured data for curriculum, faculty, notices, results
│   └── main.js         # Interactive engine (themes, counters, tabs, calculator, modals)
└── README.md           # Documentation
```

---

## ✦ How to Run

### Method 1: Direct Browser Access
Double-click `index.html` or open `file:///c:/xampp/htdocs/helloworld/new/New%20folder/project/index.html` in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).

### Method 2: Via XAMPP Local Server
1. Start **Apache** from the XAMPP Control Panel.
2. Visit:
   ```
   http://localhost/helloworld/new/New%20folder/project/
   ```
