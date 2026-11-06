# Ajwaa Seating – demo

Interactive Arabic demo of wedding seating for Ajwaa invitations, using sample data for a fictional wedding (Youssef & Laila).

- **`#planner` – ترتيب القاعة:** a real top-down photo of the hall (kosha, dance floor, aisle, 12 numbered tables) with clickable tables placed over it. Drag (or tap) families who confirmed their RSVP onto tables, see seats left per table, and auto-arrange the rest by family side.
- **`#guest` – تجربة الضيف:** a guest picks their name from an A–Z list (no typing), scratches a card to reveal their table number, and a mini map shows the way from the door.

Single static file (`index.html`, the hall photo is embedded in it), no build step. The original photo is in `assets/hall-top-view.jpg` (generated with Google Flow). Seating changes are saved only in the visitor's own browser, so every visitor gets a clean demo.

Contact: [Ajwaa on Instagram](https://www.instagram.com/ajwaa.eg_26/?hl=en)
