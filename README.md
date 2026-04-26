# Next.js Project Template

Starter template for Next.js projects with TypeScript and Tailwind CSS. Bootstrap a new Next.js app with a clean, pre-configured foundation.

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see your app.

## What's Included

- **Next.js 15+** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for utility-first styling
- **shadcn/ui** components pre-configured via `components.json`
- **ESLint** for code quality
- **Geist font** via `next/font` for modern typography

## Using as a Template

### GitHub Template

1. Click "Use this template" on the repository page
2. Create a new repository from this template
3. Clone your new repo and run `npm install`

### Manual

```bash
git clone https://github.com/jimstratus/nextjs-project-template.git my-new-project
cd my-new-project
rm -rf .git
git init
npm install
```

Then customize `package.json` and `next.config.ts` for your project.

## Project Structure

```
├── app/              # App Router pages and layouts
├── components/       # Shared React components
├── components.json   # shadcn/ui configuration
├── next.config.ts    # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json     # TypeScript configuration
```

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [shadcn/ui Documentation](https://ui.shadcn.com)
