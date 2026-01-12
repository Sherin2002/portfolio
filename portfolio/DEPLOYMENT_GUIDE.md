# How to Publish Your Portfolio on GitHub Pages

Follow these steps to create a Git repository and publish your portfolio online.

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Create your account

## Step 2: Create a New Repository on GitHub

1. Log in to GitHub
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `portfolio` (or any name you prefer)
5. Description: "My UI/UX Designer Portfolio"
6. Make it **Public** (required for free GitHub Pages)
7. **DO NOT** check "Initialize with README" (we'll add files locally)
8. Click "Create repository"

## Step 3: Install Git (if not already installed)

### For Windows:
1. Download Git from: https://git-scm.com/download/win
2. Install with default settings
3. Open Git Bash or PowerShell

### Check if Git is installed:
```bash
git --version
```

## Step 4: Initialize Git in Your Portfolio Folder

Open your terminal/command prompt in your portfolio folder and run:

```bash
# Navigate to your portfolio folder (if not already there)
cd C:\Users\User\Desktop\portfolio

# Initialize Git repository
git init

# Add all your files
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

**Note:** When you push, GitHub will ask for your username and password. Use a **Personal Access Token** instead of your password:
- Go to GitHub Settings > Developer settings > Personal access tokens > Tokens (classic)
- Generate new token with "repo" permissions
- Use this token as your password

## Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch
6. Select "/ (root)" folder
7. Click "Save"

## Step 6: Access Your Live Portfolio

After a few minutes, your portfolio will be live at:
```
https://YOUR_USERNAME.github.io/portfolio
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Quick Command Reference

```bash
# Check status
git status

# Add files
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push

# Pull latest changes
git pull
```

## Troubleshooting

### If you get authentication errors:
- Use Personal Access Token instead of password
- Or use GitHub Desktop app (easier for beginners)

### If pages don't load:
- Wait 5-10 minutes for GitHub to build
- Check repository Settings > Pages to ensure it's enabled
- Make sure your repository is Public

### If you need to update your portfolio:
```bash
git add .
git commit -m "Updated portfolio"
git push
```

## Alternative: Use GitHub Desktop (Easier Method)

1. Download GitHub Desktop: https://desktop.github.com/
2. Sign in with your GitHub account
3. Click "File" > "Add Local Repository"
4. Select your portfolio folder
5. Click "Publish repository"
6. Enable GitHub Pages in repository settings on GitHub website

---

**Your portfolio link for CV:**
`https://YOUR_USERNAME.github.io/portfolio`
