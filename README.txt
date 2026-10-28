DINK DASH - Android install guide

Dink Dash plays in landscape. The installed app opens sideways automatically.

Play right away (no setup):
  Copy index.html to your phone and open it in Chrome. Playing the computer works offline.
  Friend online needs the app installed from a web link (steps below) and internet on both phones.

Friend online:
  Each player opens Dink Dash on their own phone and picks "Friend online".
  One taps "Host game" and reads out the 4-letter code; the other taps "Join game" and types it.
  Both phones need internet: the same Wi-Fi, mobile data, or one phone sharing its hotspot
  (the hotspot phone needs mobile data turned on). Bluetooth isn't supported.

Install as an app (home-screen icon, full screen):
  1. Go to github.com and create a free account.
  2. Create a new public repository named dinkdash.
  3. Click "Add file" > "Upload files" and upload everything in this folder.
  4. Open Settings > Pages, set Source to "Deploy from a branch", branch "main", folder "/ (root)", Save.
  5. After a minute, open https://YOUR-USERNAME.github.io/dinkdash/ in Chrome on your phone.
  6. Tap the Chrome menu (three dots) > "Add to Home screen" > Install.

Get an APK file (for sideloading or the Google Play Store):
  1. Go to pwabuilder.com and paste your github.io link from step 5.
  2. Choose "Package for stores" > Android > Generate.
  3. Download the zip. It contains an .apk you can install on your phone
     (allow "Install unknown apps" for your browser or file manager)
     and an .aab file for uploading to Google Play.

Updating to a new version:
  Replace the files in your GitHub repository with the new ones. Installed copies pick up
  the new version the next time they open with internet.
