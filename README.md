# birthday ritual — full flow

Single static file: open `index.html` (no build, no dependencies).
Flow: opening -> 10 mandatory questions -> "are you ready to wish?" -> camera -> final page.

- Camera needs https or localhost (or a file opened in a browser that allows it). Photo stays in memory only.
- Birthday images are embedded in index.html (copies in assets/). Fonts and the Tenor cat GIF load online.
- Hooks: `ritual:start` and `ritual:finish` events.
