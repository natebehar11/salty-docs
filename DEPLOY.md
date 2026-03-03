# Deploy SALTY Docs to Vercel

## Option A: Deploy via Vercel Dashboard (recommended)

1. **Create a GitHub repo**  
   - Go to github.com → New repository  
   - Name it `salty-docs` (or similar)  
   - Don't initialize with README (you already have files)

2. **Push this folder to GitHub**
   ```bash
   cd /Users/nathanielbehar/Desktop/Claude/salty-docs
   git add .
   git commit -m "SALTY Docs - EU Strategy + Meta Ads presentations"
   git remote add origin https://github.com/YOUR_USERNAME/salty-docs.git
   git branch -M main
   git push -u origin main
   ```

3. **Import to Vercel**
   - Go to [vercel.com](https://vercel.com) and sign in
   - Click **Add New** → **Project**
   - Import your `salty-docs` repository
   - Framework Preset: **Other** (static HTML)
   - Click **Deploy**

4. **Live URL**  
   You’ll get a URL like `salty-docs.vercel.app`.

---

## Option B: Deploy via Vercel CLI

```bash
cd /Users/nathanielbehar/Desktop/Claude/salty-docs
npx vercel
```

Follow the prompts (login if needed, confirm project name).  
For production: `npx vercel --prod`
