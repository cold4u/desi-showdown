# Desi Showdown — Indian Politics Fighter

A standalone 3D fighting game featuring political caricatures, built with Three.js, Canvas, and Web Audio.

---

## 🎮 Features Included

- **Full 3D Character Models & Animations:** Modi, Rahul, Didi, Trump, Yogi, Nitin, and Boss (Mbapu) + Bull/Bulldozer special asset.
- **Both Desktop & Mobile Models:** High-poly desktop versions and optimized mobile `.glb` assets.
- **Complete Sound FX & Voice Lines:** 57 sound effects, announcer voice tracks ("Fight!", "K.O.!", "Final Round!"), super moves soundbeds, and music.
- **Procedural Arenas:** Sansad Bhavan, Jantar Mantar, and Desi Sadak.
- **Dynamic HUD & News Ticker:** Real-time health bars, Shakti meter, combo counters, live parody news channel commentary, and post-match victory screen.
- **Zero Build Tools Required:** Pure static files ready to be served immediately by GitHub Pages, Vercel, Netlify, or any static HTTP server.

---

## 🕹️ Controls

### Keyboard (Desktop)
- **Move:** `A` / `D`
- **Jump:** `W`
- **Crouch:** `S`
- **Block:** Hold backwards (away from opponent)
- **Punch:** `J`
- **Kick:** `K`
- **Grab:** `I` or `J + K`
- **Super Move:** `L` or `Space` (when SHAKTI meter is full)
- **Pause:** `Esc`
- **Music Toggle:** `M`
- **Mute Audio:** `N`

### Specials & Combos
- **Forward Punch:** `→ + J`
- **Forward Kick:** `→ + K`
- **Sweep:** `↓ + K`
- **Combos:** `J, J, J` · `J, J, K` · `J, K, K` · `K, K` · `↓J, J` · `↓J, K`

### Touch (Mobile / Tablet)
- Virtual joystick for movement, jump, and crouch
- Dedicated on-screen buttons: **PUNCH**, **KICK**, **GRAB**, **SUPER**

---

## 💻 Running Locally

Because the game uses ES Modules and WebGL assets (`.glb` models), it must be served over HTTP:

### Using Python:
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your web browser.

### Using Node.js:
```bash
npx serve .
```

---

## 🚀 Hosting on GitHub Pages

This game is configured with relative URLs (`./`) and `.nojekyll`, meaning it works automatically when hosted in any GitHub Pages subfolder (e.g. `https://<username>.github.io/<reponame>/`).

### Option 1: Automatic via GitHub Actions (Recommended)
1. Push this repository to GitHub.
2. In your GitHub repository, go to **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select **GitHub Actions**.
4. The included workflow (`.github/workflows/deploy.yml`) will automatically build and publish your game!

### Option 2: Deploy from Branch
1. In your GitHub repository, go to **Settings** → **Pages**.
2. Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Click **Save**. Within ~1 minute, your game will be live at `https://<username>.github.io/<reponame>/`!

---

## 📄 Parody Notice
This game is a parody for entertainment purposes. All character caricatures and political elements are intended solely as light-hearted humor.
