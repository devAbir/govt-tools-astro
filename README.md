# GovUtil BD — Govt Tools Astro

A modern static site built with [Astro](https://astro.build) for Bangladeshi government employees.

## Features

- **Pay Scale 2026 Calculator**
- **Salary Calculator** with increments
- **GPF Profit Calculator**
- **Pension & Gratuity Calculator**
- **TA/DA Calculator**
- **Service Age Calculator**
- Smart Workflow utility tools (PDF, Photo Resizer, etc.)
- Bangla + English bilingual UI
- Dark / Light mode
- Fully responsive & offline-capable

## Tech Stack

- [Astro](https://astro.build) — Static site framework
- [Alpine.js](https://alpinejs.dev) — Lightweight interactivity
- Vanilla CSS with design tokens (Emerald Civic Portal design system)
- Google Fonts: Hind Siliguri + Inter
- Material Symbols Outlined icons

## Getting Started

```sh
npm install
npm run dev
```

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start dev server at `localhost:4321`        |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview production build locally            |

## Project Structure

```
/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── CategoryNav.astro
│   │   ├── ToolCard.astro
│   │   ├── SmartWorkflow.astro
│   │   ├── BlogSection.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
└── package.json
```

> This is an independent utility website, not affiliated with the Government of Bangladesh.
