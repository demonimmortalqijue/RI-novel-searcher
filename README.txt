RI SEARCHER PWA

Upload the contents of this folder to the ROOT of your existing GitHub Pages repository, replacing the previous versions. Keep all five files together:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

NEW: Chapter range search
- Entire novel
- From a chosen chapter onward (for example, chapter 1000 to the end)
- Between two chapter numbers (for example, chapters 1000-1500)

The existing EPUB section filter remains available and can be combined with a chapter range.

After committing, wait for the GitHub Pages deployment to finish. Reopen the site in Chrome. If the installed app still shows the old version, close it fully, reopen it while online, and refresh/update the page so the new service worker cache is installed.

Your EPUB and index stay on your device in browser storage. The EPUB is not uploaded to GitHub. Because the installed PWA uses a different website origin from a local HTML file, import the EPUB into the PWA once.
