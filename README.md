# Progwise website

Single-page introduction to the direction of Progwise Ltd. Built with Astro and deployed to www.progwise.net by the existing GitHub Pages workflow.

## Development

Use Node.js 22 and run `npm ci`, then `npm run dev`.

## Verification

Run `npm run build`. The static output is written to `dist/`.

Content lives in `src/pages/index.astro` and styling in `src/styles/global.css`. The office illustration is an explicitly labelled product concept. The contact link uses the existing info@progwise.net address.

A push to `main` triggers production deployment. Repository history contains the previous website.
