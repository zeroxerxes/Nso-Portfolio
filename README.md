## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended)
1. **Push to GitHub** (using commands above)
2. **Go to your repository on GitHub**
3. **Click Settings → Pages**
4. **Under Source, select "Deploy from a branch"**
5. **Choose "main" branch and "/ (root)" folder**
6. **Click Save**

Your website will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Netlify (Alternative)
1. **Push to GitHub first**
2. **Go to netlify.com**
3. **Click "New site from Git"**
4. **Connect your GitHub account**
5. **Select your repository**
6. **Deploy settings: Branch: main, Build command: (leave empty), Publish directory: (leave empty)**
7. **Click "Deploy site"**

### Option 3: Vercel (Another Alternative)
1. **Push to GitHub first**
2. **Go to vercel.com**
3. **Import your GitHub repository**
4. **Deploy with default settings**

## 🌟 Bernice Enang Nso Keshu - Portfolio Website

Professional portfolio website for ENANG nee NSO BERNICE KESHU, featuring Benk Assist Consultancy and First Housebond Foundation (FIHOF).

## 🚀 Quick Setup Guide

### 1. Google Analytics Setup
1. Go to [Google Analytics](https://analytics.google.com/)
2. Create a new property for your website
3. Copy your **Measurement ID** (format: `G-XXXXXXXXXX`)
4. **Replace `G-XXXXXXXXXX`** in `index.html` (lines 7 & 12) with your actual ID

### 2. Contact Form Backend Setup
1. Go to [Formspree.io](https://formspree.io/)
2. Create a free account
3. Create a new form
4. Copy your **Form ID** (format: `xleqrgyo` or similar)
5. **Replace `YOUR_FORM_ID`** in `index.html` (line 1239 & 1333) with your actual Form ID

### 3. Deploy to GitHub Pages
1. **Push to GitHub** (see commands below)
2. **Enable Pages**: Settings → Pages → Deploy from main branch
3. **Your site will be live at**: `https://yourusername.github.io/repo-name/`

## 🔧 Development Commands

```bash
# Add all changes
git add .

# Commit with message
git commit -m "Your message here"

# Push to GitHub
git push origin main
```

## 📊 Features Included

- ✅ **Responsive Design** - Works on all devices
- ✅ **Contact Form** - Integrated with Formspree backend
- ✅ **Google Analytics Ready** - Just add your tracking ID
- ✅ **Professional Layout** - Clean, modern design
- ✅ **SEO Optimized** - Proper meta tags and structure
- ✅ **Fast Loading** - Optimized images and code

## 📁 File Structure
```
nso2/
├── index.html          # Main website with analytics & form backend
├── Assets/             # Profile images and media files
│   ├── Profile.jpg
│   └── my pic.jpg
├── README.md          # This setup guide
└── .gitignore         # Git ignore rules
```

## 🔄 Keeping Your Site Updated

After making changes to your website:

```bash
# Stage all changes
git add .

# Commit with a descriptive message
git commit -m "Update: Added new services section"

# Push to GitHub
git push origin main
```

Your live website will automatically update if using GitHub Pages, Netlify, or Vercel!

## 🌐 Live Website URL
Once deployed, share your website:
- **GitHub Pages**: `https://yourusername.github.io/repo-name/`
- **Netlify**: Provided when you deploy
- **Vercel**: Provided when you deploy
