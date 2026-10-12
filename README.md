# NovaWeb Studio — Freelance Web Development Agency

A modern, responsive, and professional static frontend website for a student-led freelance web development team offering website development services to local businesses.

> **Course:** Web Technologies  
> **Project Type:** University Semester Project (Static Frontend Only)  
> **Academic Focus:** Semantic HTML5, CSS3 Styling & Architecture, Bootstrap 5 Responsive Grid & UI Components  

---

## 1. Project Overview

NovaWeb Studio represents a small, student-led freelance web development agency created to bridge local businesses (such as restaurants, retail shops, real estate agencies, and individual professionals) with a modern digital presence.

The website serves as a public-facing showcase highlighting:
- The agency's core web development services
- Concept project demonstrations and previous work
- Technical proficiencies and modern web tools
- Team member roles and core values
- A clear four-step working process
- Realistic value propositions
- A frontend-only client contact and inquiry interface

---

## 2. Technology Stack

This project strictly adheres to the requested frontend requirements:

| Technology | Purpose | Usage / Delivery |
| :--- | :--- | :--- |
| **HTML5** | Semantic structure, content hierarchy, and accessibility | Native semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) |
| **CSS3** | Custom design system, color tokens, layout aesthetics, and hover transitions | `css/style.css` |
| **Bootstrap 5 (v5.3.3)** | Responsive 12-column grid system, navbar, cards, and utility spacing | Delivered via high-performance CDN |
| **Bootstrap Icons (v1.11.3)** | Interface iconography | Delivered via CDN |
| **Google Fonts** | Professional modern typography (*Plus Jakarta Sans*) | Delivered via CDN |
| **Minimal JS** | Standard Bootstrap functionality only (mobile navbar toggler) | Official Bootstrap bundle via CDN |

*Strictly Excluded: No React, Next.js, Vue, Angular, Tailwind CSS, TypeScript, Node.js, Express, Python, PHP, databases, or build tools.*

---

## 3. Folder and File Structure

```text
freelance-agency-website/
│
├── index.html              # Main HTML document containing all 10 required sections
├── css/
│   └── style.css           # Custom CSS: Design system, color tokens, cards, and transitions
├── images/
│   └── README.txt          # Asset folder placeholder for future client/team images
└── README.md               # Project documentation and presentation guide
```

---

## 4. How to Run the Website

Because this is a pure static frontend website using CDN-hosted libraries, **no installations, compilers, or server setups are required**:

1. Navigate to the project folder:
   ```text
   d:\Subjects\Web Technologies\New Project
   ```
2. Double-click **`index.html`** or right-click and select **Open with** -> **Google Chrome** (or Edge, Firefox, Safari).
3. The website will immediately load and display with full styling and interactivity.

---

## 5. Website Architecture & Sections

The single-page website includes 10 clearly organized sections accessible through smooth-scrolling anchor navigation:

1. **Navigation Bar (`<header>` / `<nav>`):** Fixed-top navbar with agency branding, smooth links, "Let's Talk" CTA, and responsive mobile collapse.
2. **Hero Section (`#home`):** Clear value proposition, twin action buttons, trust statement (*"Creative Solutions. Clean Code. Real Results."*), and a CSS-styled live browser mockup preview.
3. **Services (`#services`):** 4 core offerings (Business Websites, Restaurant & Small Business, Personal Portfolios, Website Redesigns).
4. **Portfolio (`#portfolio`):** 4 project cards with custom theme previews (Royal Taste Restaurant, Prime Estates, Personal Portfolio, Business Website Concept) with tech stack badges and a "Have a Project in Mind?" banner.
5. **Skills & Technologies (`#skills`):** Tech badges for HTML5, CSS3, Bootstrap 5, JavaScript, Responsive Web Design, and Git/GitHub.
6. **About Our Team (`#about`):** Student-led team profile cards (Frontend Developer, UI/UX Designer, Web Developer) with roles and core philosophy.
7. **Our Working Process (`#process`):** 4-step workflow (Understand Needs, Plan & Design, Develop, Review & Deliver).
8. **Why Choose Us (`#why-us`):** 4 realistic feature cards highlighting responsive design, clear communication, practical solutions, and attention to detail.
9. **Testimonials (`#testimonials`):** Demonstration cards clearly designated as placeholders for future client feedback.
10. **Contact & Inquiry (`#contact`):** Agency contact information placeholders plus a complete Bootstrap inquiry form with HTML5 validation attributes and academic presentation commentary.
11. **Footer (`<footer>`):** Dark navy footer with branding, quick links, service anchors, social links, and university course attribution.

---

## 6. University Presentation & Viva Talking Points

When presenting this project to your teacher or evaluator, highlight the following:

- **Semantic HTML5:** Every section uses proper semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<label>`) ensuring optimal search engine readability and W3C compliance.
- **CSS Architecture:** Uses CSS custom variables (`--color-primary`, `--color-navy-dark`, `--shadow-md`, etc.) defined in `:root` for a consistent design system.
- **Bootstrap 5 Grid & Utilities:** Demonstrates mastery of container layouts, responsive breakpoints (`col-md-6`, `col-lg-3`, `col-lg-4`), flex utilities, and spacing tokens (`g-4`, `p-3`, `mb-5`).
- **No Heavy Build Dependencies:** Built without complex bundlers, making the project lightweight, portable, and easy to explain.
- **Scope Compliance:** Explicitly kept frontend-only as required, avoiding unasked features while implementing clear code comments explaining how a backend would integrate into the contact form in a production environment.
