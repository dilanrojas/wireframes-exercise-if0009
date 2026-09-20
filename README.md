# Wireframe Speedrun — Clothing Store Catalog

Single-file HTML game: assemble the wireframe for a clothing store catalog page against the clock.

File: `index.html` — no dependencies, no build step. Just open it in a browser.

## How to run

Open `index.html` in any modern browser (desktop or mobile). No server required.

## How to play

1. Enter a name / nickname and press **Iniciar Desafío**.
2. Place pieces **A–H** into zones **1–8**. Pieces **I** and **J** are distractors — leave them out.
3. Move pieces by dragging, or tap a piece then tap a zone. Tap a placed piece to return it to the bank.
4. Press **Validar Wireframe** to check. Errors are highlighted and the timer keeps running.
5. When all 8 zones are correct you win — take a screenshot to show the presenter.
6. **Devolver piezas** clears the board (timer keeps running).

## Solution

| Zone | Name | Piece |
|------|------|-------|
| 1 | Encabezado | A · Header (logo, search, cart) |
| 2 | Categorías | B · Category pills |
| 3 | Promoción destacada | C · Hero Banner |
| 4 | Filtros / Orden | D · Filters |
| 5 | Productos | E · Product grid |
| 6 | Paginación | F · Paginator |
| 7 | Beneficios | G · Shipping / warranty / payments |
| 8 | Pie de página | H · Footer |
| — | Distractors (leave out) | I · Payment form, J · Terms |

## Notes

- Vanilla HTML + CSS + JS in one file, responsive layout.
- Timer starts on game start and stops only on a correct validation.
- Pieces are shuffled on each load.
