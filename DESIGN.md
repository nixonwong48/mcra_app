# Grad Ready: DESIGN.md

One spec for the app, the posters and the slides, so they look like the same product and match the class deck (SMU-style navy and indigo).

## Overview

Grad Ready helps Marcus manage graduation and hiring deadlines. The look is clean and lively: off-white surfaces, a navy header band, filled navy buttons, indigo highlights and one yellow accent word per headline. Every warning comes with a next step.

## Colours

| Role | Value | Use |
|---|---|---|
| Navy (primary) | `#151c55` | Header band, primary buttons, selected segment, headings |
| Indigo (brand) | `#3347b0` | Logo tile, selected tab text, info chips, links |
| Yellow (accent) | `#f2c14e` | One highlighted word in a headline. Nothing else |
| Ink | `#1b2150` | Body text |
| Muted | `#5a6070` | Secondary text |
| Page | `#f7f7f5` | Background |
| Surface | `#ffffff` | Cards |
| Surface 2 | `#f2f4fa` | Table heads, progress track |
| Line | `#e1e4ee` | 1px borders |
| Soft indigo | `#e8ecf8` | Active tab, info chip |
| Good / soft | `#1d7547` / `#def2e6` | Done, on track |
| Warn / soft | `#85560a` / `#fcefcf` | Needs attention |
| Risk / soft | `#b3261e` / `#fbe2df` | Missing, clash, overdue |

Rules: status colours always come with a word (Done, In progress, Missing). Risk red is only for problems. Yellow is only for the highlighted headline word.

## Typography

IBM Plex Sans for text, IBM Plex Mono for clocks and numbers (tabular figures). The posters use Inter to match the deck.
Screen title 26px bold, section title 15px semibold, body 15px, secondary 13px, chips 12.5px semibold.

## Shape and space

Radius: buttons 8px, cards 12 to 14px, phone frame 42px, chips pill. Spacing in steps of 4px. One soft shadow level. Touch targets at least 44px.

## Components

- **Header band:** navy, with the Grad Ready mark, the view name in small caps, a headline with one yellow word, and the student line.
- **Primary button:** navy fill, white text, 8px radius. **Ghost:** navy outline. **Danger:** red outline.
- **Banner:** soft status tint with a 4px bar on the left, a short title, one sentence, then the action.
- **Calendar day with a clash:** navy 1.5px border, red clash strip, "Request leave" button.
- **Progress bar:** 10px, green fill.

## Voice

Plain, short, reassuring: say what is wrong, then what to do next.

## Responsive

Phone first. On wide screens the app can sit in a phone frame next to the presenter guide; the Phone/Laptop switch overrides it. Lists never get a fixed height that squashes their content.

## Posters

Same navy, indigo and yellow, Inter type. Headline, three benefits (ONE PAGE, WEEK 3, 48 HOURS), a QR code and "Sample data". The posters live in the team's design canvas, not in this repo.
