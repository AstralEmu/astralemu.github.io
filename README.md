<p align="center">
  <img src="https://github.com/AstralEmu/.github/raw/refs/heads/main/profile/banner-astralemu.svg" alt="AstralEmu Docs" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/framework-Starlight%20%2F%20Astro-f2d974?style=flat-square" alt="Starlight"/>
  <img src="https://img.shields.io/badge/hosted-GitHub%20Pages-1a1a4e?style=flat-square" alt="GitHub Pages"/>
</p>

# astralemu.github.io

Documentation and showcase for the AstralEmu project. Built with [Starlight](https://starlight.astro.build/) (Astro) and deployed on GitHub Pages.

**Live site**: [https://astralemu.github.io](https://astralemu.github.io)

---

## Project structure

```
astralemu.github.io/
├── src/
│   ├── content/docs/       ← Documentation pages (Markdown)
│   └── assets/             ← Images, logo, etc.
├── astro.config.mjs
└── package.json
```

## Local development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

The site is automatically built and deployed via GitHub Actions on every push to `main`, using Astro's official GitHub Pages deployment action.

## Contributing

Documentation contributions are welcome — fix a typo, improve a guide, or add a page for a new device. Just edit the Markdown files in `src/content/docs/` and open a PR.

---

<p align="center">
  <a href="https://github.com/AstralEmu/astralemu">Main Repo</a> •
  <a href="https://github.com/AstralEmu/astralemu-packages">Packages</a> •
  <a href="https://github.com/orgs/AstralEmu/discussions">Community</a>
</p>
