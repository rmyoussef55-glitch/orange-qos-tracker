Orange QoS Tracker - PWA package
Files: index.html, manifest.webmanifest, sw.js, icons/ (keep this exact structure)

1) Upload ALL files (keeping the icons folder) to any HTTPS host, e.g. GitHub Pages / Netlify / internal web server.
2) Open the https link on the phone:
   Android (Chrome): menu > Install app / Add to Home screen
   iPhone (Safari): Share > Add to Home Screen
3) After publishing a new index.html, change VERSION in sw.js (e.g. qos-tracker-v3) so phones refresh the offline copy.
