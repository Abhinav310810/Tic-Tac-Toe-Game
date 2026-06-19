# Neon Grid Tic Tac Toe Engine

An optimized, fully interactive 2D grid matrix game built on vanilla state management protocols. The system features modular win condition arrays that analyze player coordinates at runtime.

## 🕹️ Architecture & Game Logic
- **Flat Array Board Mapping:** The 3x3 game coordinates are mapped linearly to a 9-slot string array (`board`), keeping database operations highly efficient.
- **Matrix Multi-Dimensional Verification:** Uses a lookup loop evaluating 8 conditional spatial coordinates (Rows, Columns, Diagonals) to capture winning match alignments instantly.
- **Dynamic Turn Switching:** Toggles running session ownership between state tokens ("X" / "O") using a clean assignment cycle.
- **Visual State Transitions:** Uses targeted dynamic CSS classes to attach neon glow properties based on individual moves.

## 🛠️ Technology Stack
- Grid System: HTML5 Canvas-Alternative Block Elements
- Interface FX: CSS3 Flexbox Models & Text-Shadow Filters
- Game Core: Vanilla JavaScript (Array Iterators & Conditional Routers)
