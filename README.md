# M's Lifestyle – Gamified Life OS

Futuristic, iOS 26–inspired life operating system that combines deep productivity tooling with a AAA-style gamification engine.

## Tech stack

- Next.js (App Router) + TypeScript
- Tailwind CSS + Framer Motion
- Supabase (Postgres, Auth, Storage)
- TanStack Query

## Getting started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a `.env.local` in the project root:

   ```bash
   NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

3. In your Supabase project, run the SQL in `supabase/schema.sql` to create the database tables and policies.

4. Run the dev server:

   ```bash
   npm run dev
   ```

## GitHub & deployment

- Commit this folder (`ms-lifestyle`) into a new GitHub repository.
- Deploy easily to a platform like Vercel by connecting the repo and setting the `NEXT_PUBLIC_SUPABASE_*` environment variables.
- Use `npm run lint` and `npm run build` locally before pushing to catch issues early.

