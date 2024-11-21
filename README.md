# Astro Static-template

New Project

```sh
npm create astro@latest -- --template basics
```

package.lock.json

```sh
npm ci
npm run dev
```

## Flow

ビルドして、distフォルダの中身をホスティングする

```sh
npm run build
```

## 🚀 Stack

TypeScript

## 🚀 Project Structure

```text
.
├── README.md
├── astro.config.mjs
├── package-lock.json
├── package.json
├── public
│   ├── favicon.svg
│   └── logo_01.png
├── src
│   ├── assets
│   │   ├── noimage-01.jpg
│   │   ├── noimage-02.jpg
│   │   └── noimage-03.jpg
│   ├── components
│   │   ├── BaseHead.astro
│   │   ├── layouts
│   │   │   ├── Footer.astro
│   │   │   ├── Header.astro
│   │   │   └── HeaderNavi.astro
│   │   └── ui
│   │       ├── Card.astro
│   │       ├── LowerPageTitle.astro
│   │       ├── NewsList.astro
│   │       ├── Slider.astro
│   │       ├── SliderComponent.astro
│   │       └── SliderItems.astro
│   ├── consts.ts
│   ├── env.d.ts
│   ├── layouts
│   │   └── Layout.astro
│   ├── pages
│   │   ├── 404.astro
│   │   ├── about
│   │   │   └── index.astro
│   │   ├── company
│   │   │   └── index.astro
│   │   └── index.astro
│   └── styles
│       └── global.css
└── tsconfig.json
```

## 🧞 Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
