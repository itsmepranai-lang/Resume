# 🚀 Deploy Your Portfolio to GitHub Pages

## ✅ What's Ready

Your portfolio is now a complete Git repository with:
- ✅ Git initialized (`main` branch)
- ✅ All files committed
- ✅ Professional README.md
- ✅ Clean project structure
- ✅ Deployment scripts

## 📝 Deployment Steps (5 Minutes)

### Step 1: Create GitHub Repository (2 min)

1. **Go to GitHub:** https://github.com/new

2. **Fill in these details:**
   - **Repository name:** `portfolio`
   - **Description:** `Professional portfolio website - Gunapu pranai`
   - **Visibility:** ✅ Public
   - **Initialize:** ❌ DO NOT check any boxes (no README, no .gitignore)

3. **Click:** "Create repository"

### Step 2: Push Your Code (1 min)

Open your terminal and run:

```bash
cd /Users/sambasiva/Documents/personal/resume/resume_siva/website
./push-to-github.sh
```

**OR manually run:**

```bash
cd /Users/sambasiva/Documents/personal/resume/resume_siva/website
git remote add origin https://github.com/samba425/portfolio.git
git push -u origin main
```

### Step 3: Enable GitHub Pages (1 min)

1. Go to your repository: https://github.com/samba425/portfolio

2. Click **"Settings"** tab (top right)

3. Click **"Pages"** in left sidebar

4. Under **"Source":**
   - Branch: Select **"main"**
   - Folder: Select **"/ (root)"**
   
5. Click **"Save"**

### Step 4: Access Your Live Site (1 min)

⏱️ **Wait 1-2 minutes** for GitHub to build your site

🌐 **Your portfolio will be live at:**
```
https://samba425.github.io/portfolio
```

You'll see a green box on the Pages settings page with the URL when it's ready!

## 🎉 You're Done!

Your portfolio is now:
- ✅ Hosted on GitHub Pages (FREE!)
- ✅ Has a professional URL
- ✅ Accessible worldwide
- ✅ Easy to update

## 🔄 How to Update Your Portfolio Later

Whenever you make changes:

```bash
cd /Users/sambasiva/Documents/personal/resume/resume_siva/website
git add .
git commit -m "Update portfolio content"
git push
```

Changes will be live in 1-2 minutes! 🚀

## 📱 Share Your Portfolio

Once live, share your portfolio URL:
- **LinkedIn:** Add to your profile
- **Resume:** Include the link
- **Email Signature:** Add the URL
- **Business Cards:** Print the URL

**Your URL:** https://samba425.github.io/portfolio

## 🛠️ Troubleshooting

**Issue:** Push fails with authentication error
- **Solution:** You may need to set up a GitHub Personal Access Token
- Go to: https://github.com/settings/tokens
- Generate new token (classic)
- Use the token as your password when pushing

**Issue:** 404 error when visiting the site
- **Solution:** Wait 2-3 minutes, GitHub Pages needs time to build
- Check that you selected "main" branch in Pages settings

**Issue:** Site shows old content
- **Solution:** Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)

## 💡 Pro Tips

1. **Custom Domain (Optional):**
   - Buy a domain (e.g., `sambsivarao.com`)
   - Add to GitHub Pages settings
   - Update DNS settings

2. **Analytics:**
   - Add Google Analytics to track visitors
   - Add the tracking code to `index.html`

3. **SEO:**
   - Your site is already SEO optimized
   - Submit to Google Search Console

## 📋 Quick Reference

**Repository URL:** https://github.com/samba425/portfolio
**Live Site:** https://samba425.github.io/portfolio
**Settings:** https://github.com/samba425/portfolio/settings/pages

---

**Need Help?** Check GitHub's documentation: https://docs.github.com/en/pages

**Questions?** Open an issue on your repository or email asiva325@gmail.com

🎊 **Congratulations on deploying your portfolio!** 🎊
