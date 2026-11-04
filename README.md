# Standalone Games

Single-file HTML games that run in any browser.

- **Tidy Corners** (`tidy-corners.html`): a drag-and-drop room tidying game with twenty levels across five rooms: Desk Corners, Cozy Nooks, Colour Pop, and Kachori's Paradise (her Snack Corner and Bow Bedroom), starring Kachori, a fluffy white cat.

Play online: https://rajatchatterjee.github.io/standalone-games/tidy-corners.html

## Other apps

- **Five-Minute Shelf** (`five-minute-shelf/`): swipeable cards with one idea from a great book each, a daily set of twelve and a 5-minute reading clock. Install it from https://rajatchatterjee.github.io/standalone-games/five-minute-shelf/ (it installs as its own app, separate from Tidy Corners).

## Install as an app

Open the link on a phone or tablet and add it to the home screen (Safari: Share, then Add to Home Screen; Chrome: the Install button in the game or the ⋮ menu). It opens full screen with Kachori's icon and works offline.

## Seasonal switch (Diwali)

At the top of the script in `tidy-corners.html`:

```js
const DIWALI={look:true,levels:true};
```

- `look`: festive colours, marigold garlands, fireworks on finishing a room, Kachori's marigold collar
- `levels`: the two Diwali rooms (8 levels) with tappable firecrackers

Set both to `false` to go back to the normal game. Commit `4e53954` is the last version without any Diwali code.
