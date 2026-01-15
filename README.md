# FactoryConnect PWA - Setup Instructions

## What's Included
```
pwa-app/
├── index.html      (Main app)
├── manifest.json   (PWA configuration)
├── sw.js          (Service worker for offline)
├── icon-192.png   (App icon small)
├── icon-512.png   (App icon large)
└── README.md      (This file)
```

---

## STEP 1: Upload Files to Free Hosting

You need to host these files online. Here are 3 easy options:

### Option A: GitHub Pages (Recommended - Free Forever)

1. Go to https://github.com and create an account (or login)
2. Click "New Repository" (green button)
3. Name it: `factory-app`
4. Keep it Public
5. Click "Create Repository"
6. Click "uploading an existing file"
7. Drag and drop ALL files from the pwa-app folder
8. Click "Commit changes"
9. Go to Settings → Pages
10. Under "Source" select "main" branch
11. Click Save
12. Wait 2 minutes, your app will be live at:
    `https://YOUR-USERNAME.github.io/factory-app`

### Option B: Netlify (Easiest - Drag & Drop)

1. Go to https://netlify.com
2. Sign up for free
3. Drag and drop the entire `pwa-app` folder onto the page
4. Done! You'll get a link like: `https://random-name.netlify.app`

### Option C: Vercel (Also Easy)

1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your GitHub repo (if you used Option A)
4. Or drag and drop files
5. Get your link

---

## STEP 2: Open on Your Phone

1. Open Chrome (Android) or Safari (iPhone) on your phone
2. Go to your app URL (from Step 1)
3. The app will load in the browser

---

## STEP 3: Install as App on Phone

### For Android (Chrome):

1. Open the app URL in Chrome
2. Tap the 3-dot menu (⋮) in top-right
3. Tap "Add to Home Screen" or "Install App"
4. Tap "Install"
5. The app icon will appear on your home screen!

### For iPhone (Safari):

1. Open the app URL in Safari
2. Tap the Share button (□↑) at bottom
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. The app icon will appear on your home screen!

---

## STEP 4: Test the App

1. Tap the app icon on your home screen
2. It will open like a real app (no browser bar!)
3. Test all features:
   - Swipe through cards
   - Tap filter tabs (All/Pending/Done)
   - Tap hamburger menu (☰)
   - Tap voice notes icon (🎤)
   - Tap on product photos
   - Check settings

---

## Troubleshooting

**App not installing?**
- Make sure you're using Chrome (Android) or Safari (iPhone)
- The URL must be HTTPS (not HTTP)

**Changes not showing?**
- Clear browser cache
- Or open in Incognito/Private mode

**Icons not showing?**
- Wait a few minutes after uploading
- Clear browser cache

---

## Next Steps

Once you've tested and finalized the UI:
1. We'll connect it to Google Sheets
2. Add real login with Google
3. Make it fully functional
4. Optionally convert to Play Store APK

---

## Need Help?

If you get stuck at any step, just ask!
