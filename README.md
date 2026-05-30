# Relationshapez: Newton Fractal

This project is a single-file HTML explorer for the Newton fractal associated with Newton's method on
\( z^N - 1 = 0 \), where \(N\) is the chosen polynomial degree.

The interface is designed to be simple, mobile-friendly, and visually consistent with the other Relationshapez fractal tools.

## Files

- `index.html` — the main interactive browser tool
- `README.md` — repository overview and usage guide
- `LICENSE` — MIT license text

## Live URL

The tool is available at:

`https://relationshapez.github.io/newton_fractal/`

## What the tool does

The explorer applies Newton's method to complex starting points and colors each pixel according to one of two modes:

- **Root** — colors by which root the iteration converges to
- **Rate** — colors by how quickly the iteration converges

The default mode is **Root**.

## Controls

- **Center point (real)** and **Center point (imaginary)** set the center of the viewing window.
- **Pixel resolution** sets the width and height of the visible square region in the complex plane.
- **Number of pixels** sets the canvas resolution.
- **Polynomial degree** sets the value of \(N\) in \(z^N - 1 = 0\).
- **Max iterations** sets the Newton iteration cap used during rendering.
- **Create Image** redraws the fractal.
- **Reset** restores the default view.
- **Pan / Zoom** toggles the interaction mode.
- **Root / Rate** toggles the coloring mode.

## How to use

1. Open `index.html` in a browser.
2. Adjust the center point, viewing size, pixel count, degree, or iteration count.
3. Press **Create Image**.
4. Use **Zoom** mode to drag a box around a region.
5. Use **Pan** mode to drag the image to a new location.
6. Use the **Root / Rate** toggle to switch between the two coloring styles.
7. Press **Reset** to return to the default view.

## Notes

- The familiar Newton fractal structure comes from solving \(z^N - 1 = 0\), which has multiple distinct roots.
- Using \(z^N = 0\) alone would produce only a single root at 0 and would not create the usual multi-basin Newton fractal picture.
- Larger pixel counts and higher iteration counts give more detail but may take longer to render.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
