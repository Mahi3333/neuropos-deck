# 🚀 **NeuroPOS Deck Deployment Guide**

## **Complete Step-by-Step Setup for GitHub Pages + Custom Domain**

### **Phase 1: GitHub Repository Setup**

#### **Step 1: Create GitHub Account**
1. Go to [github.com](https://github.com)
2. Click **"Sign up"**
3. Use your email: `mumamahesh13@gmail.com`
4. Choose username (suggest: `umamahesh` or `neuropos-founder`)
5. Complete verification

#### **Step 2: Create New Repository**
1. Click **"New repository"** (green button)
2. **Repository name:** `neuropos-deck`
3. **Description:** `AI-Powered Restaurant POS System - Investor Deck`
4. Make it **Public** ✅
5. ✅ Check "Add a README file"
6. Click **"Create repository"**

#### **Step 3: Upload Your Files**
1. In your new repository, click **"Add file"** → **"Upload files"**
2. **Drag and drop these files:**
   - `index.html` (your stunning deck)
   - `README.md` (professional description)
   - `CNAME` (custom domain config)
   - `404.html` (custom error page)
   - `.github/workflows/deploy.yml` (auto-deployment)
   - `package.json` (project metadata)
3. **Commit message:** `Add stunning investor deck and deployment files`
4. Click **"Commit changes"**

### **Phase 2: Enable GitHub Pages**

#### **Step 4: Enable Pages**
1. Go to **Settings** tab in your repository
2. Click **"Pages"** in left sidebar
3. **Source:** Select "GitHub Actions"
4. Click **"Save"**

#### **Step 5: Test GitHub Pages**
1. Wait 2-3 minutes for deployment
2. Your deck will be live at: `https://yourusername.github.io/neuropos-deck`
3. **Test it** - make sure everything works!

### **Phase 3: Custom Domain Setup**

#### **Step 6: Buy Domain (Recommended)**
**Best Options:**
- **neuropos.com** (~$10-15/year) - **RECOMMENDED**
- **neuropos.tech** (~$15-20/year)
- **neuropos.ai** (~$30-40/year)

**Where to Buy:**
1. **Namecheap** - [namecheap.com](https://namecheap.com) - Best prices
2. **Google Domains** - [domains.google](https://domains.google) - Clean interface
3. **GoDaddy** - [godaddy.com](https://godaddy.com) - Popular choice

#### **Step 7: Configure DNS Records**
**In your domain registrar's DNS settings, add these records:**

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
Value: yourusername.github.io
```

#### **Step 8: Add Custom Domain to GitHub**
1. Go back to **Settings** → **Pages**
2. In **Custom domain** field, enter your domain (e.g., `neuropos.com`)
3. ✅ Check "Enforce HTTPS"
4. Click **"Save"**

#### **Step 9: Verify Domain**
1. Go to your repository
2. Click **"Add file"** → **"Create new file"**
3. **File name:** `CNAME`
4. **Content:** `neuropos.com` (or your chosen domain)
5. Click **"Commit new file"**

### **Phase 4: Final Configuration**

#### **Step 10: Update README Links**
1. Edit `README.md`
2. Replace `https://neuropos.com` with your actual domain
3. Commit changes

#### **Step 11: Test Everything**
1. **Main URL:** `https://neuropos.com` (or your domain)
2. **www version:** `https://www.neuropos.com`
3. **HTTPS:** Should work automatically
4. **Mobile:** Test on phone

## 🎯 **Final Result:**
Your stunning deck will be live at: **`https://neuropos.com`** (or your chosen domain)

## 📱 **Share Your Professional Deck:**
- **Investors:** `https://neuropos.com`
- **LinkedIn:** Include in your profile
- **Resume:** Add as portfolio link
- **Meetings:** Show during presentations

## ⚠️ **Important Notes:**
- **DNS propagation** takes 24-48 hours
- **HTTPS** will work automatically
- **www** and non-www both work
- **GitHub Pages** is free forever

## 🆘 **Troubleshooting:**
- **Domain not working:** Wait 24-48 hours for DNS
- **HTTPS issues:** Check "Enforce HTTPS" is enabled
- **404 errors:** Make sure `CNAME` file exists
- **Deployment issues:** Check Actions tab for errors

## 🎉 **Congratulations!**
You now have a **professional, hosted investor deck** that will impress everyone!

---

**Need help?** Check the GitHub Actions tab for deployment status, or contact GitHub support.

**Your deck URL:** `https://neuropos.com` 🚀
