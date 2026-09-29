# SubTrack

A phone-first web app for tracking Netflix and Spotify subscription customers: who owes, due dates, reminders, gift cards, accounts and profit.

**Privacy:** This repository contains only the app. It holds no customer data and no passwords.
Your data is saved only on your iPhone, inside the app. Never upload your data file (`SubTrack-my-data.txt`) or any backup here.

## Put it online with GitHub Pages (one time)

1. Sign in at github.com and create a new repository named `subtrack`. Set it to **Public** (free GitHub Pages needs a public repository).
2. Click **Add file → Upload files**. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, `.nojekyll` and the whole `icons` folder. Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, then branch **main** and folder **/ (root)**. Click **Save**.
4. After 1–2 minutes your app is live at `https://YOUR-USERNAME.github.io/subtrack/`.

## Install on your iPhone

1. Open the link in **Safari**, tap **Share → Add to Home Screen**, then open SubTrack from the new icon. Always use the icon from now on.
2. Put `SubTrack-my-data.txt` in the Files app (AirDrop it, or email it to yourself and save it to Files).
3. In the app, tap **Restore from file** on the welcome card and pick the file. Your customers, payments and accounts appear.
4. Tap **Turn on** for the icon badge. Then add your passwords in **Customers → Passwords → Paste list**.

## Updating the app later

1. In the app, back up first: **Settings → Export everything as text** (or **Back up data**).
2. In the repository, click **Add file → Upload files**, drop in the new `index.html` (plus any other changed files), and commit.
3. Open the app from its icon, close it, and open it again. The second open shows the new version. Your data stays on your phone.

Keep the same repository and the same link. A different link counts as a different app and starts empty.
If you delete the home-screen icon, iPhone deletes the app's saved data too, so keep a backup.
