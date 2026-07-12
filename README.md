# Oedipus-Rex

An interactive companion to Sophocles' *Oedipus Rex*, exploring its characters,
themes, plot, historical context, and enduring ideas.

It is a single, self-contained web page — all HTML, CSS, and JavaScript in one
file, no dependencies, no build step, works offline. A companion for reading the
play, not the play itself.

## View it

- **Live:** https://bip-river.github.io/oedipus-rex/
- **Locally:** open [`index.html`](index.html) in any modern browser. That's all —
  there is nothing to install or compile.

## What's inside

Four ways into the play, plus a page for every figure in it:

- **Themes** — the four questions the play turns on: fate and the oracle, sight and
  blindness, plague and pollution, identity and origin.
- **The Investigation** — the reveal step by step, following the evidence as it
  gathers and the murderer turns out to be the hunter.
- **The House** — the family tree that folds back on itself.
- **Index** — an A–Z of every character, place, and idea, each with its essence in
  a line.

Any highlighted name can be tapped or hovered for a one-line who's-this and a
pronunciation, and links throughout let you move between related figures.

## Deployment

The site is published to GitHub Pages by the workflow in
[`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml), which
runs on every push to `main`. To enable it, set **Settings → Pages → Build and
deployment → Source** to **GitHub Actions**.

## License

See [LICENSE](LICENSE).
