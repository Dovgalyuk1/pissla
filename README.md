# PISSLA — $PISSLA meme site

One-page, no-build static site (HTML + CSS + JS, one file) for the $PISSLA meme coin:
a shiba in sunglasses who marks the wheels of white electric cars.

## Structure
```
index.html      — the whole site (styles + scripts inline)
assets/         — cut-out character, scene, crops, favicon
```

## Settings
Three lines at the top of the first `<script>` in `index.html`:

```js
window.CONTRACT = "";   // contract address
window.TWITTER  = "";   // link to X
window.BUY_URL  = "";   // buy link — BUY button stays inactive while empty
```

## Mini-game — MARK MODE
Canvas game inside a fake car console: hold to pour, aim the arc at the front
wheel, mind the wind, keep off the paint (alarm) and watch the tank. Eight cars,
each one unlocks a page of THE ROUND BOOK.

Sound and music are generated with Web Audio — no audio files.

## Local run
```
python3 -m http.server 8901
```
