# ⚽ Retro Cup '86 — European Football

A retro top-down arcade football game, built for the browser. Sensible Soccer-inspired: chunky pixel players, momentum-based ball physics, and an auto-switching control scheme.

**[▶ Play it live](#)** *(update this link once GitHub Pages is enabled — see below)*

## Controls

**Desktop**
- Arrow keys / WASD — move
- Space (hold) — charge and release a shot/pass

**Mobile / touch**
- Virtual joystick (bottom-left) — move
- SHOOT button (bottom-right) — charge and release

Control auto-switches to whichever blue player is nearest the ball.

## Running locally

No build step — it's a single HTML file.

```bash
git clone https://github.com/YOUR_USERNAME/retro-euro-football.git
cd retro-euro-football
open index.html   # or just double-click it
```

## Hosting on GitHub Pages

1. Push this repo to GitHub (see below).
2. Go to **Settings → Pages** in your repo.
3. Under **Source**, choose the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub will publish it at `https://YOUR_USERNAME.github.io/retro-euro-football/` within a minute or two.

## Tech

Plain HTML5 Canvas + vanilla JavaScript. No dependencies, no build tools.
