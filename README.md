# Cullet Size Identifier & Area Analyzer

A single-file, offline-ready web application for measuring glass cullet area, dimensions, and cumulative sieve size distribution from top-down photos calibrated with a reference ruler.

## How to Run

Double-click **`index.html`** to open it in any modern web browser (Chrome, Edge, Firefox). No installation, Python, or internet connection is required.

## Quick Workflow

1. **Upload Photo**: Drag and drop your cullet photo onto the upload area (or click **Load Sample Cullet** to test with built-in sample data).
2. **Calibrate Ruler**: Click **Click 2 Ruler Marks**, click two known marks on your ruler (e.g., `0` and `10 cm`), and enter the real distance (`mm`, `cm`, or `inch`).
3. **Exclude Ruler**: Click **Drag Box on Ruler** and draw a rectangle over the ruler so it is excluded from cullet measurements.
4. **Analyze**: Click **Calculate Cullet Area & Size** to view total area ($cm^2$ / $mm^2$), particle count, D10/D50/D90 sieve metrics, size distribution charts, and per-particle measurements.
5. **Export**: Download results as **CSV**, **JSON**, or an **Annotated PNG**.
