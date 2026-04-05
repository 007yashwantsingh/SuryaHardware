# Surya Enterprises — Building Materials Store

Online store for Surya Enterprises, Siwan, Bihar.

## How to Deploy on GitHub Pages

### Step 1 — Create GitHub Account
Go to [github.com](https://github.com) and create a free account if you don't have one.

### Step 2 — Create a New Repository
- Click the `+` button → **New repository**
- Name it: `surya-enterprises`
- Keep it **Public**
- Click **Create repository**

### Step 3 — Upload the Project Files
Option A (Easiest — via browser):
- In your new repo, click **uploading an existing file**
- Drag and drop ALL the project files (keeping the folder structure)
- Click **Commit changes**

Option B (via Git on your computer):
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/surya-enterprises.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under **Source**, select **GitHub Actions**
- Save

### Step 5 — Done!
GitHub will automatically build and deploy your site.
Your website will be live at:
```
https://YOUR_USERNAME.github.io/surya-enterprises/
```

### Updating the Site
Any time you push changes to the `main` branch, the site automatically rebuilds and deploys within 2-3 minutes.

---

## Admin Panel
- Scroll to the footer → click **Admin**
- Password: `Surya@2024`

## Tech Stack
- React 18 + Vite
- localStorage for data persistence
- WhatsApp API for orders
