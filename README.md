# NATAN MESERET — AI Portfolio Website

**Author:** Natan Meseret  
**Student ID:** UGR/31027/15  
**GitHub:** [github.com/nnnnnate-bit](https://github.com/nnnnnate-bit)

---

## Overview

A personal AI-themed portfolio website built with pure HTML, CSS, and JavaScript. The site showcases Natan Meseret's skills, projects, and background in machine learning, artificial intelligence, IoT systems, and modern web development. It features a futuristic dark design with animated backgrounds, glassmorphism UI elements, and smooth scroll-reveal effects.

---

## Features

- **Animated background** — moving grid with radial gradient glows (cyan & magenta)
- **Typing effect** — auto-types the role/tagline on page load
- **Scroll reveal** — sections fade and slide in as the user scrolls
- **Glassmorphism UI** — frosted-glass cards and navbar using `backdrop-filter`
- **Responsive design** — adapts to mobile, tablet, and desktop screens
- **Contact form** — client-side form with a submission confirmation alert
- **Gradient branding** — cyan-to-magenta gradient used consistently throughout

---

## File Structure

```
portfolio/
└── index.html      # Single-file app — all HTML, CSS, and JS in one file
```

---

## Sections

| Section | Description |
|---------|-------------|
| **Home / Hero** | Name, animated typing tagline, and CTA buttons |
| **About** | Background, interests, and experience summary |
| **Technical Skills** | 8 skill cards — HTML5, CSS3, JavaScript, React.js, Node.js, PyTorch, Machine Learning, IoT |
| **Projects** | 4 project cards linking to GitHub |
| **Contact** | Name, email, and message form |
| **Footer** | Copyright and GitHub profile link |

---

## Projects Showcased

| Project | Description |
|---------|-------------|
| Machine Learning Classifier | Classification models for data analysis and pattern recognition |
| Clustering Analysis | Clustering techniques for grouping and analyzing complex datasets |
| Smart Parking System | Sensor-based IoT parking project with real-time monitoring |
| Portfolio Website | This site — modern portfolio with animations and responsive design |

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and semantic layout |
| CSS3 | Styling, animations, glassmorphism, responsive grid |
| JavaScript (Vanilla) | Typing effect, scroll reveal, form handling |
| Google Fonts (Poppins) | Typography |
| Font Awesome 6 | Skill and UI icons |

---

## How to Run

No build tools or dependencies required. Just open the file in any modern browser:

```bash
# Option 1 — open directly
open index.html

# Option 2 — serve locally (recommended)
npx serve .
# or
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

---

## Responsive Breakpoints

| Breakpoint | Behavior |
|------------|----------|
| `> 900px` | Full layout, large hero heading (80px) |
| `≤ 900px` | Reduced hero font size (55px), tighter nav spacing |
| `≤ 650px` | Stacked navbar, compact hero (38px), smaller section titles |

---

## JavaScript Features

### Typing Effect
Animates the tagline character by character at 70ms per character on page load.

### Scroll Reveal
All `<section>` elements start invisible and translated downward. As the user scrolls, each section transitions to full opacity and its natural position over 0.9 seconds.

### Contact Form
Prevents default form submission, shows a success alert, and resets all fields.

---

## Design Highlights

- **Color palette:** Deep navy background (`#050510`) with cyan (`#00d9ff`) and magenta (`#ff00c8`) accents
- **Font:** Poppins (weights 300–800) for a clean, modern look
- **Cards:** Semi-transparent with a subtle white border and hover lift effect
- **Navbar:** Fixed, blurred glass effect with smooth link transitions
