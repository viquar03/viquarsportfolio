# Shah Viquar Mohiuddin Quadri — Portfolio

A light-themed, responsive developer portfolio built with HTML5, Tailwind CSS, and Vanilla JavaScript—configured for zero-build deployment on Vercel.

## Project Structure

```text
viquar-portfolio/
├── index.html      # Main portfolio page with animations and 3D tilt cards
├── photo.jpg       # Updated headshot portrait displayed in the hero card
├── vercel.json     # Vercel clean URL configuration
└── README.md       # Git & Vercel deployment guide
```

## Quick Start: Push to Git & Deploy on Vercel

1. **Initialize Git & Push to GitHub/GitLab/Bitbucket:**
   ```bash
   git init
   git add .
   git commit -m "Update portfolio with new blazer headshot"
   git branch -M main
   git remote add origin <YOUR_REPO_URL>
   git push -u origin main
   ```

2. **Host on Vercel:**
   - Log in to [vercel.com](https://vercel.com) and click **Add New → Project**.
   - Import your Git repository.
   - Leave **Framework Preset** as `Other` and **Build Command / Output Directory** empty (static site).
   - Click **Deploy**.
