# Fairway Fables — First Playthrough v1

A dependency-free incremental idle golf game prototype built for GitHub Pages.

## Included gameplay
- Complete nine-hole Founder’s Cup run
- Manual swing loop with variable power
- Five functional upgrades and passive income
- Local save, autosave, and up to four hours of offline earnings
- Three prestige worlds, each with buffs and nerfs
- Responsive desktop and mobile UI
- Installable PWA manifest and icons

## Included production artwork
- Home Course
- Highland Links
- Desert Championship
- Tropical Paradise
- Pip Birdie character action sheet integrated as a live CSS sprite
- Painted UI/prop sheets used for upgrades and clubhouse presentation

## Run locally
Open `index.html` directly, or run a simple local web server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment
1. Create a new empty GitHub repository.
2. Upload every file and folder from this project root. `index.html` must be at the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. GitHub will publish the game at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

No npm install or build step is required.
