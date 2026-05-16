# Candles Meme Generator

A loving tribute to [@dril's budget tweet](https://x.com/dril/status/384408932061417472?lang=en) (29 Sep 2012). Drop in your own item, handles, and avatars; export the 3-tweet conversation as a PNG styled like 2012 Twitter.

## Live

→ **https://bojanrajkovic.github.io/candles-meme-generator/**

## What it does

- Renders a 3-tweet conversation: original budget post → unhelpful advice reply → canonical "no" comeback
- You change: the bolded budget item ("Candles" → whatever), display names, @handles, avatars
- Locked to original dril values: date (`29 Sep`), price (`$3,600`), closing plea, reply scaffold, comeback (`no`)
- Auto-prefetches profile images from X (via [unavatar.io](https://unavatar.io)) when you type a handle
- One-click PNG download, plus copy-to-clipboard

## Run locally

```sh
open index.html
```

That's it. No build, no install. Single static HTML file with two CDN dependencies (`html-to-image` for the PNG export, `unavatar.io` for X profile images).

## Why

The dril candles tweet is one of the most-quoted social-media artifacts of its decade. Every snowclone deserves the right chrome around it.
