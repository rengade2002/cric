# cric DASH Player

A single-file DASH streaming player using `dash.js`. Plays encrypted or unencrypted `.mpd` files using URL parameters.

## How to Use

Visit:https://rengade2002.github.io/cric/?id=MPD_URL&key=KEY


- `id`: URL of the `.mpd` file (manifest)
- `key`: optional. For encrypted streams:
  - Format for ClearKey: `KID:KEY` (hex:hex)
  - For Widevine/PlayReady: pass as `widevine:<license_server_url>`

## Example:

