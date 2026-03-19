# Dad's Puzzle Legacy Memory Match

Here is your complete Dad's Puzzle Legacy Memory Match game — just copy the code in `index.html` into a file called `index.html` and open it on any tablet (or desktop). It works in any modern browser.

## How to Customize in 2 Minutes

1. **Open `index.html`** and find the `CONFIG` object near the top (look for `← CHANGE THESE` comments).
2. **Player name**: Change `playerName: "Dad"` to any name.
3. **Family photos**: Replace the `familyPhotoUrls` array with your own image URLs or base64 data URLs. Use [base64-image.de](https://www.base64-image.de/) or similar to convert photos. Each URL is used for one jigsaw pair (4 pairs = 4 different photos).
4. **Cryptogram messages**: Edit `cryptogramMessages` with personal messages like "We love you Dad!" or inside jokes.
5. **Mahjong tiles**: The default uses Unicode Mahjong characters. You can swap in different emoji from `mahjongTiles` if some don't render on your device.
6. **Word Search pairs**: Scroll to `WORD_SEARCH_PAIRS` and change `word` and `clue` to your own word/clue combinations.

Save the file and refresh the browser. No build step required.

## Emoji-Only Version

Use `index-emoji.html` if you prefer zero external images — jigsaw cards use emoji placeholders (🧩) instead of photos. Ideal for offline use or when image hosting isn't available.

## Features

- **6×6 grid** (18 pairs) by default; toggle to **4×4** for beginner mode
- **Four themed card types**: Mahjong tiles, Jigsaw halves, Word Search (word + clue), Cryptogram (encrypted + decoded)
- **Puzzle Legacy progression**: Progress bars, mini word search at 8 matches, jigsaw assembly at 12, cryptogram message at 16
- **Sound effects** via Web Audio API (works offline)
- **Tablet-first**, touch-friendly, accessible (ARIA labels)
