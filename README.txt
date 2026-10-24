MACHINE DOWN - participant app

FASTEST WAYS TO LAUNCH (pick one)
1. Netlify Drop: go to app.netlify.com/drop, drag this whole folder in, and you get a public link in seconds.
2. GitHub Pages: create a public repository, upload every file in this folder to the root, then Settings > Pages > Deploy from a branch > main > / (root). Your link is https://USERNAME.github.io/REPOSITORY/
3. Any web host: upload all files to one folder.

INSTALL AS AN APP ON A PHONE
Open the link in Chrome (Android) and tap Install app / Add to Home screen.
On iPhone open it in Safari, tap Share, then Add to Home Screen.

SEND ANSWERS TO YOUR GOOGLE SHEET (optional, recommended)
1. Follow the host guide (HOST-SETUP.txt) to create the Google Sheet and get a web app URL that ends in /exec.
2. Open config.js in this folder, paste the URL between the quotes, save, then upload the folder again.
3. Participants then see "Submitted" after finishing, and their answers appear in your Sheet automatically.
This only works from the hosted copy (Netlify or GitHub Pages). It does not work inside the claude.ai preview link.

Notes
- Participants never see scores. They send the submission block to you, and you rank it in the Scoreboard app.
- Opening index.html straight from a downloaded file also works for testing, but the install option needs a web link.
