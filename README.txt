# A Little World Just for You ♡

A customizable birthday surprise website with a passcode entrance, interactive questions, animated cake, memory scrapbook, cozy evening scene, gift boxes, star messages, digital hug and birthday letter.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or upload the folder to GitHub Pages / Netlify.
3. For best results, use a small local web server or free static hosting so photos and audio load consistently.

## Personalize it
Open `script.js`. The `CONFIG` section at the top contains:
- `herName`
- `passcode` (default: `143`)
- `memories` (six image paths and captions)
- `gifts`
- `starMessages`
- `letter`
- `finalMessage`
- `musicFile`

## Add photos and music
Put your images in `assets/` and name them `memory-1.jpg` through `memory-6.jpg`, or change the paths in `script.js`.
Put your chosen audio file at `assets/your-song.mp3`, or change `musicFile`.

## Important
The passcode is a playful front-door interaction only. Because this is a static website, the code and its files can be inspected by visitors. Do not put private or sensitive content in a publicly hosted version. Use photos you are comfortable sharing.

The site uses Google Fonts when online. It has CSS-based 3D styling and animations and does not require a build step.
