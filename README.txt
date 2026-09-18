PASSPORT PHOTO EXTRACTOR - WEB APP (GITHUB PAGES)
=====================================================

WHAT'S IN THIS FOLDER
----------------------
- index.html   -> the entire app (HTML + CSS + JS, self-contained)

This app runs ENTIRELY in the browser. No installation, no Python,
no admin rights, no server, no upload of your PDF anywhere - it all
happens on your own device using JavaScript.


HOW TO PUT THIS ON GITHUB PAGES (free hosting)
------------------------------------------------
1. Go to https://github.com and log in (create a free account if
   you don't have one).

2. Click the "+" icon (top right) -> "New repository".
   - Name it anything, e.g. "photo-extractor"
   - Set it to Public
   - Click "Create repository"

3. On the new repository page, click "uploading an existing file"
   (or "Add file" -> "Upload files").

4. Drag and drop "index.html" into the upload box, then click
   "Commit changes".

5. Go to the repository's Settings tab -> Pages (in the left
   sidebar).

6. Under "Build and deployment" -> "Source", choose "Deploy from a
   branch". Under "Branch", choose "main" and folder "/ (root)",
   then click Save.

7. Wait about a minute, then refresh the Pages settings page. It
   will show a link like:

       https://YOUR-USERNAME.github.io/photo-extractor/

   Open that link - your app is now live and usable from any
   device with a browser, no installation needed.


HOW TO USE THE APP
---------------------
1. Open your GitHub Pages link (or just open index.html directly
   in a browser - it works completely offline too).
2. Click the upload area (or drag and drop) to select your PDF.
3. Click "Extract Photos".
4. Thumbnails of each detected photo appear - download them one by
   one, or click "Download All (.zip)" to get everything at once.


NOTES
-----
- Works in any modern browser (Chrome, Edge, Firefox).
- Best suited for scanned sheets with photos arranged in a grid on
  a white/light background (like your sample).
- Nothing is uploaded anywhere - processing happens locally in
  your browser using JavaScript, which is why this satisfies
  privacy/upload restrictions.
- You can also just open index.html directly by double-clicking it
  (no GitHub needed) if you only need it on one computer - GitHub
  Pages is only needed if you want a shareable link or access from
  multiple devices.
