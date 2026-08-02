# tryambakkaushik.com

Personal portfolio for Tryambak Kaushik, focused on reliable AI infrastructure and Physical AI validation.

The site is now built with Astro and published through GitHub Pages at [tryambakkaushik.com](https://www.tryambakkaushik.com/).

## Run locally

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
```

The build copies the existing static `assets/` directory and `CNAME` into `dist/` so GitHub Pages receives the custom domain file and legacy site assets.

## Deployment

GitHub Pages deployment is defined in `.github/workflows/deploy.yml` and runs on pushes to `master`.

The custom domain is configured through `CNAME` and must remain `www.tryambakkaushik.com`.
