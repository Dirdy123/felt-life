# The Felt Life

**How much of your life have you already felt?**
Live: https://dirdy123.github.io/felt-life/

Enter your age, the age you expect to live to, and the age of your earliest memory. The page then shows:

- **Your life in weeks**, one row per year. Toggle between *how it feels* (early years drawn tall, later years thin) and *on the calendar* (every year the same size).
- **Your life playing out**, where each year lasts as long as it feels. Childhood takes seconds, later decades flash past.
- **Why life seems to speed up**, and what research suggests makes years feel longer when you look back.

## The model

Paul Janet (1877) suggested that a year feels as long as the share of your life it makes up. Adding up a lifetime of shrinking years gives a logarithm, counted from your earliest memory:

```
felt so far = ln(age / m) / ln(lifespan / m)     m = age of earliest memory
```

This is a thought experiment, not a measurement. The "How it works" panel on the site covers what the evidence does and doesn't support, including a square-root alternative (Lemlich, 1975) and the main counterarguments.

## How it's built

One static `index.html` with no build step and no third-party requests, served by GitHub Pages. Everything is calculated in the browser; nothing entered is sent anywhere. The fonts (Archivo and Newsreader, SIL Open Font License) are served from `fonts/`, and `og.png` is the link preview image.

To run it locally, open `index.html` in a browser.

## Credits

Inspired by Tim Urban's *Your Life in Weeks* and Maximilian Kiener's *Why Time Flies*. Full sources are listed in the site's "How it works" panel.

Feedback and ideas: [open an issue](https://github.com/Dirdy123/felt-life/issues).
