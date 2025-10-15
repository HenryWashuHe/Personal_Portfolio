# Henry He | Personal Portfolio

![Portfolio Banner](public/social_img.webp)

Personal portfolio website for Henry He, a Computer Science and Mathematics student at Columbia University. This website showcases my projects, experience, and technical skills.

## About

Computer Science and Mathematics student at Columbia University with experience in:
- Machine Learning
- Full-Stack Development
- Cloud Deployment

Currently working as a Software Engineering Intern at XPorter.

## Installation

Run the following command in your terminal

```bash
pnpm install
```

Once the packages are installed you are ready to run astro. Astro comes with a built-in development server that has everything you need for project development. The astro dev command will start the local development server so that you can see your new website in action for the very first time.

```bash
pnpm run dev
```

## Features

- **Projects Showcase**: Display of technical projects and work
- **CV/Resume**: Interactive timeline of experience and education
- **Blog**: Technical articles and insights (coming soon)
- **Responsive Design**: Mobile-friendly interface
- **RSS Feed**: Stay updated with new content

## Tech Stack

- **[Astro](https://astro.build)** - Static site generator
- **[TailwindCSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[DaisyUI](https://daisyui.com/)** - Component library for Tailwind
- **TypeScript** - Type-safe development

## Project Structure

```
├── src/
│   ├── components/     # Reusable UI components
│   ├── content/        # Blog posts and content
│   ├── layouts/        # Page layouts
│   ├── pages/          # Site pages
│   └── config.ts       # Site configuration
├── public/             # Static assets
└── astro.config.mjs    # Astro configuration
```

## Development Commands

- `pnpm run dev` - Start the development server
- `pnpm run build` - Build the production site
- `pnpm run preview` - Preview the production build locally

## Deployment

The site can be deployed on static hosting platforms like Vercel, Netlify, or GitHub Pages. For deployment instructions, see the [Astro deployment guide](https://docs.astro.build/en/guides/deploy/).

## Built With

This portfolio is built using the [Astrofy](https://github.com/manuelernestog/astrofy) template by Manuel Ernesto Garcia.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
