# Fantuan Business Development Case

An interactive bilingual presentation for a Fantuan merchant business-development case. It demonstrates how a sales representative could assess a new malatang restaurant, explain the platform workflow, model unit economics, handle objections, and propose a controlled 90-day launch.

## Experience

The React presentation includes:

- merchant persona and concern analysis
- a step-by-step discovery and sales process
- an interactive opening conversation
- delivery-menu and fixed-combo design
- contribution-margin and monthly-profit calculators
- package recommendation logic
- objection-handling examples
- a 90-day launch plan and sample KPI dashboard
- Chinese and English presentation modes

Platform facts link to Fantuan's official merchant website. Restaurant performance figures are clearly presented as scenario assumptions rather than guarantees.

## Stack

- React
- TypeScript
- Vite
- Framer Motion
- Lucide React

## Local development

Requirements: Node.js and npm.

```bash
npm install
npm run dev
```

## Commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check and create a production build |
| `npm run preview` | Preview the production build |

## Project structure

```text
src/App.tsx       Presentation content, state, and calculators
src/styles.css    Presentation layout and responsive styles
src/main.tsx      React entry point
vite.config.ts    Vite configuration
vercel.json       Vercel deployment settings
```

## Deployment

Import the repository into Vercel with the Vite framework preset. No server-side environment variables are required.

## Disclaimer

This is a portfolio/case-study presentation. Commission tiers, package benefits, prices, order volumes, and profit calculations are illustrative unless confirmed in Fantuan's current official agreement and policies.
