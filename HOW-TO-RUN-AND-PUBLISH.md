# 🐾 Brush Dau — How to play, test, and publish

A Brush Jjaemu–style game starring Dau. Brush the cat for points; the moment Dau
turns to glare (red **FREEZE!**), stop — or you get bitten and **YOU DIED**.

---

## 📁 What's in this folder

```
brush-jjaemu/
├── index.html                 ← the whole game (open this to play)
├── assets/
│   ├── cat-calm.png           ← Dau sleeping  (safe to brush)
│   ├── cat-alert.png          ← Dau glaring   (FREEZE!)
│   ├── cat-bite.jpg           ← Dau's yawn    (the YOU DIED scare)
│   └── cat-title.jpg          ← (optional) extra photo
└── HOW-TO-RUN-AND-PUBLISH.md  ← this file
```

You can swap any photo later: just replace the file in `assets/` keeping the **same
filename**. (PNG with a black/transparent background looks best for calm & alert.)

---

## ▶️ 1. Test it on your own computer (10 seconds)

1. Open the `brush-jjaemu` folder.
2. **Double-click `index.html`.** It opens in your web browser.
3. Click **Start brushing**, hold the mouse button, and drag across Dau.

That's it — no installing anything. Sound, score, and "Best" all work offline.

> If sound doesn't play at first, click once anywhere — browsers require one click
> before they allow audio.

---

## 🌐 2. Put it online so your girlfriend can play on her phone

You need the game on the internet so she can open a **link**. Two free ways —
**Option A is the easiest** (no accounts, no code).

### ✅ Option A — Netlify Drop (drag-and-drop, ~2 minutes)

1. Go to **https://app.netlify.com/drop** in your browser.
2. Open your file explorer next to it and **drag the whole `brush-jjaemu` folder**
   onto the dashed box on that page.
3. Wait ~20 seconds. You'll get a live link like
   `https://shiny-cupcake-12345.netlify.app` — **that link already works!**
4. Send that link to your girlfriend. Done. 🎉
5. *(Optional, to keep it forever + pick a nicer name)*: click **Sign up** (free,
   use Google/GitHub), then in the site's **Site settings → Change site name**, set
   it to something like `brush-dau` → your link becomes `https://brush-dau.netlify.app`.

> Without signing up, the demo link is temporary. Signing up (free) makes it permanent.

### 🅱️ Option B — GitHub Pages (permanent, free, a few more clicks)

Good if you'd rather use GitHub. You already have `git` installed.

1. Make a free account at **https://github.com**.
2. Click **New repository** → name it `brush-dau` → **Create repository**.
3. On the new repo page, click **"uploading an existing file"** → drag in
   `index.html` and the whole `assets` folder → **Commit changes**.
4. Go to the repo's **Settings → Pages**.
5. Under "Build and deployment", set **Source = Deploy from a branch**, branch
   **main**, folder **/ (root)** → **Save**.
6. Wait ~1 minute, refresh. The link appears at the top:
   `https://YOURNAME.github.io/brush-dau/` — send that to her.

---

## ✏️ Common tweaks (ask if you want help)

- **Make it easier/harder:** in `index.html`, find `nextLookDelay`, `graceWindow`,
  `lookDuration`. Bigger `graceWindow` = more reaction time = easier.
- **Change the title text:** search for `Brush&nbsp;Dau` in `index.html`.
- **Replace a photo:** drop a new image into `assets/` using the same filename.

Have fun! 🐱💗
