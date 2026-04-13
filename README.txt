FELLOW WIZARD LORDS — PWA Setup Instructions
=============================================

WHAT YOU NEED:
A simple web server to host these files. Free options:

OPTION 1: GitHub Pages (FREE, recommended)
------------------------------------------
1. Create a free account at github.com
2. Create a new repository called "fwl" (make it Public)
3. Upload ALL files from this zip to the repository
4. Go to Settings → Pages → Source: "Deploy from branch" → branch: main → Save
5. Your app will be live at: https://[yourusername].github.io/fwl
6. Open that URL in Safari on your iPhone
7. Tap Share → "Add to Home Screen" → Add
8. Done! The FWL icon appears on your iPhone homescreen.

OPTION 2: Netlify Drop (FREE, easiest)
---------------------------------------
1. Go to app.netlify.com/drop
2. Drag the entire unzipped folder onto the page
3. Netlify gives you a URL instantly (e.g. https://amazing-name-123.netlify.app)
4. Open that URL in Safari on your iPhone
5. Tap Share → "Add to Home Screen" → Add
6. Done!

IMPORTANT — iOS Safari tips:
- Must use Safari (not Chrome) to add to home screen
- Tap the Share button (box with arrow) → scroll down → "Add to Home Screen"
- The app will open fullscreen like a native app
- Sound works after tapping the 🔊 button on the Home tab

FILES IN THIS ZIP:
- index.html        ← The entire app
- manifest.json     ← PWA configuration
- sw.js             ← Service worker (offline support)
- apple-touch-icon.png ← iOS home screen icon
- icon-192.png      ← PWA icon
- icon-512.png      ← PWA icon (large)
