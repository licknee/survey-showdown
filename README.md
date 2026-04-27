# Survey Showdown

A Family Feud-style party game you can play right in your browser. No install needed.

## Play now

Open `index.html` in any browser, or visit the hosted version on GitHub Pages.

## How it works

1. **Set up** - Name your two teams, then add survey-style questions with answers and point values. You can type them manually or upload a CSV file.
2. **Face off** - Each round, the host reads the question aloud. Teams try to guess the most popular answers on the board.
3. **Reveal & strike** - The host reveals correct answers by clicking tiles (or pressing 1-8). Wrong guesses get a strike - three strikes and the other team can steal!
4. **Score** - Award the round's points to the winning team. Most points at the end wins!

## Features

- Custom questions via form or CSV upload
- Two-team scoreboard with active team indicator
- Flip-reveal animations and sound effects
- Strike overlay (the big red X)
- **Audience Display** - open a second window for a TV/projector with larger text and no host controls, synced in real-time
- Keyboard shortcuts: `1-8` reveal answers, `X` strike, `S` switch teams, `N` next round
- Confetti and victory fanfare for the winner
- CSV template included for easy question prep

## CSV format

Use `survey-showdown-template.csv` as a starting point. Each row is one round:

```
Question, Answer 1, Points 1, Answer 2, Points 2, ... (up to 8 answers)
```

Leave trailing columns empty for rounds with fewer answers.
