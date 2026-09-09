# Flap me Orbs desktop build

Run locally:

```
cd C:\Users\tinor\Desktop\flux-bird-app
npm start
```

Windows builds:

- Portable: `dist\Flap me Orbs 1.0.0.exe`
- Installer: `dist\Flap me Orbs Setup 1.0.0.exe`
- Unpacked folder Steam can launch: `dist\win-unpacked\Flap me Orbs.exe`

Rebuild after game changes: copy `flux-bird.html` to `game.html`, then `npx electron-builder --win`.

Steam: upload `win-unpacked` as a depot and set the launch executable to `Flap me Orbs.exe`.
