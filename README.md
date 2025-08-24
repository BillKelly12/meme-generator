# Meme Generator (React + Vite)

Tiny app to generate a meme: type a **top** and **bottom** caption, then fetch a **random meme image** from Imgflip.

## How it works
- On mount, it fetches the meme list from `https://api.imgflip.com/get_memes` and stores it in state.
- The “Get a new meme image” button picks a random URL from that list and updates the image.
- Inputs update the top/bottom captions in state and render over the image. :contentReference[oaicite:0]{index=0}

## Tech
- React + Vite

## Scripts
```bash
npm install
npm run dev       # start locally
npm run build     # production build (dist/)
