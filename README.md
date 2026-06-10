# 01-ts-basics

Minimal TypeScript exercises (GoIt course) — Vite + TypeScript starter.

## Overview

This repository contains a set of small TypeScript exercises in the `src/` folder (task-1.ts … task-8.ts). It's scaffolded with Vite for development and build.

## Prerequisites

- Node.js (recommended 16+)
- npm (or yarn)

## Install

Install dependencies:

```bash
npm install
```

## Development

Start the Vite dev server:

```bash
npm run dev
```

## Build & Preview

Build for production (note: `build` uses base `/01-ts-basics/`):

```bash
npm run build
```

Preview the built site locally:

```bash
npm run preview
```

## Deploy

There is a `deploy` script that builds and publishes `dist/` to GitHub Pages using `gh-pages`:

```bash
npm run deploy
```

## Project Structure

- index.html
- package.json
- tsconfig.json
- src/
  - task-1.ts … task-8.ts  — exercise files
  - vite-env.d.ts

## Notes

- The build `base` is configured for GitHub Pages under `/01-ts-basics/`.
- Edit tasks in `src/` and re-run the dev server to see changes.

If you want any additions (examples, tests, or a contribution section), tell me which and I will add them.
# 01-ts-basics