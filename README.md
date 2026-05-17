# Writing

Essays by Manny Yebz.

Live site: **https://mannyyebz.github.io/writing**

A hand-built static site — pure HTML and CSS, no frameworks, no build step.

## Structure

```
index.html                              Portfolio landing page
essays/<slug>.html                      Individual essay pages
.nojekyll                               Tells GitHub Pages to serve files as-is
```

## Adding a new essay

1. Create `essays/<slug>.html` using `essays/against-the-necessary-wound.html` as a template.
2. Add a new `<li>` entry to the `<ul class="essays">` block in `index.html`.
3. Commit and push.

### Numbering

Essays are not numbered sequentially. Each piece carries a Roman numeral pulled
from a meaningful figure inside the essay itself — a count, a date, a move, a
year. The index is a labyrinth, not a queue. Pick the number that the piece
quietly insists on.

- `xiv` — *Against the Necessary Wound* (the fourteenth reading of Zosima's passage)
- `xxiv` — *Queen Blunder on Move 24*
- `xxxi` — *The Long Side of the Door* (the thirty-one nights on the bench)
