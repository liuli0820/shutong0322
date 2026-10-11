# shutong0322

## 一炷香 · One Stick of Incense

A focus timer measured in old Chinese units of time. Pick a measure, light the stick, and work until it burns down and the bell rings.

| Measure | | Minutes |
| --- | --- | --- |
| 一盏茶 | a cup of tea | 10 |
| 一刻 | one kè | 15 |
| 一炷香 | a stick of incense | 30 |
| 半个时辰 | half a shíchen | 60 |

- The stick and its smoke are drawn live on a canvas. Move your pointer through the smoke and it swirls.
- When time is up, a singing bowl rings. The sound is synthesized with Web Audio, so there are no audio files.
- Time comes from the clock, not the frame rate, so the timer stays accurate in a background tab. A running timer survives a page reload.
- Follows your system's light or dark theme and respects reduced-motion settings.
- One HTML file with no build step and no dependencies. Fonts load from Google Fonts and fall back to system fonts offline.

### Run it

Open `index.html` in a browser. To host it, turn on GitHub Pages for this repository and serve from the branch that holds `index.html`.

Keys: <kbd>Space</kbd> lights or pauses, <kbd>R</kbd> resets, <kbd>1</kbd>–<kbd>4</kbd> pick a measure.
