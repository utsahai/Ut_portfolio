# Utkarsh Sahai — Portfolio

Source for my personal portfolio site, live at **[utsahai.github.io](https://utsahai.github.io)**.

## About this site

A single-page portfolio built to showcase my move from backend engineering into technical product management — the systems I've designed, the products I've shipped, and the impact behind both. No template, no page builder — just HTML, CSS, and JavaScript, written and tuned by hand.

## What's inside

- `index.html` — the entire site: markup, styling, and interactions in one file
- `Utkarshsahai.pdf` — my resume, linked from the nav bar and the hero section

## Sections

- **About** — background, and the product and technical skills I bring to the table
- **Experience** — my time at Accenture, broken out by role and switchable via tabs
- **Work** — featured case studies (a real-time batch-tracking platform, a chatbot pivoted into a self-service tool) alongside smaller shipped projects
- **Achievements** — recognitions from my time in engineering and product
- **Contact** — the fastest way to reach me

## Built with

Plain HTML, CSS, and vanilla JavaScript — no framework, no build step, no dependencies to install. Type is set in Inter and IBM Plex Mono, loaded from Google Fonts.

## Running it locally

There's nothing to build. Clone the repo and open `index.html` in a browser, or serve the folder if you'd rather not deal with `file://` restrictions:

```bash
git clone https://github.com/utsahai/utsahai.github.io.git
cd utsahai.github.io
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Hosted free on GitHub Pages, served straight from `main`. Push a change to this branch and it's live at [utsahai.github.io](https://utsahai.github.io) within a minute or two — no separate deploy step.

## Why no framework

This is a portfolio, not an app — it doesn't need one. Keeping it to a single dependency-free file means anyone (recruiter, collaborator, future me) can open it, understand it, and change it without setting up a build pipeline first.
