# OSRS TCG card printer

A local-only A4 PDF layout tool for personal, non-commercial OSRS TCG fan-card printing. Drag in PNG card fronts and generate precisely sized 59 × 86 mm card sheets with lossless PNG handling, 3 mm bleed, trim marks, and optional card backs.

Repository: <https://github.com/gfxhlab/OSRS-TCG-Card-Printer>

## Download

- GitHub: select **Code → Download ZIP**, then extract it.
- Git: `git clone https://github.com/gfxhlab/OSRS-TCG-Card-Printer.git`

No build step or package installation is required.

## Requirements

- Windows, Linux, or macOS
- A current Chrome, Edge, Firefox, or Safari browser
- An internet connection to load the pinned PDF library from jsDelivr
- Optional PNG cardback, selected in the app when needed

## Start the app

Open `card-printer/index.html` directly in your browser. No server, Python, Node.js, or build step is required.

## Create a PDF

1. On <https://osrs-tcg.net>, use **Inspect Card**, then **Save PNG**.
2. Drag the saved PNG fronts into the app, or choose them with the file picker.
3. Select up to 9 cards. Their order is the order they are added.
4. Leave **Include card backs** unchecked for fronts only. To add backs, check it and choose your locally saved `cardback.png`.
5. Click **Generate PDF**. The timestamped PDF downloads automatically.

## Print layout

- Finished card: 59 × 86 mm
- Bleed: 3 mm on each side
- Trim gap: 6 mm
- Maximum: 9 cards per A4 sheet
- Card backs use the same positions as the fronts

Print the PDF at **100% / Actual size** on A4. Do not use **Fit to page** or borderless scaling.

## Copyright and usage notice

This is an unofficial fan-made utility. It is not affiliated with, endorsed, or sponsored by Jagex Limited. OSRS, Old School RuneScape, RuneScape, Jagex, and related game content are owned by Jagex Limited and/or its licensors.

Created using intellectual property belonging to Jagex Limited under the terms of Jagex's Fan Content Policy. This content is not endorsed by or affiliated with Jagex.

Use this tool and any game artwork only for personal, non-commercial purposes. Do not sell, license, redistribute, or monetize the printed cards, artwork, or this tool's generated files. `Cards/` and `cardback.png` are intentionally excluded from version control; do not commit or publish artwork unless you have permission from its rights holder.

Jagex's Fan Content Policy can change and does not replace legal advice. For any commercial use or use outside that policy, obtain permission from Jagex or the relevant rights holder first.

## Third-party software

The app loads the pinned `pdf-lib` 1.17.1 library from jsDelivr at runtime. It is distributed under the MIT License. See `THIRD-PARTY-NOTICES.md`.
