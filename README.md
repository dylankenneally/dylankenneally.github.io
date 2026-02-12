# Digital scrapbook

Basic landing page used to share projects, experiments, and _stuff_. Built with [Eleventy (11ty)](https://11ty.dev/) and deployed to GitHub pages at [kenneally.dev](https://kenneally.dev/), ([dylankenneally.github.io](https://dylankenneally.github.io/)).

## To build & run

### Prerequisites

- Install [Node.js](https://nodejs.org/en)
  - Version 24.12.0 has been used in development, but any recent version should work.

### Getting the source code

```bash
git clone git@github.com:dylankenneally/dylankenneally.github.io.git
cd dylankenneally.github.io
```

### Install dependencies & start a development server

```bash
npm install
npm start
# open http://localhost:8080 in your browser
```

### Available scripts

The following scripts are available once `npm install` has been ran.

| Script | Action |
| - | - |
| `npm start` | **Starts the development server** after building the site. |
| `npm run build` | Performs a **production build** of the site/app to `./_site`. |
| `npm run deploy` | Builds and **deploys the site** to GitHub Pages. |
