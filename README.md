# Inkbound

## Overview

Inkbound is a journal-themed text adventure with no fixed script — an AI dungeon master writes each entry live, based on your choices. Pick an archetype, whisper in a detail you want the tale to involve, track your vitality and satchel, and watch the story unfold turn by turn to a proper ending, victory, defeat, or something bittersweet.

## Playing it

Open `index.html` in a browser, or visit the GitHub Pages URL once it's enabled for this repo (see below). You'll need a free [Groq API key](https://console.groq.com/keys) — paste it in on the setup screen.

The key is only ever held in your browser's memory for that session. It's sent directly to Groq's API and nowhere else, and it isn't saved anywhere — so don't share this file with your key still typed into it, and don't commit a key to this repo.

## Hosting it on GitHub Pages

1. Push this repo to GitHub (or upload `index.html` through the web UI).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. After a minute or two, the game is live at `https://<your-username>.github.io/<repo-name>/`.
