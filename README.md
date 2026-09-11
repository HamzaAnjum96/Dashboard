# Warpath Strategic Command
Desktop-first modern warfare strategy command UI. Select air, ground, and naval forces on the theater map, inspect readiness, and resolve encounters through quick engagements.

## Development
This project uses pnpm 10. Enable Corepack once, then install and start Vite:

```sh
corepack enable
pnpm install
pnpm run dev
```

## Deployment
The included GitHub Actions workflow installs the pinned pnpm version, builds the application, and deploys GitHub Pages on pushes to `main`. Select **GitHub Actions** as the Pages source in repository settings.
