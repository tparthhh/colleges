# College Compass 🎓

A premium entrance exam portal with comprehensive information about top colleges and entrance exams in India.

## Features

- 🔐 Secure login system
- 🎨 Modern glassmorphism design with Mac-like aesthetics
- 📊 Comprehensive data on 14+ entrance exams
- 🏛️ Information on 50+ top colleges (IITs, NITs, BITS, etc.)
- 💰 Package details, cutoffs, and fees
- 🔍 Search and filter functionality
- 📱 Fully responsive design

## Login Credentials

- **Username:** `parth` or `utkarsh`
- **Password:** `7092008` (DOB format: DDMMYYYY)

## Deployment Instructions for GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Name your repository (e.g., `college-compass`)
5. Make it **Public**
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop the `index.html` file
3. Scroll down and click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Navigate to the folder containing index.html
cd /path/to/your/folder

# Initialize git (if not already done)
git init

# Add the file
git add index.html

# Commit
git commit -m "Initial commit: College Compass portal"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Under **"Branch"**, select **"main"** and **"/ (root)"**
5. Click **"Save"**

### Step 4: Access Your Website

After 1-2 minutes, your site will be live at:

```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

For example: `https://parth123.github.io/college-compass/`

## Quick Start (Summary)

1. Create GitHub repo → Make it public
2. Upload `index.html` file
3. Go to Settings → Pages
4. Select `main` branch → Save
5. Visit `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Custom Domain (Optional)

If you want a custom domain like `collegecompass.com`:

1. Buy a domain from GoDaddy/Namecheap/Google Domains
2. In your domain provider, add these DNS records:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   
   Type: A
   Name: @
   Value: 185.199.109.153
   
   Type: A
   Name: @
   Value: 185.199.110.153
   
   Type: A
   Name: @
   Value: 185.199.111.153
   
   Type: CNAME
   Name: www
   Value: YOUR_USERNAME.github.io
   ```
3. In GitHub Pages settings, enter your custom domain
4. Enable "Enforce HTTPS"

## Updating Your Website

To make changes:

1. Edit `index.html` locally
2. In your GitHub repo, click on `index.html`
3. Click the pencil icon (Edit)
4. Paste your new code
5. Click **"Commit changes"**
6. Your site updates automatically in 1-2 minutes!

## Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after enabling Pages
- Check that your repo is Public
- Ensure the file is named exactly `index.html` (lowercase)
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)

**404 Error?**
- Make sure GitHub Pages is enabled in Settings
- Verify the branch is set to `main`
- Check the URL format: `https://username.github.io/repo-name/`

## Tech Stack

- React 18 (via CDN)
- Tailwind CSS
- Lucide Icons
- Glassmorphism UI
- Babel Standalone (for JSX transformation)

## License

Free to use for personal and educational purposes.

---

Made with ❤️ for aspiring college students
