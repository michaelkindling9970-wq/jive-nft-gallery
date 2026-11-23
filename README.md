# NFT Art by Michael Kindling

A static gallery of 44 NFT artworks by Michael Kindling, made for The Jive 88.1.

The page is a single `index.html` file. Thumbnails and OpenSea links are public; the page itself does not use an API key.

## What's included

- **Originals (6)** from the [Abstract Contemplation](https://opensea.io/collection/abstract-contemplation-1) collection, listed first
- **Minty NFT Collection (38)** after the originals
- Each card links to the artwork on OpenSea

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

## Deploy

This is a free Render static site. It publishes the repo root with no build step (`buildCommand` is `true`, publish path is `.`).
