# Quick Setup Guide

## Step-by-Step Instructions

### 1. Create Private GitHub Repository

1. Go to https://github.com/new
2. Repository name: `AbdCTBench-website` (or your preferred name)
3. **Set to Private** (important for double-blind review)
4. **Do NOT** initialize with README, .gitignore, or license
5. Click "Create repository"

### 2. Initialize Local Repository

Open terminal in the `AbdCTBench-website` directory and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Make initial commit
git commit -m "Initial commit: AbdCTBench website for ICLR 2026"

# Rename branch to main (if needed)
git branch -M main

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/AbdCTBench-website.git

# Push to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under **Source**:
   - Select **Branch**: `main`
   - Select **Folder**: `/ (root)`
5. Click **Save**

### 4. Access Your Site

- Your site will be available at: `https://YOUR_USERNAME.github.io/AbdCTBench-website/`
- **Note**: For private repos, only collaborators can access the site
- It may take a few minutes for the site to be available after first push

### 5. Add Collaborators (Optional)

1. Go to repository **Settings**
2. Click **Collaborators** (left sidebar)
3. Click **Add people**
4. Enter GitHub usernames or emails
5. They will receive an invitation

## Double-Blind Review Compliance ✅

The website is designed to be compliant:
- ✅ No author names or affiliations
- ✅ Anonymous citation format
- ✅ Private repository
- ✅ Only accessible to collaborators

## Testing Locally

You can test the website locally before pushing:

```bash
# Using Python 3
python3 -m http.server 8000

# Or using Node.js (if you have it)
npx http-server

# Then open http://localhost:8000 in your browser
```

## After Paper Acceptance

When the paper is accepted, you can:
1. Update citation with actual author information
2. Make repository public (optional)
3. Update any placeholder text
4. Add links to paper, code, and dataset

## Troubleshooting

**Site not loading?**
- Wait 5-10 minutes after first push
- Check repository Settings > Pages to ensure it's enabled
- Verify branch is set to `main` and folder to `/ (root)`

**Changes not showing?**
- GitHub Pages rebuilds automatically on push
- Hard refresh browser (Ctrl+F5 or Cmd+Shift+R)
- Check if build is in progress in repository Actions tab

**Need to update content?**
- Edit files locally
- Commit and push: `git add . && git commit -m "Update content" && git push`

