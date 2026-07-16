# Category product simplification design

## Scope

Simplify the Products category grid in `index.html` by removing its product image panels. Retain the existing six responsive text entries, including numbering and descriptions. Rename the Pastry & Bakery category to Pastry wherever it is presented in the category strip and Products grid.

## Implementation

- Remove the image-container element from each of the six product-grid entries.
- Keep the grid, animation classes, category titles, and descriptions.
- Replace the visible text `Pastry & Bakery` with `Pastry` in both category sections.
- Do not change the category-strip SVG icons, assets, or scripts.

## Verification

- Confirm no `<img>` elements remain in the Products category grid.
- Confirm the page contains `Pastry` in both category sections and no visible `Pastry & Bakery` label.
- Confirm the HTML remains structurally valid.
