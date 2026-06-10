# SPOTLIGHT Dance Film Festival Website

One-page Astro website for SPOTLIGHT Dance Film Festival, an independent dance film festival based in Frankfurt am Main, Germany.

## Tech Stack

- Astro
- HTML and CSS
- Minimal JavaScript through Astro only
- Static deployment

## Install

```sh
npm install
```

## Local Development

```sh
npm run dev
```

Astro will print a local URL, usually `http://localhost:4321`.

## Build

```sh
npm run build
```

The production site is generated into `dist/`.

## Preview Production Build

```sh
npm run preview
```

## Deploy To Netlify

This repository includes `netlify.toml` with static build settings:

- Build command: `npm run build`
- Publish directory: `dist`
- Node version: `24`

On Netlify, connect the Git repository and use the included configuration. Netlify will install dependencies, run the Astro build, and publish the generated static site.

## Content And Assets

Planning files live in `project_brief/` and `references/`.

Original source assets remain untouched in `source-assets/`. Selected web-ready copies are stored in `public/images/`.
