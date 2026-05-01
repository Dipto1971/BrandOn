# BRANDON OVERVIEW
- **Type**: Digital Advertising Agency Platform.
- **Features**: Custom service orders (banners, signboards), portfolio gallery.
- **RBAC**: Strict role access (ADMIN, AGENT, CUSTOMER).

# STACK
- **Frontend**: Next.js 14 (App Router), TypeScript, Tailwind.
- **Backend**: Node.js, API Routes, NextAuth.
- **DB**: PostgreSQL 15, Prisma.
- **Infra**: Docker.

# ARCHITECTURE
- `app/(public)`: Open pages.
- `app/(auth)`: Auth pages.
- `app/(admin)`: Admin routes.
- `app/(dashboard)`: Agent/Customer routes.
- `middleware.ts`: Handles RBAC routing.

# COMMANDS
- Dev: `npm run dev`
- DB Gen: `npm run db:generate`
- DB Push: `npm run db:push`

# AI GUIDELINES (CAVEMAN EFFICIENCY)
- USE FEW TOKENS.
- NO FLUFF. NO GREETINGS.
- DIRECT ANSWERS. 
- BULLETS ONLY.
- ONLY SHOW CHANGED CODE.
- ASSUME DEV EXPERT.
