# John Luke Rochester | Personal Portfolio Website

A professional, recruiter-targeted personal website and portfolio built for the **CSC 4125 Vibe Coding Assignment** at **Louisiana State University**.

- **LinkedIn Profile:** [https://www.linkedin.com/in/luke-rochester-369280389/](https://www.linkedin.com/in/luke-rochester-369280389/)
- **Live Public Website:** [https://johnrochester-git.github.io/JohnRochester.github.io/](https://johnrochester-git.github.io/JohnRochester.github.io/)
- **GitHub Repository:** [https://github.com/JohnRochester-git/JohnRochester.github.io](https://github.com/JohnRochester-git/JohnRochester.github.io)

---

## Project Overview

This website implements a **hybrid layout** designed to present professional credentials, competencies, and achievements to prospective recruiters, academic evaluators, and industry partners.

- **`index.html` (Single-Page Core Hub):** High-level overview presenting John Luke Rochester's profile as a Senior ISA / IT student at LSU, Business Analyst Intern at GoAuto Insurance, core competencies (Microsoft Excel, IT Business Analysis, Customer Service, Organization), 5+ year career timeline at GoAuto Insurance, and direct contact avenues.
- **`resume.html` (Comprehensive Curriculum Vitae):** A dedicated, printer-friendly CV page expanding on academic credentials at Louisiana State University (BS in IT, 2021–2026), St. Michael the Archangel High School (2017–2021), Microsoft Office Specialist: Excel Expert & Associate certifications (with verified Credly credentials), and detailed job achievements.
- **`project.html` (Signature Case Study):** In-depth exploration of the *GoAuto Business Performance Analytics & Operations Reporting System*, detailing operational challenges in insurance claim tracking, Excel reporting model development, corporate letter system management, and business impact.
- **`styles.css` (Design System):** A unified, accessible stylesheet adhering to a **Coffee & Beige** color palette (rich espresso typography, creamy beige surfaces, warm mocha accents) with responsive design for desktop, tablet, and mobile devices.

---

## Vibe Coding Reflection (CSC 4125 Rubric Requirement)

> **Reflection on Pairing with Antigravity AI Agent:**
> 
> During the initial architectural design of the website, I noticed that the agent created a shared stylesheet (`styles.css`) and linked it inside the `<head>` of all three pages (`index.html`, `resume.html`, and `project.html`) rather than loading it once in the root page. I asked the agent why the CSS file had to be linked across every page individually if they were all hosted inside the same project repository. The agent explained that web browsers treat each HTML file as an independent document execution context; when navigating to a new URL, the browser constructs a fresh Document Object Model (DOM) from scratch and will only render styles referenced in that specific page's markup. This helped me understand how client-side web document lifecycles work and why centralizing design tokens in shared CSS custom properties allows multiple independent pages to maintain visual consistency without code duplication.
