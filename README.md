# Information Assurance Portfolio

A professional, English-language portfolio for an Information Assurance student (FPT University), focused on **Blue Team** fundamentals with a long-term path toward **Red Team** roles. Built with a modern cybersecurity theme and responsive layout.

## Features

- **Responsive layout** — Works on desktop, tablet, and mobile
- **Smooth animations** — Typing effect, skill bars, and scroll-based highlights
- **Sticky navigation** — With active section highlighting and mobile hamburger menu
- **Animated skill bars** — Reveal on scroll with percentage labels
- **Contact form** — Client-side validation and success/error messages
- **Dark theme** — Cybersecurity-oriented color scheme (slate + cyan accent)

## Project structure

```
portfolio/
├── index.html          # Main page (all content in English)
├── styles/
│   └── main.css       # Layout, theme, and responsive styles
├── js/
│   └── script.js      # Typing, nav, skill bars, form, smooth scroll
├── assets/            # Optional: images, avatars
└── README.md
```

## Tech stack (portfolio site)

- **HTML5** — Semantic structure and accessibility
- **CSS3** — Grid, Flexbox, variables, transitions, media queries
- **JavaScript (ES6+)** — Intersection Observer, smooth scroll, form handling
- **Font Awesome** — Icons
- **Google Fonts** — Space Grotesk, JetBrains Mono

## Color scheme

| Variable   | Value    | Usage        |
|-----------|----------|--------------|
| Primary   | `#0f172a`| Background   |
| Secondary | `#1e293b`| Cards, nav   |
| Accent    | `#22d3ee`| Links, CTAs  |
| Text      | `#f8fafc`| Main text    |

## Sections

1. **Navigation** — Logo, menu, mobile toggle, active link on scroll
2. **Hero** — Typing headline, short intro, CTA buttons
3. **About** — FPT University, Year 4, tech stack (Python, Docker, VirtualBox, Burp Suite, Linux, Cloud), stats
4. **Skills** — Programming (Python, Bash), Security (Burp Suite, Wireshark), Infrastructure (Docker, VirtualBox), Linux & Cloud
5. **Projects** — Placeholder cards (Network lab, Web app security, Docker tools, Blue Team exercises); replace with your real links
6. **Career path** — Short-term: Blue Team; Long-term: Red Team
7. **Contact** — Email, LinkedIn, GitHub, contact form
8. **Footer** — Year, Bruce Schneier quote

## Customization

### Personal details

Edit `index.html`:

- Replace `your.email@example.com` with your email
- Update LinkedIn and GitHub `href` in the contact section
- Add your real project URLs to `.project-link` elements
- Optionally add a profile image: put it in `assets/` and replace the `.image-placeholder` block with an `<img>` (see comments in CSS for sizing)

### Skills and percentages

In the `#skills` section, change `data-width` on each `.skill-fill` and the corresponding `.skill-pct` text.

### Adding a real contact backend

The form currently shows a success message only. To send emails or store submissions, replace the form handler in `js/script.js` with a `fetch()` call to your API or form service (e.g. Formspree, Netlify Forms, or your own backend).

## Running locally

1. Clone or download the project.
2. Open `index.html` in a browser, or use a local server (e.g. VS Code Live Server).

No build step required.

## Browser support

- Chrome, Firefox, Safari, Edge (recent versions)
- Smooth scroll and Intersection Observer supported in all modern browsers

## License

MIT — Free for personal and commercial use.

---

*"Security is not a product, but a process."* — Bruce Schneier
