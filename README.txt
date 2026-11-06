HOW TO PUT CGPA PRO ONLINE (free)

Option A - Netlify (easiest, no account tools needed)
1. Unzip this folder on a computer.
2. Go to app.netlify.com/drop and drag the whole folder onto the page.
3. Netlify gives you a link. Open it on a phone.

Option B - GitHub Pages
1. Create a free GitHub account and a new public repository.
2. Upload all files in this folder to it.
3. Settings > Pages > Deploy from branch (main, root). Your link appears after a minute.

INSTALL ON A PHONE
Android (Chrome): open the link, tap "Install app" or menu > Add to Home screen.
iPhone (Safari): open the link, tap Share > Add to Home Screen.
After the first open online, it works offline.

UPDATING: upload the changed files again. If you change index.html, change "cgpa-pro-v1" in sw.js to "cgpa-pro-v2" so phones refresh.
Note: the app must be served over https (Netlify and GitHub Pages do this). Opening index.html directly from a file still works, but without installing or offline caching.
