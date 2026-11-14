# afterzerogames.github.io

The After Zero website: https://afterzerogames.github.io

- `index.html`: brand page with every game.
- `<game>/privacy.html`: each game's privacy policy (linked from Google Play).
- `games.json`: store status per game; the marketing bot sets `"status": "live"` when a game appears on Google Play.
- `media/` exists only on the `gh-pages` branch: the marketing bot puts the current clip there so Instagram can fetch it.

Edit `main`; the `publish site` workflow rebuilds `gh-pages`.
