# GME BIZ Development Status

## Deploy to Vercel

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd vercel-deploy
vercel --prod
```

### Option B — GitHub + Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new
3. Import your repo
4. Settings:
   - Framework: **Other**
   - Build Command: *(leave empty)*
   - Output Directory: `.` *(enable Override)*
5. Click **Deploy**

## Update the site
Just push changes to GitHub → Vercel auto-deploys.
