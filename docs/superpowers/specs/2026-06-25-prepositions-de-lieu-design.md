# French Prepositions of Place — Interactive Game

## Overview

A single HTML file interactive quiz for learning French prepositions of place (SUR, SOUS, DANS) at A1 level, with instructions in English (A2 level). Theme: "Où est le chat?"

## Structure

1. **Header** — Title "Où est le chat? 🐱", subtitle/instructions in simple English
2. **Mini cheat-sheet** — Table with SUR, SOUS, DANS, translations, and examples
3. **6 question cards** — Each showing a cat-in-context emoji scene, question "Où est le chat?", two answer buttons (a/b), click to reveal correct/incorrect with explanation
4. **Progress bar** — "Répondu: X/6"
5. **Final summary table** — All 6 answers with preposition and meaning

## Questions

| # | Scene | Correct answer | Preposition |
|---|-------|---------------|-------------|
| 1 | Cat under bed | a. Le chat est SOUS le lit | SOUS |
| 2 | Cat on bed | a. Le chat est SUR le lit | SUR |
| 3 | Cat under blanket | a. Le chat est SOUS la couverture | SOUS |
| 4 | Cat in a box | a. Le chat est DANS une boîte | DANS |
| 5 | Cat peeking from under bed | b. Le chat est SOUS le lit | SOUS |
| 6 | Cat hidden under blanket | a. Le chat est SOUS la couverture | SOUS |

## Interaction

- Click an answer → lock choice, highlight green (correct) or red (incorrect), show explanation
- Cannot change answer after selection
- Progress bar updates on each answer
- Final summary table automatically populated

## Audio (Speech)

- Speaker button 🔊 next to each phrase in questions and cheat-sheet
- Uses browser's Web Speech API (SpeechSynthesis) — no audio files needed
- French voice selected when available (lang="fr-FR")
- Plays: "Où est le chat?", answer phrases like "Le chat est SUR le lit", example phrases from cheat-sheet

## Visual Design

- Warm orange/cream palette with French flag accent colors (blue, white, red)
- Large readable font
- Card layout with rounded corners and subtle shadows
- Emoji-based visuals (no external images)

## Technical

- Single self-contained HTML file
- No external dependencies
- Inline CSS and vanilla JavaScript
- Responsive layout

## Files

- `index.html` — the game
