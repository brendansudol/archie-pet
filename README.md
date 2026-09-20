# Archie

Archie is a cute red robot dog with a studious personality and a trusty pencil.

This interactive showcase includes thirteen animations, sixteen look directions, adjustable sizes, inline text examples, task states, and a draggable desktop companion.

## Run locally

```sh
python3 -m http.server 8000 --directory docs
```

Open http://localhost:8000. The site uses plain HTML, CSS, and JavaScript with no build step.

## Publish

GitHub Pages serves the `docs` directory on the `main` branch. Push a change to `main` to update the site.

## Assets

`docs/assets/archie-pet.zip` contains the pet manifest and animation atlas. The site also includes a waving GIF and a still image for inline use.

## Extra animations

Skateboard, sunglasses, love, and thinking each have six frames and a downloadable GIF. `docs/assets/archie-extras.webp` is a 6-column × 4-row atlas with 192 × 208 pixel cells. Row order and per-frame durations are recorded in `docs/assets/archie-extras.json`. These web animations supplement the standard pet atlas.
