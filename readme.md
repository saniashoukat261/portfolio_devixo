# Personal Portfolio Website — Sania Shoukat

A fully responsive personal portfolio website built as **Task 01** for the DEVIXO Solutions Web Development Internship.

**Live site:** (https://portfolio-saniashoukat.vercel.app/)

---

## About This Project

This portfolio showcases my background, skills, education, and projects as a Computer Science student and aspiring web developer. It was built from scratch using only **HTML5** and **CSS3** — no frameworks, no templates, and no external UI libraries — as required by the internship task.

## Tech Stack

- **HTML5** — semantic page structure
- **CSS3** — layout (Flexbox & Grid), responsive design, and animations

This site uses **no JavaScript**. The mobile menu, smooth scrolling and scroll-in card animations are all done with CSS, and the contact form uses a standard `mailto:` action.

No Bootstrap, Tailwind, or any front-end framework was used. No pre-built template was used — the layout, styling, and content structure are original.

## Folder Structure

```
devixo-portfolio/
├── index.html          # Main page (all sections)
├── style.css            # All styling
├── images/
│   ├── profile.jpg          # Hero profile photo
│   ├── virexo-innovations.png
│   ├── inkline-resume-builder.png
│   ├── ironvault-gym.png
│   ├── careerly-job-portal.png
│   ├── car.png              # Velora Drive project
│   └── artisan-coffee.png   # CopyCoffee project
├── documents/
│   ├── sqrock-certificate.jpg
│   ├── sqrock-recommendation-letter.pdf
│   ├── virexo-certificate.jpg
│   └── virexo-recommendation-letter.pdf
└── README.md
```

## Sections

| Section | Description |
|---|---|
| **Home** | Name, tagline, short intro, and call-to-action buttons |
| **About** | Academic background and career interests |
| **Skills** | Skill cards with progress bars: Front-End (HTML5, CSS3, JavaScript, Bootstrap), Back-End & Databases (PHP, Node.js, Express.js, MongoDB) and Tools & CMS (Git, GitHub, WordPress), plus chips for Python, C++, C, C#, Dart and SQL |
| **Education** | Timeline of academic history (Matriculation → Intermediate → BS Computer Science) |
| **Experience** | Internship timeline: CodeAlpha (Full Stack), SQRock IT Solutions (Frontend) and Virexo Innovations (Web Development), with role, company and dates; certificates and recommendation letters open from the cards |
| **Projects** | Six real projects, each with a description, tags, and a live link |
| **Contact** | Contact form (opens the visitor's email app via `mailto:`) plus email, location, and social links |
| **Footer** | Four-column footer: short bio with social links, quick links, services, contact details, and a copyright bar |

## Design Approach

- A single consistent color palette (dark charcoal + gold accent) used throughout, for a clean, professional look.
- One serif font for headings and one sans-serif font for body text, kept consistent across all sections.
- Responsive layout using CSS Grid and Flexbox, with breakpoints at 900px, 700px and 560px for tablet and mobile.
- A light Experience section with a CSS-only vertical timeline showing the internship history.
- A CSS-only mobile navigation menu (checkbox toggle).
- Simple, restrained hover effects on buttons, cards, and links — kept minimal and purposeful rather than decorative.
- Cards fade in as they scroll into view using CSS scroll-driven animations (`animation-timeline: view()`); browsers without support simply show the cards normally.
- Smooth scrolling between sections via `scroll-behavior: smooth`.

## Projects Featured

1. **Virexo Innovations** — Digital engineering studio website
2. **Inkline** — AI resume builder
3. **IronVault** — Gym management system
4. **Careerly** — Job portal
5. **Velora Drive** — Car rental platform
6. **CopyCoffee** — Full-stack coffee shop website with database-backed ordering and rewards

## Running Locally

This is a static site with no build step or dependencies.

1. Download or clone this folder.
2. Open `index.html` directly in any browser, **or** serve it locally:
   ```
   npx serve .
   ```
3. Visit the printed local URL in your browser.

## Responsiveness

Tested at common breakpoints:
- Desktop (1280px+)
- Tablet (~768–900px)
- Mobile (~375–480px)

No horizontal scrolling occurs at any of the above widths.

## Author

**Sania Shoukat**
BS Computer Science, University of Agriculture Faisalabad (Sub-Campus Burewala)
Email: saniashoukat565@gmail.com
GitHub: [github.com/saniashoukat261](https://github.com/saniashoukat261)
LinkedIn: [linkedin.com/in/sania-shoukat-2aa78b3a6](https://www.linkedin.com/in/sania-shoukat-2aa78b3a6)

---

*Built for the DEVIXO Solutions Web Development Internship — Task 01.*
