# NEXUS ⊳ nexus.live

**Stream Everything. Earn Fairly.**

The first streaming platform that pays creators **95% forever** and lets them **own their audience**.

- 95/5 tips · 90/10 subs · instant payouts  
- One-click export your entire channel  
- AI clipper · live translation · no gambling ads  
- Built on Supabase + Next.js 15 + Cloudflare Stream

Founder: @WIPcash (age XX, dropping out to build this full-time)

## Quick Start (you’re already here)

```bash
git clone https://github.com/yourusername/nexus-live.git
cd nexus-live
cp .env.example .env.local
# paste your Supabase URL + anon key
npm install
npm run dev# nexus-live
Stream Everything. Earn Fairly. The 95% creator platform.


**.gitignore**
```gitignore
# See https://help.github.com/articles/ignoring-files/ for more about ignoring files.

# dependencies
/node_modules
/.pnp
.pnp.js

# testing
/coverage

# next.js
/.next/
/out/

# production
/build

# misc
.DS_Store
*.pem

# debug
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# local env files
.env*.local
.env

# vercel
.vercel

# typescript
*.tsbuildinfo

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url_here
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key_here
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key  # only on server

STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

GROK_API_KEY=  # for AI moderation

{
  "name": "nexus-live",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@supabase/supabase-js": "^2.45.0",
    "next": "15.0.0-rc.0",
    "react": "^19.0.0-rc-f38c22b244-20240704",
    "react-dom": "^19.0.0-rc-f38c22b244-20240704"
  },
  "devDependencies": {
    "@types/node": "^20",
    "@types/react": "^18",
    "@types/react-dom": "^18",
    "autoprefixer": "^10.0.1",
    "eslint": "^8",
    "eslint-config-next": "15.0.0-rc.0",
    "postcss": "^8",
    "tailwindcss": "^3.4.1",
    "typescript": "^5"
  }
}
