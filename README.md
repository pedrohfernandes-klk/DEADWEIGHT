# DEADWEIGHT

**DEADWEIGHT** is a single-page text tool for cutting drag.

It gives the user one sharp instruction at a time: name the unnecessary weight, drop it, and move lighter. The app is part of the broader **SPARK TOOLS** family: small browser-based writing, thinking, and reframing machines built around compact text, strong visual identity, and fast interaction.

## Concept

DEADWEIGHT is a subtraction engine.

It is not a productivity app, a therapy tool, or a task manager. It is a blunt little machine for noticing what is being carried past its usefulness: stale obligations, old fear, emotional ballast, digital clutter, overbuilt systems, inherited defaults, circular delay, false safety, and beautiful excuses.

The logic is simple:

> Press **DROP...**
> Read the cargo.
> Decide what no longer deserves room.

## Core Interaction

The app displays one card at a time from a 999-card deck.

Each card names a form of drag, for example:

> the familiar burden with a pet name. Affection does not reduce mass.

The card itself appears without a prefix. When copied, the app formats the text as:

```text
DROP the familiar burden with a pet name. Affection does not reduce mass.

DEADWEIGHT
```

This keeps the screen clean while making copied outputs feel complete, stamped, and shareable.

## Features

* 999-card curated text deck
* One-card-at-a-time random draw
* No visible `DROP` prefix inside the card display
* Copy output automatically adds `DROP`
* Simple **DROP...**, **COPY**, **CLEAR**, and **ABOUT** controls
* Animated icon drop on button press
* Impact-style card reveal animation
* Responsive single-file HTML design
* No dependencies
* No tracking
* No saved data
* No external assets required

## Design Direction

DEADWEIGHT uses the same sibling-app visual language as the rest of the SPARK TOOLS suite:

* dark terminal-like shell
* bold condensed title treatment
* compact status bar
* central output card
* restrained retro interface cues
* simple but memorable icon
* minimal controls
* mobile-friendly layout

The visual tone should feel direct, heavy, useful, and slightly comic without becoming silly.

## Text Standards

The card deck follows these rules:

* cards must be clear at first reading
* each card should name one piece of removable drag
* each line should feel usable, not decorative
* humour should come from precision, not randomness
* avoid vague self-help language
* avoid corporate productivity jargon
* avoid repeated openings
* avoid overexplaining
* avoid therapy-speak unless transformed into plain language
* no card should include `DROP` inside the deck itself

Preferred pattern:

```text
the [specific form of drag]. [short sharp consequence or release.]
```

Example:

```text
the plan built for a fictional adult. Build for the person who actually woke up.
```

## Technical Notes

DEADWEIGHT is built as a single HTML file containing:

* HTML structure
* CSS styling
* JavaScript engine
* full text-card deck

The app runs locally in any modern browser. No build step is required.

To use it:

1. Open the HTML file in a browser.
2. Press **DROP...** to generate a card.
3. Press **COPY** to copy the formatted output.
4. Press **CLEAR** to reset the card area.
5. Press **ABOUT** to view the short project description and deck count.

## Editing the Deck

Cards are stored in the JavaScript `CARDS` array.

Each card should be entered as a plain string:

```js
"the old fear with new paperwork. Ask whether it still has jurisdiction.",
```

Do not include the word `DROP` in the card string. The app adds that only when copying.

Before release, validate:

* total card count
* no duplicate full cards
* no duplicate cargo headings
* no accidental `DROP` inside the deck
* no contamination from other SPARK TOOLS apps
* copy output format remains correct

## Relationship to SPARK TOOLS

DEADWEIGHT belongs to a family of small text machines designed to provoke better thinking through constraint, humour, and friction.

Where other tools generate questions, bad advice, crooked definitions, false evidence, or counterarguments, DEADWEIGHT does one thing:

It asks what can be removed.

## Intended Use

Use DEADWEIGHT when something feels heavy but unnamed.

It can be used for:

* writing prompts
* creative blocks
* project resets
* decision fatigue
* emotional clutter
* digital decluttering
* reflective journaling
* workshop exercises
* personal review rituals
* playful self-interruption

It works best when the user does not ask, “What should I add?”

It works best when the user asks, “What am I still carrying?”

## Privacy

DEADWEIGHT runs entirely in the browser.

It does not collect, store, transmit, or analyse user input. No user account, server, database, or analytics layer is required.

## Status

Current version:

* 999 text cards
* complete single-file prototype
* sibling-style visual system
* icon-drop animation
* impact card reveal
* clean copy logic

## Licence

All rights reserved unless otherwise specified by the creator.
