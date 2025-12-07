## Chance — Prediction-Native Blockchain (Landing Page)

This repository contains a static landing page for **Chance**, a prediction-native OP Superchain rollup.

### Local preview

From `/Users/andy/ChanceBlockchain`:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### Initial Git setup

```bash
cd /Users/andy/ChanceBlockchain
git init
git add .
git commit -m "Initial commit: Chance landing page"
```

### Create and push to a new GitHub repository

1. Create a new **empty** GitHub repo (no README, no `.gitignore`) from the GitHub UI, e.g. `chance-landing`.
2. Replace the placeholder URL below with your new repo URL:

```bash
git remote add origin git@github.com:YOUR_GITHUB_USERNAME/chance-landing.git
git branch -M main
git push -u origin main
```

### Deploy on Vercel

1. Go to the Vercel dashboard and click **"New Project"**.
2. Import the new GitHub repository you just created.
3. Since this is a static site with only `index.html`, you can:
   - Keep the **Framework Preset** as **"Other"** or **"Static"**.
   - Leave the **Build Command** empty.
   - Set the **Output Directory** to `.`.
4. Click **Deploy**. Vercel will build and give you a live URL.





