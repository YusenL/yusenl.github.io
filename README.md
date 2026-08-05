# Yusen Liu — Research Website

A single-page academic website published at [yusen.website](https://yusen.website).

The site is based on Pascal Michaillat's MIT-licensed
[`hugo-website`](https://github.com/pmichaillat/hugo-website) template and its
bundled PaperMod theme, adapted into a one-page research profile.

## Development

Hugo 0.147.2 or newer is required.

```sh
hugo server -D
hugo --minify --cleanDestinationDir
```

Hugo writes the static site to `docs/`, which GitHub Pages publishes from the
`main` branch. The previous Hexo site remains available on the
`archive/legacy-hexo-2021` branch.
