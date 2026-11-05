# AGENTS.md — Rules for working on nickytgar.github.io

This is Nicky Garcia's personal website, hosted on GitHub Pages at
https://nickytgar.github.io. Any AI agent editing this folder follows these rules.

## 1. Never publish

- **Phone number.** It's on the CV, but it never goes on the public site.
- **Home address, birth date, or ID numbers** (passport, SSN, etc.).
- **Confidential deal details** beyond what's on the CV: client or company names
  the CV leaves anonymous ("a Philippine conglomerate", "a gold mining company")
  stay anonymous. Don't add internal figures, client names, or non-public data.
- **Other people's personal info** (names, photos, contact details) without
  Nicky's explicit OK.
- **Files that aren't meant to be public:** the original CV PDF, the
  full-resolution photo (`IMG_4857.JPG`), drafts, notes, or anything with
  secrets/keys. Use the downsized `headshot.jpg` on the site instead.
- **Invented content.** No made-up accomplishments, metrics, testimonials, or
  skills. Everything on the site traces back to the CV or to something Nicky
  wrote.

## 2. Ask Nicky first before

- **Pushing, committing, or deploying** anything to GitHub (including creating
  the repo or enabling Pages).
- **Adding a downloadable CV** or any new contact method (email, phone, socials).
- **Changing facts**: dates, titles, numbers, or wording of CV bullets beyond
  light formatting.
- **Adding third-party services**: analytics, trackers, contact forms, comment
  widgets, fonts/scripts from new CDNs.
- **Deleting or overwriting** existing files.
- **Adding new pages or sections** that aren't on the CV.

## 3. Style

- **Vibe:** professional but casual — warm, confident, plain-spoken. No
  buzzword piles, no exclamation-point marketing.
- **Colors:** Columbia blue (`#B9D9EB`) as the signature accent, deep Columbia
  navy (`#1D4F91` / `#0B2545`) for text and contrast, warm off-white background.
  Text must keep at least WCAG AA contrast — never put white or light text on
  Columbia blue.
- **Navigation:** streamlined — one sticky top bar, a handful of section links,
  smooth scroll. No dropdowns or hamburger menus unless the page grows past ~6
  sections.
- **Content order:** follows the CV — Education, Experience, Additional
  Information.
- **Tech:** plain HTML + CSS (+ minimal vanilla JS). No build step, no
  frameworks. Must work as a static GitHub Pages site and on phone screens.
- **Images:** web-sized (under ~200 KB), with descriptive `alt` text.
- **Writing:** US English, sentence case headings, numbers as on the CV
  (e.g., `$41.3B`, `8+ hours`).
