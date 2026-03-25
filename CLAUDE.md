# Tampa Panel Press — Claude Code Instructions

## What This File Does
Claude Code reads this file automatically when you open this project. It tells Claude everything it needs to know to edit the site correctly without breaking anything.

---

## Project Overview
- **Site:** Tampa Panel Press — wood veneer & laminate hot-pressing service
- **Live URL:** https://tampapanel.com
- **Repo:** https://github.com/wattmeter/tampapanel
- **Stack:** Plain HTML + CSS, no frameworks, no build step
- **Host:** GitHub Pages (main branch, root folder)

---

## File Structure
```
/
├── index.html           — Main landing page
├── privacy-policy.html  — Privacy policy (REQUIRED — do not remove)
├── terms.html           — Terms of service (REQUIRED — do not remove)
├── logo.png             — Business logo
├── CNAME                — Custom domain (DO NOT EDIT OR DELETE)
└── CLAUDE.md            — This file
```

---

## Brand Guidelines
- **Primary color:** #AA3333 (deep red) — used for all headings and links
- **Background:** #FCFCF8 (warm off-white)
- **Text:** #333333 (charcoal)
- **Font stack:** "Segoe UI", Tahoma, Geneva, Verdana, sans-serif
- **Max container width:** 800px, centered
- **Logo:** logo.png, max-width 400px, centered, always links to /

---

## Business Information
- **Business name:** Tampa Panel Press
- **Address:** 107 E. Adalee St, Tampa, FL 33603
- **Phone:** 813-600-9562
- **Email:** info@tampapanel.com
- **Hours:** Mon–Fri, 8 AM – 5 PM
- **Service area:** Tampa Bay, FL
- **Services:** Wood veneer and laminate hot pressing, 4x8 panels only
- **Press:** Industrial Joos German Hot Press, up to 120°C at 5 bar
- **Shop humidity:** 50–55% RH (industrial dehumidifiers)

---

## Current Pricing (update here when prices change)
- 1–9 sheets: $49/sheet
- 10–49 sheets: $44/sheet
- 50+ sheets: $39/sheet
- Edge trimming: included in all services
- Delivery: $150 flat rate (free drop-off & pick-up)
- All pricing: per 4x8 sheet, both sides, standard PVA adhesive

---

## Legal Requirements (NEVER remove these)
Every page MUST have in the footer:
- Link to /privacy-policy.html
- Link to /terms.html
- Copyright notice: © 2026 Tampa Panel Press

The pricing section MUST include the disclaimer:
"Pricing subject to confirmation via written quote. Subject to change without notice."

---

## ADA / Accessibility Rules
- All images MUST have descriptive alt text
- All iframes MUST have a title attribute
- Links must be descriptive — no "click here"
- Color contrast: #AA3333 on #FCFCF8 passes WCAG 2.1 AA ✓

---

## How to Deploy Changes
After editing any file:
```
git add -A
git commit -m "brief description of what changed"
git push
```
Site goes live within ~60 seconds.

---

## Common Tasks

### Update pricing:
Find the `<ul class="pricing">` section in index.html and update the dollar amounts. Also update the numbers in this CLAUDE.md file.

### Add a photo:
```html
<h2>Our Work</h2>
<div style="display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:30px;">
  <img src="photo1.jpg" alt="Descriptive caption here" style="max-width:300px;border-radius:4px;">
</div>
```

### Add a new service to the list:
Find `<h2>Our Services` in index.html and add a new `<li>` in the same format as the others.

### Create a new page:
Copy the header/footer from privacy-policy.html for consistent styling. Add a link to it in the footer of index.html, privacy-policy.html, and terms.html.

---

## Planned Future Pages
- /quote.html — Online quote request form
- /process.html — Step-by-step process with photos
- /faq.html — Common customer questions
- /about.html — About Ben and the shop
- /gallery.html — Photo gallery of completed work

---

## DO NOT TOUCH
- CNAME — deleting this breaks the custom domain
- The `<meta charset="UTF-8">` tag in every page head
- The legal footer links (privacy policy + terms) on any page
- The Google Maps embed src URL
