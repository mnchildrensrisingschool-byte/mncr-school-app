MN CHILDRENS RISING SCHOOL — PWA package

Upload the CONTENTS of this folder to the root of the existing GitHub repository
(the same folder that contains index.html). Keep this structure:

index.html
manifest.json
sw.js
icons/icon-192.png
icons/icon-512.png

Then open the GitHub Pages website in Chrome. The Install School App button
should appear when Chrome considers the site installable. Otherwise use Chrome
menu > Install app / Add to Home screen.

Notes:
- Firebase login and database still require an internet connection.
- This package makes the website installable as a PWA; it is not an APK file.
- APK packaging can be done afterward using a Trusted Web Activity/PWA packaging
  workflow once the PWA is deployed and verified on its final HTTPS URL.
