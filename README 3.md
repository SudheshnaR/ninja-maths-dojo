# Ninja Maths Dojo

A year-long Vedic maths game for children. It covers all **16 sutras and 13 upasutras** in 33 levels, with:

- a picture story, lessons, worked examples and an Example machine for every level
- 4 missions per level (Quick, Training, Master and the Lightning Round), plus a 50-question practice with no timer
- a Hero Lab: create a hero (ninja kid, tiger, panda, fox, bunny, bear or dragon), win weapons and armour, and feed it healthy food to raise its power

It is one web page and needs no server, no account and no internet after the first visit.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, colours and icons, so it installs like a desktop app |
| `sw.js` | Keeps the app working offline |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## 1. Put it on GitHub (no coding needed)

1. Sign in at [github.com](https://github.com) as **SudheshnaR**.
2. Click **+** (top right) → **New repository**.
3. Name it `ninja-maths-dojo`, choose **Public** (needed for free GitHub Pages), and click **Create repository**.
4. On the new repository page, click **uploading an existing file**.
5. Unzip `ninja-maths-dojo.zip` on your PC. Open the folder and drag **all the files inside it** into the GitHub page (not the folder itself).
   - `.nojekyll` is a hidden file. If Windows hides it, turn on **View → Show → Hidden items** in File Explorer. The app also works without it.
6. Write a short message such as "First version" and click **Commit changes**.

## 2. Turn on the website (GitHub Pages)

1. In the repository, open **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. Wait 1–2 minutes and refresh. GitHub shows the address:
   `https://sudheshnar.github.io/ninja-maths-dojo/`

## 3. Install it as a desktop app on Windows

**Microsoft Edge**

1. Open `https://sudheshnar.github.io/ninja-maths-dojo/` in Edge.
2. Click the **App available / Install** icon in the address bar, or **⋯ menu → Apps → Install this site as an app**.
3. Click **Install**. Tick **Pin to taskbar** and **Create desktop shortcut** if you want them.

**Google Chrome**

1. Open the same address in Chrome.
2. Click the **install** icon at the right end of the address bar, or **⋮ menu → Cast, save and share → Install page as app**.
3. Click **Install**.

The app now opens in its own window from the Start menu, the taskbar or the desktop, with its own icon. After the first visit it also works with no internet.

**On iPhone or iPad:** open the address in Safari → **Share** → **Add to Home Screen**.

## 4. Move his progress from the Claude version

Progress is saved separately in each browser and on each device, so the desktop app starts empty. To bring his stars, levels and hero across:

1. In the **Claude version**, open **Hero Lab** → scroll to **For grown-ups** → tap **Copy progress code**.
2. In the **desktop app**, open **Hero Lab** → **For grown-ups** → paste the code into the box → tap **Load progress code**.

You can use the same steps any time to move progress between the PC and the iPhone.

## 5. Updating the app later

1. In GitHub, open `index.html` → click the **pencil (edit)** or **⋯ → Upload files** to replace it with a new version → **Commit changes**.
2. Open `sw.js` and change `ninja-maths-v1` to `ninja-maths-v2` (then v3 next time, and so on), and commit. This tells installed copies to pick up the new files.
3. Close and reopen the desktop app once or twice. The new version loads, and his progress stays.

## Good to know

- **Progress lives in the browser.** Clearing Edge or Chrome site data erases it. Copy a progress code now and then as a backup.
- **Fonts:** the app loads its fonts from Google Fonts. Offline, it falls back to the computer's own fonts, which look slightly different but work the same.
- **Grown-up tools** in Hero Lab → For grown-ups: sound on or off, a test mode that opens every level without saving, progress codes, and Start over.
