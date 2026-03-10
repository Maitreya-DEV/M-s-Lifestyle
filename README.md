<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>M's Lifestyle – Gamified Life OS</title>
  </head>
  <body>
    <main>
      <section id="hero">
        <h1>M's Lifestyle – Gamified Life OS</h1>
        <p>
          Futuristic, iOS 26–inspired life operating system that combines deep productivity tooling
          with a AAA-style gamification engine.
        </p>
      </section>

      <section id="tech-stack">
        <h2>Tech stack</h2>
        <ul>
          <li>Next.js (App Router) + TypeScript</li>
          <li>Tailwind CSS + Framer Motion</li>
          <li>Supabase (Postgres, Auth, Storage)</li>
          <li>TanStack Query</li>
        </ul>
      </section>

      <section id="getting-started">
        <h2>Getting started</h2>
        <ol>
          <li><code>npm install</code></li>
          <li>
            Create a <code>.env.local</code> file and add:
            <pre>
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
            </pre>
          </li>
          <li>Run the SQL in <code>supabase/schema.sql</code> inside your Supabase project.</li>
          <li>Start the dev server with <code>npm run dev</code>.</li>
        </ol>
      </section>

      <section id="github-deploy">
        <h2>GitHub &amp; deployment</h2>
        <ul>
          <li>Commit the <code>ms-lifestyle</code> folder to a new GitHub repository.</li>
          <li>
            Deploy to a platform like Vercel and configure the
            <code>NEXT_PUBLIC_SUPABASE_*</code> environment variables.
          </li>
          <li>
            Run <code>npm run lint</code> and <code>npm run build</code> locally before pushing.
          </li>
        </ul>
      </section>

      <section id="command-center">
        <header>
          <h2>Command Center</h2>
          <p>Your executive dashboard for XP, streaks, and focus.</p>
        </header>
        <div class="neural-stat-ring"></div>
        <aside class="xp-feed">
          <h3>Live XP Feed</h3>
          <ul>
            <li>+50 XP: Read for 20 mins</li>
            <li>+30 XP: Hydration streak</li>
          </ul>
        </aside>
        <section class="focus-widgets">
          <article class="widget current-goal">
            <h4>Current Goal</h4>
            <p>Finish Deep Work block.</p>
          </article>
          <article class="widget active-streak">
            <h4>Active Streak</h4>
            <p>7 days in a row.</p>
          </article>
        </section>
      </section>

      <section id="task-matrix">
        <header>
          <h2>Task &amp; Habit Matrix</h2>
        </header>
        <div class="task-grid">
          <article class="task-card" data-difficulty="easy">
            <h3>Read 20 minutes</h3>
            <span class="badge">Easy</span>
            <button>Complete</button>
          </article>
          <article class="task-card" data-difficulty="legendary">
            <h3>Launch side project</h3>
            <span class="badge badge-legendary">Legendary</span>
            <button>Complete</button>
          </article>
        </div>
        <div class="habit-heatmap">
          <h3>Habit Heatmap (30 days)</h3>
        </div>
      </section>
    </main>
  </body>
</html>
