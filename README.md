# WortBlitz

A German vocabulary flashcard app with spaced repetition, built for learners targeting B2 proficiency.

## Features

- **Flashcards** — Leitner spaced repetition system (5 boxes, intervals: 0, 1, 3, 7, 14 days)
- **Learn Mode** — Focused sessions: pick "Not Learned", "Due for Review", or "All Words"
- **Browse** — Search and filter all words by Lektion with mastery indicators
- **Stats** — Track streak, daily reviews, learned vs not-learned, per-Lektion progress
- **Trilingual** — German words with English + Russian translations
- **Offline-first** — All data stored in localStorage, works without internet
- **Keyboard shortcuts** — Space/Enter to flip/reveal, Arrow keys to answer

## Word List

180+ curated words from Lektionen 5-15, covering:
- Everyday objects, colors, materials (L5)
- Work & communication (L6)
- Hobbies & abilities (L7)
- Days, time & places (L8)
- Food & drink (L9)
- Travel & transport (L10)
- Shopping & past tense (L11)
- Weather & seasons (L12)
- City & housing (L13-15)

## Tech Stack

Single-file HTML/CSS/JS — no frameworks, no build step, no dependencies.

## Getting Started

Just open `index.html` in any browser. That's it.

Or serve locally:
```bash
npx serve .
```

## License

MIT
