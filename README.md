# Flap me Orbs

A vibe-coded desktop game. Fly through pipes, grab orbs, and climb through changing skies.

Inspired by **Flappy Bird**, developed by **Dong Nguyen**.

## Play

Pick a control mode, then **Play** or **Practice**.

**Modes**

- **Jump** — tap / click / Space to flap
- **Mouse drag** — hold and drag to move; release to fall
- **Web** — keep your jump, and hold click on a pipe to sling

**Orbs**

- **Pink** — shield (survives one hit)
- **Cyan** — drift (slower fall)
- **Green** — tiny (smaller hitbox)
- **Gold** — double score
- **Orange** — dash (hold left click to burst toward the cursor)
- **?** — switches you to mouse-drag

Practice is a slow looping course that walks through every power-up. Crashes bounce you back. Leave with **Menu** or **Esc**. Scores stay local to this machine.

## Run locally

```
cd C:\Users\tinor\Desktop\flap-me-orbs
npm start
```

## Windows builds

- Portable: `dist\Flap me Orbs 1.0.0.exe`
- Installer: `dist\Flap me Orbs 1.0.0.exe`
- Unpacked folder Steam can launch: `dist\win-unpacked\Flap me Orbs.exe`

After editing the game, copy `C:\Users\tinor\Desktop\flap-me-orbs.html` to `game.html`, then:

```
npx electron-builder --win
```

Close the running game first or the rebuild cannot overwrite `dist\win-unpacked`.

Steam: upload `win-unpacked` as a depot and set the launch executable to `Flap me Orbs.exe`.
