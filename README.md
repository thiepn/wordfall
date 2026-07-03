# Wordfall v1.0.2

Wordfall is a self-contained space-defense typing game built with one `index.html` file.

## Keyboard controls

| Key | Action |
|---|---|
| Letter keys | Type alien-ship words only |
| Arrow keys | Navigate menus and overlays |
| Enter | Select the focused menu or overlay option |
| Escape | Pause or resume an active run; return from secondary screens |

There are no keyboard shortcuts for mute, fullscreen, abilities, target switching, target cancellation, or pausing with letter keys. `M`, `P`, and `F` are always treated as typing input during gameplay. Number keys, Space, and Tab do not activate game actions.

## Mouse controls

Use the on-screen buttons to:

- mute or unmute sound
- toggle fullscreen
- activate Time Freeze, Plasma Pulse, and Shield Repair
- pause the game
- cancel the current target
- switch to another matching target

## Running locally

Open `index.html` directly in a current desktop browser. No installation, server, framework, or build process is required.

## GitHub Pages

1. Upload `index.html` to the repository root.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the main branch and root directory.
5. Save.

## Verifying the keyboard fix

The main menu footer must display:

```text
v1.0.2 · Keyboard fix · Local save only
```

The HTML also contains this build marker:

```html
<meta name="wordfall-build" content="1.0.2-keyboard-fix" />
```

If an older version still appears after uploading, hard-refresh the page or open the Pages URL in a private browser window.
