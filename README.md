# Flap me Orbs

Vibecoded. This is a tribute to Dong Nguyen's Flappy Bird. Thanks, Dong!

Steer your hero through pipes and star trails. Jump to fly. Rare power-up orbs change how you move. The code is yours to use, fork, and remix. GG!

-Rance

## How to play

Click, tap, or press Space to jump.

- **Play** — score through six skies, from Dusk Vale to Event Horizon
- **Practice** — a slow looping course. Crashes bounce you back. Leave with **Menu** or **Esc**
- **Modify your hero** — change shape, colors, glow, and pose. That look is saved with your leaderboard score

Scores are shared online for everyone on the public link.

### Pickups

Power-up orbs are rare and random. The legend sits in the bottom-left corner.

| Orb | Effect |
| --- | --- |
| Stars | Trails between pipes. +1 each (+2 with gold) |
| White | Mouse-drag for a few seconds. Hold and drag; release to fall |
| Pink | Shield. Survive one hit |
| Cyan | Drift. Slower fall |
| Green | Tiny. Smaller hitbox |
| Gold | Double score |
| Orange | Dash. Hold left click to burst toward the cursor |

## Play online

Open the GitHub Pages link:

https://potatoflewaround.github.io/flap-me-orbs/

Anyone with that URL can play in a browser. The leaderboard updates live for every open page.

## Run the game

You do not need Node or a browser. Double-click:

`dist\win-unpacked\Flap me Orbs.exe`

If Windows SmartScreen warns you, choose **More info**, then **Run anyway**.

There is also a packaged build in `dist\Flap me Orbs 1.0.0.exe`.

## Build from source

```
npm start
```

Edit `game.html`, close the running game, then:

```
npx electron-builder --win
```


