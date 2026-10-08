# OTOPROJECT WMS Surabaya - GitHub PWA Launcher

Target Google Apps Script Web App:
https://script.google.com/macros/s/AKfycbziW5yaz8RSz-LLaZKx8xfCGotzrN06UfClCs9nOvZPGKaz-gfPTce_Vkdz39YdS4IZ/exec

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `wms-surabaya`.
2. Upload all files/folders from this package to the repository root.
3. Open Settings -> Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, folder `/ (root)`.
6. Save and wait for the GitHub Pages URL.
7. Open the GitHub Pages URL from an Android phone.
8. Choose Add to Home Screen / Install App.
9. The icon will appear as `WMS SBY`.

## Architecture

GitHub Pages is only the mobile/PWA launcher.
The actual WMS remains hosted by Google Apps Script.

This avoids embedding the Apps Script Web App in an iframe.
