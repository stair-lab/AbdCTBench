# AbdCTBench Website

This repository contains the GitHub Pages website for AbdCTBench, a dataset and benchmark for learning clinical biomarker representations from abdominal surface geometry.

## Setup Instructions

### 1. Create a Private GitHub Repository

1. Go to GitHub and create a new repository (e.g., `AbdCTBench-website`)
2. **Make it private** to comply with double-blind review policy
3. Add collaborators who need access

### 2. Initialize and Push to GitHub

```bash
cd AbdCTBench-website
git init
git add .
git commit -m "Initial commit: AbdCTBench website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/AbdCTBench-website.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Pages** (under Settings)
3. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **Save**

### 4. Access Your Site

- Your site will be available at: `https://YOUR_USERNAME.github.io/AbdCTBench-website/`
- **Note**: For private repositories, GitHub Pages sites are only accessible to:
  - Repository collaborators
  - Organization members (if in an org)
  - You can also use GitHub's private repository access controls

### 5. Custom Domain (Optional)

If you want to use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings as per GitHub Pages documentation

## File Structure

```
AbdCTBench-website/
├── index.html          # Main website page
├── styles.css          # CSS styling
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Double-Blind Review Compliance

This website is designed to comply with double-blind review policies:

- ✅ No author names or affiliations
- ✅ No identifying information
- ✅ Anonymous citation format
- ✅ Private repository (not publicly accessible)
- ✅ Only accessible to collaborators

## Updating the Website

After making changes:

```bash
git add .
git commit -m "Update website content"
git push
```

GitHub Pages will automatically rebuild the site (usually within a few minutes).

## After Paper Acceptance

Once the paper is accepted:

1. Update the citation section with actual author information
2. Make the repository public (if desired)
3. Update any placeholder text
4. Add links to the paper, code repository, and dataset download

## Notes

- The website uses vanilla HTML/CSS/JavaScript (no build process required)
- All styling is in `styles.css`
- Interactive features are in `script.js`
- The site is fully responsive and works on mobile devices

## License

This website is part of the AbdCTBench project. See the main paper repository for licensing information.

