# Grad Ready: DESIGN.md

One spec for the app, the posters and the slides, so they look like the same product.
Format follows the DESIGN.md idea from [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) (MIT).
We borrowed structure and principles from the Notion, Stripe and Airbnb files. We did not borrow their colours, fonts or logos.

## Overview

Grad Ready is for a stressed Year 4 student, Marcus, who wants answers in one place and no surprises. The look is calm, flat and clear. Every alarming message comes with a next step.

- **One accent.** Teal is used for the main action and active states only, like Airbnb's single accent. Everything else is white, ink and soft tints.
- **Flat with hairlines.** Cards are white with a 1px border, as in Notion. Only floating things (toast, hot card, phone frame) get a shadow, and there is one shadow level.
- **Numbers line up.** Counts, clocks and percentages use tabular figures, as in Stripe's money cells.
- **Never pure black.** Text is a navy-tinted ink, as in Stripe and Airbnb.

## Colours

| Role | Light | Dark | Use |
|---|---|---|---|
| Accent | `#0b6e6e` | `#4fc9c4` | Primary button, active tab, links. Nothing else |
| Accent soft | `#d8eeed` | `#123a3b` | Active tab fill, info chips, header band |
| Ink | `#16212b` | `#e8eef2` | Headings and body text |
| Muted | `#55656f` | `#9bafbc` | Secondary text, captions |
| Line | `#d6dde2` | `#2a3945` | 1px borders and dividers |
| Surface | `#ffffff` | `#16202a` | Cards and panels |
| Surface 2 | `#f4f6f7` | `#1c2833` | Table heads, quiet fills |
| Page | `#eceff1` | `#0e151b` | App background |
| Good / soft | `#1d7547` / `#def2e6` | | Done, on track |
| Warn / soft | `#85560a` / `#fcefcf` | | Needs attention |
| Risk / soft | `#b3261e` / `#fbe2df` | | Missing, at risk, overdue |
| Cream | `#f7f1e3` | | Warm highlight for the "next step" card (poster and slides too) |

Rules:
- Teal is never used for body text or for large backgrounds. The dark poster ground is the one exception.
- Good, warn and risk always come with a word or icon, never colour alone.
- Risk red is a different red from the accent. Do not use the accent for errors.

## Typography

- **Headings:** Bricolage Grotesque, 600 to 700, line-height 1.1 to 1.2, slight negative letter-spacing (about -0.01em).
- **Body:** IBM Plex Sans, 400 and 500, line-height 1.5.
- **Numbers and clocks:** IBM Plex Mono 500, tabular figures.

| Level | Size | Weight |
|---|---|---|
| Screen title | 24px | 700 |
| Section title | 15 to 17px | 600 |
| Body | 15px | 400 |
| Secondary | 13 to 13.5px | 400 |
| Chip, label | 12.5px | 600 |
| Big number | 28 to 30px | 500 mono |

Posters scale the same families up: headline 100px (square) or 148px (landscape), benefits 34 to 36px.

## Shape and space

- Spacing steps of 4px; common gaps 8, 12, 16, 18.
- Radius: buttons 8px, inputs 9px, cards and lists 12px, panels 16px, chips pill-shaped, phone frame 42px.
- Shadow, one level: `0 1px 2px rgba(15,23,32,.04), 0 4px 12px rgba(15,23,32,.06)`.
- Touch targets at least 44px high.

## Components

- **Primary button:** teal fill, white text, 8px radius, 44px high. One per screen area.
- **Secondary:** ghost (teal outline) or quiet (grey fill). **Destructive:** red outline.
- **Banner:** soft tint, 4px left bar in the status colour, a short title, one sentence, then the action button.
- **Chip:** soft tint with a dot, e.g. Done, In progress, Missing.
- **Card:** white, 1px line, 12px radius. The "hot" card gets a teal border and the shadow.
- **Progress bar:** 10px, rounded, green fill.
- **Table:** turns into cards under 600px.
- **Countdown clock:** mono, large, turns red and says "Overdue" when late.

## Voice

Plain, short, reassuring. Say what is wrong, then what to do next.
- Yes: "1 requirement missing. Request a reserved seat."
- No: "Critical error: graduation at risk!"

## Do

- Show the one thing the student must do next, with a button.
- Keep status words consistent: Done, In progress, Missing.
- Keep sample data labelled as sample.

## Don't

- Add a second accent colour.
- Use pill-shaped primary buttons (chips and tabs can be pills).
- Stack several shadows or heavy drop shadows.
- Put text on a photo without a dark overlay.

## Responsive

- Phone first. On 960px and wider, the student view sits in a phone frame with presenter notes beside it. The Phone/Laptop switch overrides this for any role.
- Lists and tables never get a fixed height that can squash their content.

## Posters

- Same teal, ink and fonts. Dark teal ground `#0c4a4a`, white cards, one warm highlight line in `#f0c15a`.
- Headline, three benefits, one call to action with a QR code. Nothing else.
- Sizes: square 1080×1080 (Telegram), landscape 1920×1080 (screens), vertical 1080×1920 (story, optional).
- Every poster needs the real QR code and launch details before it goes out.
