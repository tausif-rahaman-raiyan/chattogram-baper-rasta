# চাটগাঁর রাস্তা — Chattogram Arcade Drive

A browser-playable Chattogram driving satire inspired by the public-facing gameplay concept and satirical tone of Baper Rasta. It uses original Canvas-rendered visuals and code, adapted with local roads, Bengali UI, local traffic, and tongue-in-cheek 'national damage' scoring.

## Run locally

1. Extract the ZIP.
2. Open `index.html` in a modern desktop or mobile browser.
3. Press **রাস্তায় নামেন** and choose a starting road.

No build tools, server, login, or external libraries are required. The game draws its road, traffic, vehicles, roadside buildings and hills with HTML Canvas. It includes national-damage scoring, a damage multiplier when driving off-road, fatal bus/truck collisions, a public-chase timer after non-fatal crashes, a boost charge meter, yellow recharge lines, pink case-close lines, and a local Most Wanted board.

## Controls

- **W / ↑** accelerate
- **S / ↓** brake
- **A / ←** steer left
- **D / →** steer right
- **Shift / Space** boost
- **H** horn
- **M** toggle synthesized sound
- **Enter** start/restart

Touch buttons are included for mobile.

## Chattogram route themes

Includes selectable/rotating street themes for Chatteswari Road and Chawkbazar Circle, College Road, Jamal Khan Road, Cheragi Pahar, New Market/Jubilee Road, GEC Circle, 2 No. Gate, Muradpur, Bahaddarhat, Agrabad Access Road, Badamtali, Tigerpass, Lalkhan Bazar, Bayezid Bostami Road, Oxygen, Patenga/Sea Beach Road, Anderkilla, Arakan Road, K.B. Aman Ali Road, Golpahar, Polytechnic, Sholoshahar and Strand Road.

These are arcade route themes rather than a survey-accurate GPS road network. Road names and local areas are included to give the game a Chattogram identity; the driving road is procedurally drawn, not Google Maps or satellite imagery.

## Owner credit

The in-game credit links to [Tausif Rahaman Raiyan's portfolio](https://tausif-rahaman-raiyan.github.io/).

## Publish on GitHub Pages

The game entry point is `index.html`. The GitHub Actions workflow validates the inline JavaScript and deploys the repository root. It now asks `actions/configure-pages` to enable Pages where the workflow token has permission; if GitHub rejects that request, a repository administrator must enable **Settings → Pages → Source → GitHub Actions** once.

## Automatic website deployment

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`. Every push to `main` publishes the static game to GitHub Pages automatically. You can also run it manually from the **Actions** tab.

### Enable Pages once

1. Open **Settings → Pages**.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Push to `main` or run **Deploy Chattogram Baper Rasta** from the **Actions** tab.
4. The published URL will be `https://tausif-rahaman-raiyan.github.io/chattogram-baper-rasta/`.

The game is plain HTML/CSS/JavaScript and needs no build step or third-party runtime libraries.
