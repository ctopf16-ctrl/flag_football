# Flag Bowl QB

A retro flag football game where you play quarterback. Run your own playbook against man, Cover 2, Cover 3 and Cover 4 defenses, tweak routes before the snap, draw new plays in the play maker, and learn your reads in study mode.

**▶ Play it here: https://ctopf16-ctrl.github.io/flag_football/**

It's built for phones first and also works on a computer. The game checks what device you're on and sets up the controls to match.

## On your phone

Open the link and turn your phone sideways. For the best experience, add it to your home screen so it opens full screen like an app:

- **iPhone (Safari):** Share button → *Add to Home Screen*
- **Android (Chrome):** ⋮ menu → *Add to Home screen* / *Install app*

| | Phone controls |
|---|---|
| Snap | Tap the field or **HIKE** |
| Throw | Pull back, aim, release |
| Bullet pass | Tap a second finger while aiming |
| Hand off | Tap the runner |
| QB run | Push forward, or aim backward |
| Steer | Hold and drag |
| Juke | Flick up or down |
| Stutter / burst | Flick back / flick forward |

## On a computer

| | Mouse | Keyboard |
|---|---|---|
| Snap | Click the field or **HIKE** | Space or Enter |
| Throw | Click, drag back to aim, release | |
| Bullet pass | Right-click while aiming | Space or B while aiming |
| Hand off | Click the runner | |
| QB run | Drag forward, or aim backward | |
| Steer | Hold and drag | W / S or ↑ / ↓ |
| Juke | Flick up or down | Space |
| Stutter / burst | Flick back / flick forward | A / D (or ← / →) |
| Next play | | Enter |
| Back to plays | | Esc |
| Fullscreen | | F |

## Saving

Your plays from the play maker, keep/toss picks, route tweaks and settings are saved in your browser on the device you play on. They don't sync between devices.

## How it's built

The whole game is one file, [`index.html`](index.html): plain HTML, CSS and JavaScript with a canvas for the field. The music and sound effects are generated live with the Web Audio API. There's no build step. Edit the file and push, and GitHub Pages serves the new version.
