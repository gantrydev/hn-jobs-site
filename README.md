This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deployment

Pushes to `main` and `data-updated` repository dispatches run CI against the latest
data. Lint, type checking, the high-severity dependency audit, and the production
build must pass before the Pages artifact is uploaded. The reusable deployment
workflow publishes that checked artifact. Pull requests never publish.

TODO: Clear the remaining moderate [minimatch advisory](https://github.com/advisories/GHSA-g3hv-75wg-m249)
when ESLint supports its patched major version. The low-severity
[deepmerge advisory](https://github.com/advisories/GHSA-gcqx-w48m-w2h4) in shadcn has no patched release.
