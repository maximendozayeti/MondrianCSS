# CSS Mondrian Project

A small layout exercise recreating a **Piet Mondrian–style abstract painting** using pure HTML and CSS Grid.

## Project Files

- `index.html` – Your implementation of the Mondrian layout.
- `solution.html` – Reference/solution implementation for comparison.

## What It Demonstrates

- **CSS Grid layout**
  - Fixed-size grid: `748px × 748px`
  - Custom `grid-template-columns` and `grid-template-rows` to match the original artwork.
  - Use of `gap` to simulate the black grid lines.
- **Grid item positioning**
  - `grid-column`, `grid-row`, and `grid-area` to create larger white blocks.
- **Color blocking**
  - Background colors that match Mondrian’s palette:
    - Line/Gap: `#000000`
    - White: `#F0F1EC`
    - Red: `#E72F24`
    - Blue: `#004592`
    - Yellow: `#F9D01E`
    - Black: `#232629`
- **Centering the artwork**
  - `body` uses Flexbox to center the painting vertically and horizontally.

## How to Run

1. Open the project folder `10.3 Mondrian Project`.
2. Double-click `index.html` to open it in your browser.
3. (Optional) Open `solution.html` in another tab to compare your version with the reference.

## Key Concepts Practiced

- Combining **Flexbox (for page centering)** with **CSS Grid (for internal layout)**.
- Using **grid tracks and gaps** to emulate a precise visual composition.
- Managing **class-based styling** to reuse common styles (`.item`) and add variations (`.red`, `.blue`, `.yellow`, etc.).

## Possible Extensions

- Make a responsive version that scales the painting while keeping proportions.
- Add comments in the CSS explaining each region.
- Experiment with different Mondrian-style compositions by changing row/column sizes and item spans.
