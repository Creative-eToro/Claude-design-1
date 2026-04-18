# eToro — Copytraders × Crypto landing page

Deploy-ready static site for Vercel.

## Option A — Vercel CLI (fastest)

```bash
npm install -g vercel
cd etoro-landing
vercel          # preview deploy
vercel --prod   # push to production
```

The CLI auto-detects a static site. Accept the defaults on first run.

## Option B — GitHub + Vercel dashboard

1. Create a new GitHub repo and push this folder.
2. Go to https://vercel.com/new and import the repo.
3. Click **Deploy**. Every subsequent `git push` auto-redeploys.

## Option C — Drag & drop

1. Zip this `etoro-landing` folder.
2. Go to https://vercel.com/new → **"Deploy without Git"** → upload.

## Files

- `index.html` — the landing page (single-file, self-contained)
- `vercel.json` — clean URLs + light security headers
