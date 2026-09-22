# Bellman Meets Lyapunov — anonymous project page

Static, single-file project page for the ICLR 2027 submission
*Bellman Meets Lyapunov: Unsupervised Reinforcement Learning Through Mastering Chaos*.

## Layout

```
index.html               the whole site (no build step)
assets/figures/          Figure 1 strips, method schematic, Lorenz figure, gibbon strip
assets/videos/           walker/hopper six-way comparisons (hero), walker/hopper F-CIP-only clips
```

Equations are rendered by MathJax 3 from cdnjs, so the page needs network access for that;
everything else is local. Fonts are the system font stack.

## Preview locally

```
python3 -m http.server 8000
```

then open <http://localhost:8000>. Opening `index.html` directly from Finder also works.

## Deploy anonymously

Any static host works. To stay anonymous, host it from an account that does not reveal the
authors, for example a fresh GitHub account with GitHub Pages (Settings → Pages → `main`, root),
or Netlify Drop. Do not host it under a personal or lab GitHub account.

## Anonymity checklist

- No author names, affiliations, emails, or acknowledgements appear on the page.
- `<meta name="robots" content="noindex">` keeps search engines from indexing it.
- The paper PDF is intentionally not hosted here; the submission itself lives on OpenReview.
- The Code button points at the anonymous 4open.science link from the paper.
