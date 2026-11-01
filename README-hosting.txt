HOSTING STEPS FOR https://gitesh-chaurasia.github.io/takshak-verify
====================================================================

1. Go to https://github.com/Gitesh-Chaurasia/takshak-verify
   and click "Add file > Upload files".

2. Drag in ALL files INSIDE the verify-site/ folder
   (not the folder itself — you should see index.html, certificates.json,
   verify/, logo.webp, .nojekyll etc. at the root level).
   Then click "Commit changes".

3. Wait about 1 minute for GitHub Pages to deploy, then open:
     https://gitesh-chaurasia.github.io/takshak-verify/verify/?id=<any cert id>
   and scan one certificate QR code with a phone on mobile data to confirm it works.

NOTE: The .nojekyll file MUST be included — without it GitHub Pages may
      ignore some files. Make sure hidden files are shown when uploading.
