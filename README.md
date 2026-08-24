# Downtime Arcade

A small collection of self-contained, offline browser games. No build step,
no server, no accounts — open an HTML file and play.

## Play

Open [`index.html`](index.html) — it links to both games below. Or open
either file directly:

- **[`downtime_1.html`](downtime_1.html)** — Task Manager: Word Guess,
  Codebreaker (cryptograms), Memory, Reflex, Sudoku, Checkers, Damas Chinas,
  and a set of Analyst Training mini games (Morse code, logic deduction,
  pattern spotting) with a Tradecraft reference tab.
- **[`arena.html`](arena.html)** — Arena Log: a small idle RPG. Recruit
  heroes, gear up, and push through a campaign of stages.

Everything runs entirely client-side and saves progress to `localStorage` —
no data leaves your browser.

## Boss key

Press **Esc** in either game (or the landing page) to instantly switch to a
fake spreadsheet view. Press Esc again, or click Close, to return.

## Development

There's no build process. Each `.html` file is self-contained (HTML, CSS,
and JS inline) — edit and reload.

## License

This project's code is licensed under the [MIT License](LICENSE). It also
bundles a Spanish word list under a separate Apache-2.0 license — see
[`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) for details.
