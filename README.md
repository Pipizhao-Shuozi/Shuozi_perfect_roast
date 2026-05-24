# Perfect Roast

Perfect Roast is a mobile-first HTML Canvas mini game inspired by campfire roasting and casual arcade timing games.

Players drag a rotating skewer to bounce food in the air, roast it to the perfect stage, and drop it at the right moment before it burns.

## What This Demo Includes

- Single-file browser game built with HTML, CSS, and vanilla JavaScript
- Mobile-friendly portrait layout for phone demos and screen recordings
- Two gameplay levels with increasing pace and obstacles
- Campfire-themed objects including logs, sparks, butter boost, and heart drops
- Cosmetic shop with skewer skins, face skins, and food skin switching
- Food skin modes:
  - `Marshmallow` for a North America campfire feel
  - `Banana` for a Southeast Asia inspired roast variant

## How to Play

- Drag the skewer tip
- Bounce the food 3 times
- Drop it when golden
- Avoid over-bouncing and burning the batch

## Controls

- `Touch / Mouse drag`: move the skewer tip
- Best experience: mobile portrait view

## Tech Stack

- `HTML5 Canvas`
- `Vanilla JavaScript`
- `Tailwind CSS` via CDN
- `Font Awesome` via CDN

## Project Files

- [perfect_roast.html](./perfect_roast.html): main game file and the correct demo entry
- [bbq_background.png](./bbq_background.png): game background asset
- [rules.pdf](./rules.pdf): supporting project document

If you are opening or deploying this project, use `perfect_roast.html` as the source of truth.

## Run Locally

Because this is a static web project, you can run it in any simple local server.

Option 1:

- Open `perfect_roast.html` directly in a browser

Option 2:

- Serve the folder with any static server
- Then open `perfect_roast.html` on your local URL

## Demo Goals

This prototype is designed for:

- mobile showcase demos
- portfolio presentation
- quick playtesting
- lightweight web deployment

## Notes

- Gameplay logic is implemented directly in the HTML file for fast iteration
- Cosmetic skins do not change the core scoring or physics rules
- The game is optimized for casual, TikTok-style, short-session play
