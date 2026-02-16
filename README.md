# Avenue Saint Charles - GitHub Pages Website

A modern, vibrant website for Avenue Saint Charles restaurant featuring authentic New Orleans cuisine in Beaverton, Oregon.

## 📦 Complete File List

Your website includes:
- `index.html` - Homepage with hero, about, menu preview, and location
- `menu.html` - Menu page with food gallery
- `location.html` - Location page with map, hours, and directions
- `CNAME` - Custom domain configuration
- `README.md` - This file

## 🖼️ Images You Need to Download

Before taking down your WordPress site, download these images and add them to your GitHub repository:

### Image Download URLs:

1. **Chef/Owner Photo (About page):**
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/68254833_10101323097943243_5537691279661465600_n.jpg
   ```
   Save as: `chef-tyler.jpg`

2. **Menu Image:**
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/minimenu-07.heic
   ```
   Save as: `menu-image.jpg` (convert from HEIC to JPG first using cloudconvert.com or iPhone export)

3. **Food Gallery Photos:**
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0642-1024x685.jpg
   ```
   Save as: `food-1.jpg`
   
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0488-1024x685.jpg
   ```
   Save as: `food-2.jpg`
   
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0453-1024x685.jpg
   ```
   Save as: `food-3.jpg`
   
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0328-1024x685.jpg
   ```
   Save as: `food-4.jpg`
   
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0282-1024x685.jpg
   ```
   Save as: `food-5.jpg`
   
   ```
   https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0241-1024x685.jpg
   ```
   Save as: `food-6.jpg`

### How to Download Images:

**Option 1: Manual Download (Easiest)**
1. Copy each URL above
2. Paste into your browser
3. Right-click the image and "Save Image As..."
4. Save with the suggested filename

**Option 2: Bulk Download Script**
Copy and paste this into your terminal (Mac/Linux):
```bash
curl -o chef-tyler.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/68254833_10101323097943243_5537691279661465600_n.jpg"
curl -o food-1.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0642-1024x685.jpg"
curl -o food-2.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0488-1024x685.jpg"
curl -o food-3.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0453-1024x685.jpg"
curl -o food-4.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0328-1024x685.jpg"
curl -o food-5.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0282-1024x685.jpg"
curl -o food-6.jpg "https://www.avenuesaintcharles.com/wp-content/uploads/2023/11/DSC_0241-1024x685.jpg"
```

## 🚀 Quick Start Deployment

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `avenuesaintcharles`
3. Make it **Public**
4. Click "Create repository"

### Step 2: Upload All Files

**Via GitHub Web Interface (Recommended):**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop: `index.html`, `menu.html`, `location.html`, `CNAME`, `README.md`
3. Click "Commit changes"
4. Click "Add file" → "Create new file"
5. Name it: `images/placeholder.txt` (just type "placeholder" inside)
6. Commit
7. Go into the `images` folder
8. Click "Add file" → "Upload files"
9. Upload all your downloaded images
10. Commit

### Step 3: Enable GitHub Pages

1. Go to **Settings** → **Pages** (left sidebar)
2. Under "Source", select **"Deploy from a branch"**
3. Branch: **main**, Folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes
6. Your site is live at: `https://YOUR_USERNAME.github.io/avenuesaintcharles/`

### Step 4: Connect Your Domain

1. **In your domain registrar** (where you bought avenuesaintcharles.com):
   
   Delete old WordPress DNS records, then add:
   - Type: `A` | Name: `@` | Value: `185.199.108.153`
   - Type: `A` | Name: `@` | Value: `185.199.109.153`
   - Type: `A` | Name: `@` | Value: `185.199.110.153`
   - Type: `A` | Name: `@` | Value: `185.199.111.153`
   - Type: `CNAME` | Name: `www` | Value: `YOUR_USERNAME.github.io`

2. **In GitHub** (Settings → Pages):
   - Custom domain: `www.avenuesaintcharles.com`
   - Save
   - Wait 24 hours for DNS
   - Enable "Enforce HTTPS"

## 📂 Final File Structure

```
avenuesaintcharles/
├── index.html
├── menu.html
├── location.html
├── CNAME
├── README.md
└── images/
    ├── chef-tyler.jpg
    ├── menu-image.jpg
    ├── food-1.jpg
    ├── food-2.jpg
    ├── food-3.jpg
    ├── food-4.jpg
    ├── food-5.jpg
    └── food-6.jpg
```

## ✏️ How to Edit Your Site

**Edit on GitHub (no coding needed):**
1. Go to your repository
2. Click the file (e.g., `location.html`)
3. Click pencil icon ✏️
4. Make changes
5. Scroll down, click "Commit changes"
6. Live in ~1 minute!

**Common edits:**
- **Update hours**: Edit `location.html`, find the hours section
- **Change menu**: Replace `images/menu-image.jpg` with new image
- **Update story**: Edit `index.html`, find the about section
- **Add photos**: Upload to `images/` folder, update `menu.html` image paths

## 🎨 Website Features

- ✅ Mardi Gras color scheme (gold, purple, green)
- ✅ Clean Oswald/Arial typography
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth scroll navigation
- ✅ Embedded Google Maps
- ✅ Yelp & Instagram integration
- ✅ Hours and location info

## 🔗 Your Links

- **Yelp**: https://www.yelp.com/biz/avenue-saint-charles-beaverton-3
- **Instagram**: https://www.instagram.com/avenuesaintcharles/
- **Location**: BG Food Cartel, 4250 SW Rose Biggi Ave, Beaverton, OR 97005

## 🆘 Troubleshooting

**Images not showing?**
- Check filenames match exactly (case-sensitive!)
- Images must be in `images/` folder
- Convert HEIC to JPG

**Domain not working?**
- Wait 24-48 hours for DNS
- Check DNS records are exactly as shown above
- CNAME file must contain only: `www.avenuesaintcharles.com`

**Changes not appearing?**
- Wait 1-2 minutes after commit
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

## 📞 Business Info

- **Address**: 4250 SW Rose Biggi Ave, Beaverton, OR 97005
- **Hours**: 
  - Monday-Tuesday: Closed
  - Wednesday-Thursday: 12:00 PM - 7:00 PM
  - Friday-Saturday: 12:00 PM - 8:00 PM
  - Sunday: 12:00 PM - 8:00 PM

---

© 2026 Avenue Saint Charles - Bringing New Orleans to Oregon ⚜
