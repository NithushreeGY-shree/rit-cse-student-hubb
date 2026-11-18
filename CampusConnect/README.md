# CampusConnect — Smart College Hub

A responsive, interactive college community website created for **CODESTORM 2026 – Challenge 01**.

## Features
1. **Event Explorer** — search and filter event cards; register interest (saved in browser localStorage).
2. **Student Resource Hub** — filter useful learning and career links by category.
3. **Community Connect** — discover student community areas and external GDG resources.
4. **Contact form** — browser-side validation and local message storage (no email is sent).
5. Responsive navigation, active section highlighting, toast feedback and mobile menu.

## Tech stack
- HTML5
- CSS3 (responsive layout, media queries, reduced-motion support)
- Vanilla JavaScript
- Browser localStorage for demo interactions

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For local development, you can also use the VS Code **Live Server** extension.

No build tools or package installation are required.

## Required organizer logos
The page expects these files:
- `assets/logos/rit-logo.svg`
- `assets/logos/cse-logo.svg`
- `assets/logos/gdg-logo.svg`

Replace the placeholder files with the **official logo assets supplied by the CODESTORM organizers**. Keep the filenames or update the corresponding image paths in `index.html`. Do not stretch or recolor the official logos.

## Before public submission
- Replace illustrative event details with verified event information.
- Replace illustrative community names/links with official college club information.
- Add the correct contact details and social links.
- Test all pages and links on mobile, tablet and desktop.
- Confirm the three official logos are visible.
- Publish using GitHub Pages, Netlify or Vercel, then add the live URL here.

## Deployment (GitHub Pages)
1. Push this project to a public GitHub repository.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Wait for the deployment URL to appear in the Pages section.

## Demo data and privacy
Event interests and contact form messages are stored only in the visitor's browser using localStorage. They are not sent to a server, email inbox, or database. A backend/API is required for real multi-user registration and message delivery.

## Challenge alignment
Includes Home, About, Main Content, Features, Contact and Footer sections; three institution logo positions; responsive UI; functional navigation; working external resource links; three interactive features; and source code suitable for a public GitHub repository.
