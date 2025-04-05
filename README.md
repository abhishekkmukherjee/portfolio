# Personal Portfolio Website

A modern, responsive portfolio website built with Astro and TypeScript. Features a clean design, dark/light mode, and sections for showcasing work experience, projects, skills, and more.

## Features

- 🚀 Built with Astro for fast performance
- 💻 Responsive design that works on all devices
- 🌓 Dark/light mode support
- ⌨️ NeoVim-inspired keyboard shortcuts
- 📄 Printable CV generation
- 🎨 Beautiful and modern UI
- ⚡ Fast page loads and smooth transitions

## Tech Stack

- Astro
- TypeScript
- Tailwind CSS
- PNPM
- React Icons
- Astro Icons

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/abhishekkmukherjee/portfolio.git
```

2. Install dependencies:

```bash
pnpm install
```

3. Start the development server:

```bash
pnpm dev
```

4. Build for production:

```bash
pnpm build
```

## Project Structure

```
/
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
└── package.json
```

## License

MIT License

## Author

Abhishek Mukherjee

- GitHub: [@abhishekkmukherjee](https://github.com/abhishekkmukherjee)
- LinkedIn: [Abhishek Mukherjee](https://www.linkedin.com/in/abhishek-mukherjee-a8811a19b/)

## Print-friendly portfolio CV

> [!TIP]
> 〔🌐〕[Take a look](#)

<p align = "center">
    <img src="public/astro-vim.png" alt="logo" width="200"/>
</p>

## 🛠️ Stack

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.
- [**TailwindCSS**](https://tailwindcss.com/) - Utility-first CSS framework.
- [**Iconify**](https://iconify.design/) - Icon library.
- [**FancyBox**](https://fancyapps.com/fancybox/3/) - Image viewer.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Dropdown menu with keyboard shortcuts made in pure JavaScript.

## 🚀 Getting Started

Modify the `cv.json` file to create your own printable Portfolio/CV.

### 1. Use this Repo as an Astro Project Template

- I use [pnpm](https://pnpm.io/installation) as my package manager.

# Initialize the project

```bash
pnpm create astro@latest --template ArielFalcon/portfolio
```

### 1-1. Clone the repo

If you don't want to use the template command, you can clone this repo and install the dependencies.

```bash
git clone https://github.com/ArielFalcon/portfolio.git
cd portfolio
pnpm install
```

### 2. Add Your Content:

Edit the `cv.json` file to create your own printable Portfolio/CV.

### 3. Launch the Development Server:

```bash
# Enjoy the results
pnpm dev
```

1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result 🚀

### 4. Customisable colours:

Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber, pink and default, with its variants in dark mode, or create your own.

## 🧞 Commands

|     | Command             | Action                                                         |
| :-- | :------------------ | :------------------------------------------------------------- | --- |
| ⚙️  | `dev` or `start`    | Launches a local development server at `localhost:4321`.       |
| ⚙️  | `build`             | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`           | Local preview at `localhost:4321`                              |
| 📦  | `deploy:vercel`     | Deploy on Vercel.                                              |
| 📦  | `deploy:cloudflare` | Deploy on Cloudflare, please run `wrangler login` first.       |     |

CV JSON schema from [**jsonresume.org**](https://jsonresume.org/schema/)
summary: experienced in full stack development building high complexity applications in code and no code tools with a focus on performance, user experience, and system integration.
