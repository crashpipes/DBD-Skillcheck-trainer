[README.md](https://github.com/user-attachments/files/29168675/README.md)
# DBD Skill Check Trainer

A tiny web app to practice **Dead by Daylight** skill checks — built to drill the hard
**Great** (white) skill checks on generators and heals.


## Features

- Faithful base-game skill check: white circle, red needle, white Good zone with the bright Great zone on its leading edge — straight (non-rounded) edges like in the game.
- Rotation speed matched to real gameplay (~1.05 s per rotation, measured frame-by-frame from a game clip).
- Official DBD sounds: appear cue, Great "ting", and the miss explosion.
- Adjustable master volume + mute.
- Rebindable key (Space by default) — or just click.
- Session stats: Greats, Goods, Misses, Great %, current Great streak and best.

## How to use

1. Open the page and click **Start**.
2. Press your bound key (**Space** by default) — or click — when the needle reaches the zone.
3. Hit the small bright-white **Great** zone for a perfect check. Checks repeat automatically.

## Controls

| Action | Default |
| --- | --- |
| Hit skill check | `Space` or mouse click |
| Change key | **Key** button, then press any key (`Esc` to cancel) |
| Volume / mute | Slider and 🔊 button |

## Deployment (GitHub Pages)

This is a single self-contained `index.html` (sounds are embedded, no external files).

1. Create a public repository and upload `index.html`.
2. Go to **Settings → Pages**.
3. Set the source to branch **main**, folder **/ (root)**, and save.
4. Your site goes live at `https://<your-username>.github.io/<repo>/`.

## Credits

Game audio and the Dead by Daylight name are property of **Behaviour Interactive**.
This is an unofficial fan-made practice tool, not affiliated with or endorsed by Behaviour Interactive.
