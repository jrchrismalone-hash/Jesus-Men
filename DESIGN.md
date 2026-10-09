# DESIGN.md

Brand design system for the app (a discipleship tool helping men grow in Christlikeness as men, husbands and fathers). Built with the `design-taste-frontend` skill. Applies to marketing surfaces: Instagram stories, landing page, launch graphics.

## Design read

Manifesto-style brand for Christian men, aged 25-55, mostly friends-of-friends on Instagram. Bold, direct, unpretentious. Closer to a field manual or a training program than a church bulletin. No pastel faith-aesthetic, no stock-photo smiles.

## Dials

| Dial | Value | Why |
|---|---|---|
| DESIGN_VARIANCE | 7 | Each slide or section uses a different composition. Asymmetric, left-aligned. |
| MOTION_INTENSITY | 1 (stories) / 4 (web) | Story slides are static images. Web gets entry fades only. |
| VISUAL_DENSITY | 2 | One idea per frame. Lots of air. |

## Color

Pure monochrome plus one warm pop taken from the app UI. Dark theme only, locked.

| Token | Hex | Use |
|---|---|---|
| `--ink` | `#121212` | Background. Never pure `#000`. |
| `--ink-2` | `#1c1c1c` | Photo placeholder / raised surface |
| `--paper` | `#ededea` | Primary text |
| `--mute` | `#9a9a96` | Secondary text |
| `--signal` | `#f2b35a` | The one accent, matched to the app's own button colour. Emphasis words, CTA fill, strike-throughs. Nothing else. |

Banned: beige/bone backgrounds, brass/metallic-gold accents, purple gradients, glows.

## Type

- **Archivo** (Google Fonts, variable width + weight). One family for everything.
  - Display: weight 800, width 100, tracking -0.035em, line-height 0.95.
  - Body: weight 400, 44px on stories, line-height 1.35, `--mute` with `--paper` bold for key words.
  - Labels: weight 600, uppercase, tracking 0.14em. Max 1 per 3 frames.
- Emphasis inside a headline = Archivo italic in `--signal`. Never a second font.
- Scripture is set in Archivo regular, not a script or serif.

## Shape

All-sharp. Radius 0 on everything: photos, CTA blocks, dividers. No cards, no pills, no glass.

## Photography

Real photos of real men beat stock. Direction:
- Low light, natural, desaturated warm. Faces partly in shadow or from behind.
- Hands, tools, open Bibles, fire, early morning, fathers with kids.
- No posed smiles to camera, no studio backdrops, no text baked into images.
- Photo slots are sharp-edged rectangles or full-bleed. A dark gradient scrim sits under any text placed on a photo.

## Copy rules

- Zero em-dashes or en-dashes. Use periods, commas, colons.
- Headlines 3-8 words. Body under 25 words.
- No filler verbs (elevate, unleash, transform-your-life).
- One call to action across the whole sequence.

## Instagram story frame

- Canvas 1080 x 1920.
- Text safe area: 250px from top, 340px from bottom, 80px sides.
