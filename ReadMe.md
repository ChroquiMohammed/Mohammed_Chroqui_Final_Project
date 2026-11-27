# Sawti — صوتي

A reporting platform against forced marriage of minors, built with HTML and CSS for the 16 Days of Activism against Gender-Based Violence (25 Nov – 10 Dec 2026).

"On a dit oui à sa place." — She never consented.

## What it does

- Report in 3 ways: write a letter, record a voice message, or answer 5 simple questions in Arabic
- A trusted-person step: share the contact of someone you trust
- After reporting: what happens next (listen, guide, support, justice)
- Helplines: 2511 (children), 8350 (Kolona Maak), 19 (police)
- Quick-exit button on every page

## Pages

- Accueil — hero and key numbers
- Signaler — report (letter, voice, questionnaire)
- Après — what happens after reporting
- Aide — helplines and FAQ

## Colors

- Orange (accent) — #FF6B00
- Black (background) — #111111
- Beige (light background) — #FDF8F0

## Fonts

- Playfair Display — hero title (font-display)
  https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;0,800;1,400;1,500;1,600&display=swap
- EB Garamond 600 — big numbers (font-stat)
  https://fonts.googleapis.com/css2?family=EB+Garamond:wght@500;600;700&display=swap

## Tech

- HTML
- CSS
- Tailwind CSS v4 (CLI)
- Google Fonts
- Git & GitHub
- No JavaScript — everything interactive is pure HTML/CSS
## Project structure

```
sawti/
├── index.html
├── public/
│   ├── css/
│   │   ├── input.css
│   │   └── output.css
│   ├── images/
│   │   ├── logo_sawti.webp
│   │   └── hero_section_bg.webp
│   └── pages/
│       └── signaler.html
```

## How to work on it

1. Edit `public/css/input.css` (custom classes) or the HTML files.
2. Rebuild the CSS:

```bash
npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch
```

3. Open `index.html` in your browser.
4. Do not edit `output.css` directly — it is generated from `input.css`.
