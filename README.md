# Sumanth Pabba — Full Stack Developer Portfolio

A modern, minimalist developer portfolio built with **Astro** and **Tailwind CSS v4**, showcasing my skills, experience, and projects as a Full Stack Developer.

**Live Site:** [sumanth-uwin.github.io/FullStack-devportfolio](https://Sumanth-Uwin.github.io/FullStack-devportfolio)

---

## Built With

- **[Astro](https://astro.build/)** — Static site generator
- **[Tailwind CSS v4](https://tailwindcss.com/)** — Utility-first CSS framework
- **[Tabler Icons](https://tabler.io/icons)** — Icon library
- **TypeScript** — Type-safe configuration

---

## Features

- Single-file configuration (`src/config.ts`) for all content
- Sections: Hero, About, Skills, Projects, Experience, Education
- Conditional rendering — sections auto-hide if data is removed
- Accent color system that propagates site-wide
- Fully responsive and mobile-friendly
- Deployed via GitHub Actions to GitHub Pages

---

## Local Development

```bash
git clone https://github.com/Sumanth-Uwin/FullStack-devportfolio.git
cd FullStack-devportfolio
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

---

## Customization

All content is managed through [`src/config.ts`](src/config.ts):

- **Personal info**: name, title, description, accent color
- **Social links**: email, LinkedIn, GitHub (all optional)
- **About**: bio paragraph
- **Skills**: array of technology strings
- **Projects**: name, description, link, skills used
- **Experience**: company, title, date range, bullet points
- **Education**: school, degree, date range, achievements

---

## Deployment

Deployed automatically to GitHub Pages via GitHub Actions on every push to `master`.

---

## License

MIT
