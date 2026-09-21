# 🚀 GitHub Setup Instructions for CPCA

This guide walks you through publishing the Cross-Media Pop Culture Archive to GitHub and enabling GitHub Pages.

---

## Step 1: Create a New Repository on GitHub

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** `video-game-culture` (or similar)
3. **Description:** "Cross-Media Pop Culture Archive - Mapping video games through books, essays, interviews, and art"
4. **Public:** Yes (to allow anyone to visit)
5. **Initialize with:** Leave unchecked (we already have files locally)
6. Click **Create repository**

---

## Step 2: Add GitHub Remote and Push

Once the repository is created, you'll see push instructions. Run these commands in your terminal from the project root:

```bash
# Add GitHub as remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/video-game-culture.git

# Rename branch to main if needed
git branch -M main

# Push all commits
git push -u origin main
```

**Alternative (if using SSH):**
```bash
git remote add origin git@github.com:USERNAME/video-game-culture.git
git branch -M main
git push -u origin main
```

---

## Step 3: Enable GitHub Pages

1. On GitHub, go to your repository
2. Click **Settings** (top right)
3. In the left sidebar, click **Pages**
4. Under "Build and deployment":
   - **Source:** Select "GitHub Actions"
   - This will automatically use the workflow we created in `.github/workflows/deploy.yml`
5. Click **Save**

The site will now build and deploy automatically whenever you push to `main`.

---

## Step 4: Access Your Live Site

After the GitHub Actions workflow completes (usually within 1-2 minutes):

- Your site will be live at: `https://USERNAME.github.io/video-game-culture/`
- You can find the exact URL in **Settings > Pages** under "Your site is live at..."

---

## Step 5: View Deployment Status

1. Go to your repository
2. Click **Actions** (top menu)
3. You'll see the deployment workflow run in real-time
4. Once it shows a ✅ green checkmark, your site is live

---

## Troubleshooting

### If the build fails:
- Check the **Actions** tab to see error logs
- Ensure all `.md` files in `content/` are valid Markdown
- Verify the workflow file is at `.github/workflows/deploy.yml`

### If the site doesn't update:
- Clear your browser cache (Ctrl+Shift+Delete)
- Wait 5-10 minutes for GitHub to fully propagate the changes
- Check the Actions tab to confirm the latest push built successfully

---

## Making Updates

After setup, updating is simple:

```bash
# Create or edit a new game card
# (e.g., content/games/my-game.md)

# Commit and push
git add content/games/my-game.md
git commit -m "Add My Game card"
git push
```

The site will rebuild automatically within 1-2 minutes!

---

## Repository Structure (Reference)

```
.
├── README.md                          # Project overview
├── TEMPLATE.md                        # Template for new game cards
├── GITHUB_SETUP.md                    # This file
├── content/
│   ├── index.md                       # Home page
│   └── games/
│       ├── castlevania-aria-of-sorrow.md
│       └── ... (add more games here)
├── quartz-setup/                      # Quartz static site generator
│   ├── content/                       # Links to ../content
│   ├── quartz/                        # Quartz configuration
│   ├── package.json
│   └── public/                        # Generated static site (in .gitignore)
├── .github/
│   └── workflows/
│       └── deploy.yml                 # Auto-deployment workflow
└── .gitignore                         # Git ignore rules
```

---

**Ready to go live?** Follow Steps 1-5 above, and your CPCA will be online! 🎮📚

