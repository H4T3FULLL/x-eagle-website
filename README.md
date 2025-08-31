# X Eagle Esports Website (Next.js + Tailwind + MySQL + Markdown CMS)

## Setup
```bash
npm install
cp .env.example .env
# edit .env with DB and FORM_ENDPOINT
npm run dev
```

Deploy on Vercel: push to GitHub → Import on vercel.com → add env vars → deploy.

News: add markdown files under `content/news/` with front matter.
Matches: uses MySQL `matches` table from your schema.
