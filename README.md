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

ビルドして、distフォルダの中身をアップする

```sh
npm run build
```

## 🚀 Stack

TypeScript

## 🚀 Project Structure

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── noimage-01.jpg
│   ├── components/
│   │   └── Card.astro
│   │   └── Header.astro
│   │   └── Footer.astro
│   │   └── LowerMainTitle.astro
│   │   └── HeaderNavi.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── styles/
│   │   └── global.css
│   └── pages/
│       └── index.astro
│       └── about/
│           └── index.astro
└── package.json
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
