# Grad Ready: DESIGN.md

One spec for the app, the posters and the slides, so they look like the same product.
Format follows the DESIGN.md idea from [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) (MIT).
We borrowed structure and principles from the Notion, Stripe and Airbnb files. We did not borrow their colours, fonts or logos.

## Overview

Grad Ready helps Marcus manage graduation and hiring deadlines. Use a white, practical interface with charcoal actions, light grey borders and restrained status colours. Keep the app light even when the operating system uses dark mode.

## Colours

| Role | Colour | Use |
|---|---|---|
| Page / surface | `#ffffff` | Background, cards and headers |
| Surface 2 | `#f7f7f7` | Quiet fills and table headings |
| Ink | `#242424` | Headings and body |
| Muted | `#666666` | Secondary text |
| Line | `#e3e3e3` | Borders and dividers |
| Action | `#303030` | Primary buttons and active controls |
| Action soft | `#f1f1f1` | Selected tabs and neutral chips |
| Good / soft | `#1d7547` / `#f4f8f5` | Done and on track |
| Warn / soft | `#85560a` / `#fbf8f0` | Needs attention |
| Risk / soft | `#b3261e` / `#fcf5f4` | Missing and overdue |

Use status words alongside colour. Headers stay white; avoid gradients and large tinted panels.

## Typography

- **Headings:** IBM Plex Sans, 600 to 700, line-height 1.1 to 1.2, slight negative letter-spacing (about -0.01em).
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

- **Primary button:** charcoal fill, white text, 8px radius, 44px high. One per screen area.
- **Secondary:** ghost (charcoal outline) or quiet (grey fill). **Destructive:** red outline.
- **Banner:** soft tint, 4px left bar in the status colour, a short title, one sentence, then the action button.
- **Chip:** soft tint with a dot, e.g. Done, In progress, Missing.
- **Card:** white, 1px line, 12px radius. The "hot" card gets a charcoal border and the shadow.
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

- Add decorative accent colours.
- Use pill-shaped primary buttons (chips and tabs can be pills).
- Stack several shadows or heavy drop shadows.
- Put text on a photo without a dark overlay.

## Responsive

- Phone first. On 960px and wider, the student view sits in a phone frame with presenter notes beside it. The Phone/Laptop switch overrides this for any role.
- Lists and tables never get a fixed height that can squash their content.

## Posters

Match the white background, charcoal type and IBM Plex fonts. Use status colour only when it communicates meaning.

- Headline, three benefits, one call to action with a QR code.
- Sizes: square 1080×1080 (Telegram), landscape 1920×1080 (screens), vertical 1080×1920 (optional).
- Every poster needs the real QR code and launch details before it goes out.

## Phone content hierarchy

Use short action-led copy and separate bordered cards for each task. Show missing requirements first; keep completed items in an expandable group. Career uses three numbered sections and individual day cards. Presenter guidance stays in an expandable panel outside the student screens. Inputs use at least 16px type on mobile.
