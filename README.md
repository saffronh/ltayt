# Letters to a Young Technologist - GitHub Pages Setup

This is a static website recreation of Letters to a Young Technologist.

## Files Included
- `index.html` - Main page with "About the Essays"
- `what-is-technology.html` - Essay by Saffron Huang
- `value-beyond-instrumentalization.html` - Essay by Jasmine Wang
- `its-time-to-govern.html` - Essay by Anna Gát
- `study-the-past.html` - Essay by Matthew Guay
- `to-be-human.html` - Essay by Tammy Xu

## How to Upload to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon in the top right, select "New repository"
3. Name it something like `letters-to-young-tech` (or any name you prefer)
4. Make it **Public**
5. Do NOT add README, .gitignore, or license (we'll add files manually)
6. Click "Create repository"

### Step 2: Upload Your Files
1. On your new repository page, click **"uploading an existing file"** link
2. Drag and drop ALL the HTML files from your downloads:
   - index.html
   - what-is-technology.html
   - value-beyond-instrumentalization.html
   - its-time-to-govern.html
   - study-the-past.html
   - to-be-human.html
3. Add a commit message like "Initial upload"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click **Settings** (top right)
2. Scroll down to **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** (or master) and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for GitHub to build your site

### Step 4: Visit Your Site
Your site will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

For example: `https://johndoe.github.io/letters-to-young-tech/`

### Step 5: Connect Your Custom Domain (Optional)
1. In GitHub repository Settings → Pages
2. Add your custom domain: `letterstoayoungtechnologist.com`
3. Check "Enforce HTTPS"
4. Go to your domain registrar (where you bought the domain)
5. Add these DNS records:
   - Type: **A Record**
   - Host: **@**
   - Points to: 
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   
   - Type: **CNAME**
   - Host: **www**
   - Points to: **YOUR-USERNAME.github.io**

6. Wait 24-48 hours for DNS to propagate
7. Once propagated, your site will be live at your custom domain!

### Step 6: Cancel Cargo
Once your new site is live and working with your domain, you can cancel your Cargo subscription!

## Troubleshooting
- **Site not loading?** Wait a few more minutes, GitHub Pages can take up to 10 minutes to deploy
- **Links broken?** Make sure all files are in the root directory (not in a subfolder)
- **Custom domain not working?** DNS can take up to 48 hours to propagate globally

## Need Help?
Check out GitHub's official documentation: https://docs.github.com/en/pages
