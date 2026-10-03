# Milk Expense Calculator — Installable PWA

This is a Progressive Web App version of the Milk Expense Calculator.

## Install on Android
1. Put this folder on a web server/HTTPS hosting service (PWA installation requires HTTPS, except localhost).
2. Open `index.html` through that HTTPS address in Chrome.
3. Chrome menu → **Add to Home screen** / **Install app**.
4. The app will open in standalone mode and cache the calculator for offline use.

## Important
Opening `index.html` directly as a `file://` URL will run the calculator, but Chrome cannot install the service-worker-based PWA from a local file. For installation, use HTTPS hosting.

No external libraries are required.
