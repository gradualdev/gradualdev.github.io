# Portfolio design notes

These notes record the current design and the owner's preferences. Read them before changing the page. The working implementation remains in index.html; this document is guidance, not a stylesheet.

## Direction

- A clean, restrained personal introduction page, written in English.
- Display name: Ho JoonSoo. Keep the actual GitHub account URL unchanged.
- Favor whitespace, concise text, thin dividers, and simple sections.
- Avoid dashboard styling, neon effects, decorative waveforms, oversized slogans, and unnecessary visual elements.
- Extend the existing layout as new work is added.

## Colors and typography

- Background: #fbfcfb.
- Main text: #192122; secondary text: #687577.
- Dividers: #dce4e3; green accent: #126c5a.
- Manrope for body text and headings; DM Mono for navigation, dates, and small labels.
- Use green sparingly for links and supporting labels.

## Layout

- Centered content, maximum width 880px; horizontal padding 28px on desktop and 20px on mobile.
- Intro: 180px portrait at the upper left, brief biography to its right, with a 40px gap.
- Career: dates and institution logos in the left column; role and description in the right column.
- Keep Focus, Interests, and Contact below the introduction and career entries.
- At widths of 620px or less, stack the intro and career columns; put the portrait before the biography.
- Preserve comfortable section spacing and thin dividing lines.

## Images and interaction

- Preserve image proportions and show the entire portrait, flag, and institution logos.
- Institution logos share a centered 140 × 120px area. Account for source whitespace without clipping the artwork or using translation offsets.
- Use the supplied local assets. Do not substitute a multi-variant logo sheet or redraw the supplied flag.
- The portrait is a button: clicking flips it to the supplied South Korean flag and Ho JoonSoo; clicking again restores the photo.
- Keep the restrained 600ms flip, keyboard operation, visible focus outline, and reduced-motion support.
- Check logo alignment and both portrait faces in the browser after changing image sizing or layout.

## Content

- Use factual, concise descriptions. Distinguish completed experience from planned work.
- Interests include Circuit Design, Analog & Mixed-Signal IC Design, Processing-in-Memory (PIM), Computer Architecture, Memory Systems, and Hardware–Software Co-design.
- Contact entries use working tel: and mailto: links.
- Do not invent project results, metrics, or credentials.
