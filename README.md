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
