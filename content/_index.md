+++
title = "zola-quiet"
template = "index.html"
+++

<pre class="whoami">
$ whoami
zola-quiet
  a quiet two-skin Zola theme
  - typography skin (minima-flavoured)
  - terminal skin (monospace)
  light/dark toggle on the right
  skin toggle next to it
</pre>

Two stylesheets ship in this theme. Hit the **type** / **terminal**
glyph in the top-right corner to flip between them at runtime — no
rebuild, just a `<link href>` swap with the choice saved to
`localStorage`. Hit the **sun** / **moon** next to it to flip between
light and dark, also persisted.

## &gt; what it ships

- A Minima-flavoured typographic skin (`style.css`) and a
  monospace terminal skin (`style-terminal.css`).
- Sun/moon dark-mode toggle with system-preference fallback and no
  flash-of-light-mode on cold loads.
- A `<div class="addendum">` convention for adding a dated extension
  to a post after it was originally published.
- An iframe `postMessage` protocol for hosting interactive
  visualisations next to posts and syncing theme + height with the
  parent page.
- `xkcd` shortcode for attribution-correct comic embeds.

## &gt; get started

```bash
git submodule add https://github.com/johnnybravo-xyz/zola-quiet themes/zola-quiet
# then in your config.toml:
# theme = "zola-quiet"
```

See the [README](https://github.com/johnnybravo-xyz/zola-quiet) for
the `[extra]` keys the templates read and the conventions baked in.
