# Moonlit Lantern

Pass-and-play party games for a single phone: Mafia and Imposter. One static file, no build step, no server.

Live site: https://fenrirak.github.io/Moonlit-Lantern/

## Mafia with no human host

The phone is the narrator. It deals roles privately, then runs each night by visiting every living player in number order (everyone remembers their player number). Everyone taps through the same screens, even innocents (who get a decoy pick), so nobody can tell who holds a power. In the morning it announces what happened, runs a discussion timer with an alarm, collects secret ballots, counts them and checks who has won. Optional voice narration, player names, a group-decides voting mode, a one-kill-per-night mode and a one-save-per-night mode for doctors are in the setup screen. A game in progress survives a page refresh.

## Home screen icon

The page ships with a crescent-moon icon. Keep `apple-touch-icon.png`, `icon-192.webp`, `icon-512.webp`, `icon-maskable-512.webp` and `manifest.webmanifest` in the same folder as `index.html` so "Add to Home Screen" on iPhone and Android picks them up.

## Run locally

Open `index.html` in any browser.
