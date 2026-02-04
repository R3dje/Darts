# 🎯 Darts Battle - iPhone App Installation Guide

## How to Install on iPhone

Your Darts Battle app is now a Progressive Web App (PWA) that can be installed on your iPhone like a native app!

### Installation Steps:

1. **Deploy to GitHub Pages** (or any web server):
   - Go to your GitHub repository settings
   - Navigate to "Pages" section
   - Select your branch (e.g., `feature/darts-updates` or `main`)
   - Save and wait for deployment

2. **Open in Safari on your iPhone**:
   - Open Safari browser (must use Safari, not Chrome)
   - Navigate to your GitHub Pages URL (e.g., `https://r3dje.github.io/Darts/darts.html`)

3. **Add to Home Screen**:
   - Tap the Share button (square with arrow pointing up)
   - Scroll down and tap "Add to Home Screen"
   - Edit the name if you want (default: "Darts Battle")
   - Tap "Add" in the top right

4. **Launch the App**:
   - Find the Darts Battle icon on your home screen
   - Tap to open - it will run in full-screen mode like a native app!

## Features

✅ Works offline after first load
✅ Full-screen experience (no browser UI)
✅ Optimized for touch/mobile use
✅ Large touch targets for easy scoring
✅ Number pad for quick input
✅ Player selection before each match

## Creating App Icons

You need to create two icon files:
- `icon-192.png` (192x192 pixels)
- `icon-512.png` (512x512 pixels)

### Quick Icon Creation Options:

**Option 1: Use an online tool**
- Go to https://www.favicon-generator.org/
- Upload a dart emoji or dart image
- Download the generated icons
- Rename them to `icon-192.png` and `icon-512.png`

**Option 2: Use Canva (free)**
- Create a 512x512px design
- Add a dart emoji 🎯 or design
- Use dark background (#1a1a1a) with yellow accent (#ffcc00)
- Export as PNG
- Resize to 192x192 for the smaller icon

**Option 3: Simple emoji icon**
- Take a screenshot of the 🎯 emoji on a dark background
- Crop to square
- Resize to 512x512 and 192x192

## Files Created

- `manifest.json` - PWA configuration
- `service-worker.js` - Enables offline functionality
- `darts.html` - Updated with PWA meta tags
- `README.md` - This file

## Troubleshooting

**App not installing?**
- Make sure you're using Safari (not Chrome or other browsers)
- Check that all files are deployed to your web server
- Ensure icons exist (icon-192.png and icon-512.png)

**App not working offline?**
- Open the app once while online to cache files
- Check browser console for service worker errors

**Need to update the app?**
- Delete the app from home screen
- Clear Safari cache
- Reinstall following the steps above