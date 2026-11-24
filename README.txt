FINANCE MANAGER - ANDROID PWA

Included files:
- index.html : full app
- manifest.json : Android install metadata
- sw.js : offline caching
- icons/icon.svg : app icon

Features:
- Editable monthly income and budget
- Expense transaction recording and deletion
- Dashboard with budget remaining, transactions, allocation bars
- Emergency fund goal Rp10,000,000
- Wedding savings goal Rp100,000,000
- Debt tracker with one-tap installment record
- Local storage persistence on the browser/device
- JSON export/import backup
- Offline caching after first visit

INSTALL ON ANDROID:
A PWA must be hosted over HTTPS (or localhost) to install reliably.
1. Upload this folder to an HTTPS static host (e.g. GitHub Pages or Netlify).
2. Open the hosted URL in Chrome on Android.
3. Tap Chrome menu (three dots) > Install app / Add to Home screen > Install.
4. Launch Finance Manager from the app drawer/home screen.

Data is stored locally on that browser/device. Export backups periodically.
This package is a Progressive Web App, not a compiled APK. To make a native APK,
wrap/package this web app with Capacitor or Trusted Web Activity and build using Android Studio.
