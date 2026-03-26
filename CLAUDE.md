# DevOdyssey — LinkedIn for Developers

## Project
Modern LinkedIn clone for developers. Fast, beautiful, feature-rich.

## Stack
- Next.js 16 (App Router, RSC, Turbopack)
- Tailwind CSS v4
- TypeScript
- Prisma + PostgreSQL
- NextAuth.js
- tRPC
- Framer Motion

## Design
**Pencil is the source of truth for all UI/UX decisions.**
- All screens, components, and flows are designed in `.pen` files
- Use `mcp__pencil__*` tools to read design, never implement without checking design first
- Design file: `design.pen`

## Key Features
- Developer profiles (skills, GitHub, projects, contributions)
- Job board with user-friendly filters for finding devs and jobs
- Dev feed (posts, code snippets, articles)
- Real-time messaging
- Skill endorsements & recommendations
- Open source showcase

## Principles
- Mobile-first, pixel-perfect implementation matching Pencil design
- Performance: Core Web Vitals green
- Accessibility: WCAG 2.1 AA
- у нас минимализм, чем меньше отвликающих элементов, тем лучше
