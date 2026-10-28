# Snake

Play Snake in your browser: <https://rehanmohammed2609.github.io/snakegame-web/>.

Source code is kept separately in the private `snakegame` repository.

## Controls

- Move with the **arrow keys** or **WASD**.
- The snake wraps around the edges.
- Eat green food to grow and increase your score.
- Avoid running into yourself.
- Press **Space** or click after a game ends to restart.

The game runs in the browser using WebAssembly. The browser downloads the game build when you play.

## Deploy

This repository publishes the static game files in `site/` to GitHub Pages with the workflow in `.github/workflows/pages.yml`.
