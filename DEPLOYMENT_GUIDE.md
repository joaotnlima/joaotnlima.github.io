# GitHub Pages Deployment Guide

## Files Ready for Deployment

This folder contains **only the necessary files** for your website:

- ✅ `index.html` - Main website file
- ✅ `favicon.svg` - Browser tab icon
- ✅ `logo-concept5-lettermark.svg` - Navigation logo
- ✅ `photo.jpg` + `photo.webp` - Your photo (optimized)
- ✅ `*.jpeg` - Company logos (Glovo, Dott, Nestlé, Jumia, Rocket Internet, Lazada)

## Deployment Steps

### 1. Create GitHub Repository

```bash
# Option A: New repository named joaotnlima.github.io
# This will make your site available at https://joaotnlima.github.io

# Option B: Any repository name (e.g., "portfolio")
# This will make your site available at https://joaotnlima.github.io/portfolio
```

### 2. Upload Files

Upload all files from this folder to your repository (main branch)

### 3. Enable GitHub Pages

1. Go to repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select: **main branch**
4. Click Save
5. Your site will be live in 1-2 minutes!

### 4. Activate Contact Form (Important!)

The contact form uses **Formspree** (free service):

**First submission activation:**
1. After deploying, visit your website
2. Fill out the contact form and submit it
3. Check your email (**joaotnlima@gmail.com**)
4. Click the **verification link** from Formspree
5. ✅ Form is now active and will send messages to your email!

**Alternative:** Sign up at [formspree.io](https://formspree.io) to get a dashboard and update the form action to `https://formspree.io/f/YOUR_FORM_ID`

## What Works on GitHub Pages

✅ All HTML/CSS/JavaScript
✅ Images and logos
✅ Calendly booking widget
✅ Contact form (via Formspree)
✅ Schema.org SEO
✅ Dark mode
✅ All animations

## Schema.org URLs

If you use a different URL than `https://joaotnlima.github.io`, update these in `index.html`:
- Line ~40: Update all `"@id"` URLs
- Search for `joaotnlima.github.io` and replace with your actual URL

## Need Help?

The website is completely static - no build process, no dependencies, just upload and go!
