# Kazadi Mukendi — Bootstrap Portfolio

A fully responsive personal portfolio built with Bootstrap 5, submitted as the **"Clone Your Future"** assignment for the Zaio Bootstrap course.

---

## Live Demo

> Replace this line with your Netlify or GitHub Pages URL once deployed.

---

## Sections Implemented

### 1. Hero Section
Full-bleed CSS gradient background with a dark overlay for text contrast. Displays the headline **"I am Kazadi Mukendi"** and the sub-headline role. Includes a sticky, semi-transparent navbar with logo on the left and navigation links on the right — the active link has an underline indicator. A skip-to-content link is included for keyboard accessibility. Fully responsive from 360px to 4K.

### 2. About Me Card
Two-column Bootstrap card with a subtle shadow and rounded corners. The left column holds a profile photo, contact details (Name, Profile, Phone, Email), and a grid of skill badges. The right column features a pale highlight section label, a short bio (under 160 words), and a row of stat cards highlighting projects, certificates, technologies, and education background.

### 3. Projects Grid
Six project cards in a responsive 3-column (lg) → 2-column (md) → 1-column (sm) grid. Each card has a banner image, title, subtitle, and two buttons — a primary "View Website" button and an outline code icon button linking to the GitHub repo. All images use inline SVG placeholders and include descriptive `alt` text.

**Projects included:**
| Project | Live Link | Repo |
|---|---|---|
| Tesla Landing Page | [kazadicars.netlify.app](https://kazadicars.netlify.app/) | [GitHub](https://github.com/KMukendi10/TeslaLandingPage.git) |
| Netflix Landing Page | [kazadimoviesite.netlify.app](https://kazadimoviesite.netlify.app/) | [GitHub](https://github.com/KMukendi10/netflixlandingpage.git) |
| YouTube Homepage | [kazadiyoutubeclone.netlify.app](https://kazadiyoutubeclone.netlify.app/) | [GitHub](https://github.com/KMukendi10/ZaioYouTubeLandingPage.git) |
| To-Do App | [kmukendi10.github.io/To-Do-App](https://kmukendi10.github.io/To-Do-App/) | [GitHub](https://github.com/KMukendi10/To-Do-App.git) |
| Portfolio Website | [github.com/KMukendi10](https://github.com/KMukendi10) | [GitHub](https://github.com/KMukendi10) |
| Responsive Design Study | [github.com/KMukendi10](https://github.com/KMukendi10) | [GitHub](https://github.com/KMukendi10) |

### 4. Contact Section
Centered "Let's connect" heading with a pale highlight label. A row of six social icon links (Instagram, GitHub, LinkedIn, Facebook, Twitter/X, WhatsApp) using Bootstrap Icons. Below that, an accessible contact form with labelled fields for Email Address, Name, Subject, and Message, plus a Submit button. HTML-only validation (`required`, `type="email"`). No backend.

### 5. Footer
Dark footer bar with centered text: *Developed by Kazadi Mukendi using Bootstrap, for portfolio purposes.* High contrast white-on-dark text with consistent padding.

---

## Bonus Features

### Auto Dark Mode
Implemented using `prefers-color-scheme: dark` and CSS custom properties (`--accent`, `--bg`, `--surface`, etc.). When the user's OS is set to dark mode, the entire portfolio automatically switches to a dark violet-and-near-black palette — no JavaScript required.

### Print-Ready Résumé View
A `@media print` stylesheet hides the navbar, hero, projects, contact, and footer, leaving only the About Me card formatted cleanly on an A4 page. Skill badges and section labels are adjusted for print contrast. External link URLs are appended inline using CSS `content: attr(href)`.

---

## Tech Stack

- **Bootstrap 5.3** — CDN, no JS bundle used
- **Bootstrap Icons 1.11** — CDN
- **Vanilla CSS** — `styles.css` for all custom design tokens, layout overrides, and bonus features
- **No JavaScript** — zero JS, including no Bootstrap JS

---

## File Structure

```
portfolio/
├── index.html      # All sections: Hero, About, Projects, Contact, Footer
├── style.css       # Custom styles, CSS variables, dark mode, print styles
└── README.md       # This file
```

---

## Image Credits

All card images are inline SVG placeholders generated in CSS/HTML — no external image requests are made. To swap in your own photos, replace the `src="data:image/svg+xml,..."` values with your image file paths and update the `alt` text accordingly.

Profile photo: replace the SVG placeholder with `./Assets/Kazadi Profile Pic.png` (your existing asset).

---

## Author
Kazadi Mukendi