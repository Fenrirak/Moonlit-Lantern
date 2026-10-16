# Moonlit Lantern

Pass-and-play party games for a single phone: Mafia and Imposter. One static file, no build step, no server.

## Mafia with no human host

The phone is the narrator. It deals roles privately, then runs each night by visiting every living player in seat order. Everyone taps through the same screens, even innocents (who get a decoy pick), so nobody can tell who holds a power. In the morning it announces what happened, runs a discussion timer with an alarm, collects secret ballots, counts them and checks who has won. Optional voice narration, player names, a group-decides voting mode and a one-kill-per-night mode are in the setup screen. A game in progress survives a page refresh.

## Put it online with GitHub Pages

1. Create a new GitHub repository and upload `index.html`, `.nojekyll` and this `README.md`.
2. Open the repository's Settings, then Pages.
3. Under Build and deployment, set Source to "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, then Save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

Custom domain: add it under Settings, then Pages, then Custom domain, and point a CNAME record at `YOUR-USERNAME.github.io`.

## Run locally

Open `index.html` in any browser.
