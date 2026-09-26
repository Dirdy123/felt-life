# The Felt Life

A minimalist single-page site that shows your life in weeks and estimates how much of it you have *felt*, using a logarithmic model of time perception (Janet, 1877):

```
felt share = ln(age / m) / ln(lifespan / m)     m = age of earliest memory
```

It ends with research on how novelty, fulfillment, relationships and presence make time feel longer when you look back on it.

A single static `index.html` with no build step, served by GitHub Pages. All calculations run in the browser.
