# MacBook Neo On-Screen Ruler

A lightweight, zero-dependency on-screen ruler calibrated for the **13.0-inch MacBook Neo** (`2408 × 1506` native resolution at `219 PPI`).

## Features
- **Auto-calibrates across macOS Display Scaling modes** using `window.screen.width` and the MacBook Neo's physical width (`2408 / 219 = 10.995 in` / `279.28 mm`).
- **Metric (mm / cm)** and **Imperial (1/16 in)** scales rendered with crisp SVG vector ticks.
- **Interactive measurement marker** (click or drag anywhere on the ruler).
- **Credit card verification overlay** (`85.6 mm`) and scale fine-tune slider.
- **Iframe embed mode** (`?embed=1` or auto-detected when inside an `<iframe>`).

## Embed with an `<iframe>`

```html
<iframe
  src="https://<your-username>.github.io/macbook-neo-ruler/?embed=1"
  width="100%"
  height="225"
  style="border: 0;"
  title="MacBook Neo Ruler"
></iframe>
```
