# 🏆 FIFA World Cup 2026 Predictor

An unofficial, free, single-file fan tool for predicting the 2026 FIFA World Cup. Fill in match scores, see live standings, rank the best third-place teams, build your knockout bracket, and export everything to Excel.

No framework. No build step. No backend. Just open `index.html` and go.

---

## Features

### Group Stage
- All 48 teams across 12 groups (A–L) with the real 2026 draw
- Enter match scores manually, or click a team name to quickly set them as the winner
- Live standings update automatically — points, wins, draws, losses, goals for/against

### Best 3rd-Place Teams
- All 12 third-place finishers are ranked together by points → goal difference → goals scored
- The top 8 advance to the Round of 32 (highlighted in amber)
- The bottom 4 are eliminated (highlighted in red)
- Updates live as you enter group results

### Knockout Stage
- Full bracket from Round of 32 → Round of 16 → Quarter-finals → Semi-finals → Final
- Group winners and runners-up auto-populate from your group results
- The best 8 third-place teams fill into the bracket automatically
- Third-place teams are marked with an amber left border so you always know who they are
- Click a team to advance them · Enter scores at every stage

### Excel Export
Download your full prediction as a `.xlsx` file with 5 sheets:
| Sheet | Contents |
|---|---|
| Group Standings | All 48 teams with W/D/L, GF, GA, GD, points, and qualification status |
| Best 3rd Places | All 12 third-place teams ranked, with advance/eliminate status |
| Group Matches | Every group match with scores and result |
| Knockout Stage | Every knockout match with scores and winner |
| Summary | Champion, semi-finalists, and best 3rd-place teams at a glance |

---

## Getting Started

### Run locally
Just open `index.html` in any browser. No installation needed.

## Tech Stack

- **Vanilla HTML/CSS/JS** — no framework, no dependencies to install
- **[SheetJS (xlsx)](https://sheetjs.com/)** — Excel export, loaded from cdnjs
- **Flag emojis** — no image assets required

---

## License

The code in this repository is licensed under the [MIT License](LICENSE).

> The MIT license covers the source code only. Team names, tournament structure, and all related football data remain the property of their respective owners. The license does not grant any rights over FIFA's intellectual property.

---

## Disclaimer

This is an unofficial fan tool and is not affiliated with, endorsed by, sponsored by, or connected to FIFA, any national football association, or any official World Cup partner.

"FIFA", "FIFA World Cup", and related marks are registered trademarks of FIFA. All team names and national flags are used for informational and non-commercial purposes only. No official logos, badges, or crests are used.

This tool is free, non-commercial, and intended for personal entertainment only.
