# SidSphere

Personal Portfolio by Sidharth Kumar — a collection of work, experience, and creative interests presented through an interactive, code-inspired website.

[View the live site](https://sidhaaarth24.github.io/sidsphere/)

## About

SidSphere introduces Sidharth Kumar, a Computer Science & Engineering student interested in development, design, and creative technology. The site brings together an introduction, skills, education, experience, selected projects, certificates, awards, and contact links.

## Features

- Responsive portfolio with light and dark themes
- Interactive Three.js hero visual and motion effects
- Keyboard-friendly command palette for navigating sections
- Reduced-motion support
- Portfolio content maintained separately in `data/content.json`
- Static production build suitable for GitHub Pages

## Built with

- TypeScript
- Vite
- Three.js
- Tailwind CSS and PostCSS
- Font Awesome icons

## Getting started

### Requirements

- Node.js 22 or later
- npm

### Install and run locally

```bash
git clone https://github.com/sidhaaarth24/sidsphere.git
cd sidsphere
npm ci
npm run dev
```

Vite prints the local development URL in the terminal (by default, `http://localhost:5173`). The development server is also configured to listen on the network interface.

### Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run typecheck` | Run the TypeScript type check |
| `npm run build` | Create the production build in `dist/` |
| `npm run preview` | Preview the production build locally |

## Project structure

```text
data/
  content.json       Portfolio text, links, and project data
public/
  images/            Project previews, certificates, and award images
src/
  main.ts            Page structure and interactive behavior
  hero-object.ts     Three.js hero visual
  spatial-motion.ts  Pointer and scroll motion
  styles.css         Site styles
  types.ts           TypeScript data types
index.html           Vite entry page
vite.config.ts       Vite configuration
```

## Updating portfolio content

Edit `data/content.json` to update the portfolio's text, skills, education, experience, projects, certificates, awards, and social links. Referenced image files live under `public/images/`. Keep image paths and content entries in sync.

## Deployment

Run `npm run build` and publish the generated `dist/` directory to a static host. The Vite configuration sets the base path to `/sidsphere/`, matching the GitHub Pages project site.

## License

The project source code is available under the [MIT License](./LICENSE). Portfolio content, personal information, images, and third-party materials may have separate rights or terms; the MIT license should not be taken as permission to reuse materials that are not owned by the project author.