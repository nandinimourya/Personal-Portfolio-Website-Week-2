# Personal Portfolio Website — Week 2: CSS Styling

A styled personal portfolio website built by adding CSS3 to the Week 1 HTML structure. This project focuses on visual design, layout, responsiveness, and interactive styling.

**Student:** Nandini Mourya
**Course:** B.Tech CSIT — Web Development Internship
---

## Project Description

This is the Week 2 continuation of the personal portfolio project. The same semantic HTML5 structure from Week 1 is now styled using an external `style.css` file. The design uses a deep indigo and lavender color theme, Flexbox for layout, and media queries for full mobile responsiveness.

---

## Technologies Used

- HTML5 (from Week 1)
- CSS3 — external stylesheet, custom properties, Flexbox, media queries

---

## Folder Structure

```
Personal-Portfolio-Website/
│
├── index.html          ← Main website file
├── style.css           ← External CSS stylesheet (Week 2)
├── README.md           ← This file
├── images/
│   └── profile.jpg     ← Profile photo


---

# How to Run

1. Clone or download this repository.
2. Open `index.html` in any web browser.
3. Both `index.html` and `style.css` must be in the same folder.

---

# CSS Features Implemented

# Selectors Used (3+ types)
- **Element selectors** — `body`, `h1`, `h2`, `h3`, `p`, `input`, `textarea`, `button`
- **Class selectors** — `.error-msg`, `.form-success`, `.skill-highlight`
- **ID selectors** — `#about`, `#skills`, `#contact`, `#dark-mode-btn`
- **Pseudo-classes** — `:hover`, `:focus`, `:last-child`
- **Attribute selectors** — `input[type="text"]`, `input[type="email"]`

# Color Scheme
| Token | Value | Used For |
|---|---|---|
| Deep Indigo | `#1e1b4b` | Headings, nav, footer background |
| Indigo | `#4f46e5` | Buttons, links, borders, accents |
| Lavender | `#ede9fe` | Section backgrounds, ghost buttons |
| Soft Purple | `#c4b5fd` | Header subtitle, footer text |
| Near-white | `#f8f7ff` | Page background |

# Layout
- **Flexbox** used for navigation bar, footer social links, and form button row
- **max-width: 820px** content column centered with `margin: 0 auto`
- **Sticky navigation** using `position: sticky; top: 0`

# Hover Effects
- Nav links — indigo background highlight on hover
- Buttons — darker shade + `translateY(-1px)` lift effect
- Form inputs — indigo glow ring on focus (`box-shadow`)

# Responsive Design
- `@media (max-width: 600px)` breakpoint for mobile
- Navigation stacks vertically on small screens
- Buttons become full-width on mobile
- Font sizes scale down using `clamp()`-ready values

# Additional Styling
- Circular profile image using `border-radius: 50%`
- Gradient header using `linear-gradient(135deg, ...)`
- Section heading underline accent using `border-bottom`
- Dark mode styles (added in Week 3 prep) using `.dark-mode` class

---

# What's Next — Week 3

JavaScript will be added to make the portfolio interactive — dark mode toggle, form validation with error messages, skill click highlights, scroll spy navigation, and a live character counter.
