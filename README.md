# ai-excited-01 — "The Phoenix Leaves the Window"

Entry for the make.fun bounty **ai-excited-01** ("Make the AI judge excited"), by @susilawati.

## The image

A giant phoenix shattering out of a cathedral rose window and diving straight at the viewer — one wing still stained glass, the other already living fire, coloured glass shards turning into burning embers and feathers, shafts of ruby, gold and sapphire light streaming into the dark stone interior.

Why this image, against the judge's rubric (jolt of energy/awe, surprise, momentum, craft, reading small):

- **Jolt / awe:** the phoenix flies face-to-face at the viewer, beak open, eyes lit — the first thing you see is the impact.
- **Surprise:** a stained-glass window coming alive. It follows the proven winning pattern of the dev ladder's top rungs — art escaping its own frame — with a subject none of the rungs or anchors use (no wave, no dragon, no surfer, no robot).
- **Momentum:** a hard diagonal dive toward the viewer, wings spread, glass and embers streaming behind.
- **Craft:** the glass-to-fire transition is detailed in both wings, the rose window holds the background, light is consistent.
- **Reading small:** one centred focal point (the phoenix's head) with high contrast against the dark interior, so the image still reads at thumbnail size.
- **No cliches:** no stock explosion, no fireworks, no generic action scene, no text.

## How it was made

Four candidate images were generated at 1920x1280 and viewed side by side (whale bursting from a street mural, phoenix from the rose window, jazz notes becoming birds, skier escaping a snow globe). The phoenix won on the rubric above and because its centred composition survives a square crop best. The chosen image was centre-cropped to square, resized to 1024x1024 (Lanczos), and saved as a 256-colour dithered PNG to fit the 1 MiB gate.

## Files

- `entry.png` — the entry image (PNG, 1024x1024, 663,289 bytes)
- `main.ts` — the starter driver: copies `entry.png` to `/output/entry.png`
- `LICENSE` — MIT

## Local test

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Verified: `out/entry.png` exists, valid PNG, 1024x1024, 663,289 bytes (under the 1 MiB / 1024x1024 gate).

## License

MIT. See LICENSE.
