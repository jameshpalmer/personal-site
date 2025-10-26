# jamespalmer-site

A personal site built with modern web technologies, featuring minimal design and smooth view transitions.

## Tech Stack

- **[Astro](https://astro.build)** - Static site framework
- **[Tailwind CSS 4.x](https://tailwindcss.com)** - Utility-first CSS framework
- **[DaisyUI](https://daisyui.com)** - Tailwind CSS component library
- **[@tailwindcss/typography](https://tailwindcss.com/docs/typography-plugin)** - Beautiful typographic defaults

##  Features

- Minimal, clean design aesthetic
- View transitions for smooth page navigation
- Responsive layout
- Static site generation for optimal performance

## Project Structure

```text
/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   └── Hero.astro
│   ├── layouts/
│   │   ├── Layout.astro
│   │   └── ArticleLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── about.astro
│   │   ├── projects.astro
│   │   └── self.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
└── package.json
```

## Commands

All commands are run from the root of the project:

| Command           | Action                                           |
| :---------------- | :----------------------------------------------- |
| `pnpm install`    | Installs dependencies                            |
| `pnpm dev`        | Starts local dev server at `localhost:4321`      |
| `pnpm build`      | Build your production site to `./dist/`          |
| `pnpm preview`    | Preview your build locally, before deploying     |
| `pnpm astro ...`  | Run CLI commands like `astro add`, `astro check` |

## Learn More

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [DaisyUI Documentation](https://daisyui.com)
