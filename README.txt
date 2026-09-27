Ledgerbook — Personal Finance Statement
========================================

Files in this folder:
- index.html    → the app itself. Open this directly in a browser to run it.
- manifest.json → PWA metadata (name, icons, colors) — needed for "Add to
                  Home Screen" and for Play Store packaging later.
- sw.js         → service worker; caches the app so it also works offline
                  once loaded once.
- icons/        → app icons (192px and 512px).

How to use it:
1. Double-click index.html to run it locally, OR
2. Upload this whole folder to a free static host (GitHub Pages, Netlify,
   Vercel) to get it a public URL and enable installing it as a PWA.

Your data is stored in the browser's local storage on whichever device
and browser you use it in — it does not sync between devices or get sent
anywhere.

Next steps for the Google Play Store are covered separately — ask if you
want the walkthrough again.
