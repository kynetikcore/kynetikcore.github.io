# Kynetic Core - Official Website

Science-based fitness supplements company website built with modern web technologies.

## Tech Stack

- **Astro** - Modern static site generator for optimal performance
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Type-safe development
- **GitHub Pages** - Automatic deployment

## Features

- ⚡ Lightning-fast static site generation
- 📱 Fully responsive design
- 🎨 Modern UI with smooth animations
- ♿ Accessible and SEO-friendly
- 🚀 Automatic deployment via GitHub Actions

## Development

### Prerequisites

- Node.js 18+ and npm

### Getting Started

1. Clone the repository:
```bash
git clone https://github.com/kynetikcore/kynetikcore.github.io.git
cd kynetikcore.github.io
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open http://localhost:4321 in your browser

### Available Commands

| Command | Action |
|---------|--------|
| `npm install` | Install dependencies |
| `npm run dev` | Start development server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

### Manual Deployment Setup

1. Go to your GitHub repository Settings
2. Navigate to Pages section
3. Under "Build and deployment", select:
   - Source: GitHub Actions
4. The workflow will automatically deploy on the next push

## Project Structure

```
/
├── public/
│   ├── images/          # Static images
│   └── favicon.svg      # Site favicon
├── src/
│   ├── components/      # Reusable components
│   │   ├── Navigation.astro
│   │   └── Footer.astro
│   ├── layouts/         # Page layouts
│   │   └── BaseLayout.astro
│   └── pages/           # Site pages
│       └── index.astro  # Homepage
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind CSS configuration
└── tsconfig.json        # TypeScript configuration
```

## Brand Colors

- **Kynetic Green**: `#A4FF00` - Primary accent color
- **Kynetic Dark**: `#0A0A0A` - Primary background

## Connect

- Instagram: [@corekynetik](https://www.instagram.com/corekynetik/)

## License

Copyright © 2025 Kynetic Core. All rights reserved.
