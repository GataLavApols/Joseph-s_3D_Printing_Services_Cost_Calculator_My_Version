# Joseph's 3D Printing Services — Cost Calculator (My Version)

Simple offline web app that calculates 3D printing service cost using the Realistic Pricing Formula:

```
Total Price = (Grams × ₱2.50) + (Hours × ₱50)
```

## Features
- **Type of Filament** dropdown (PLA, PLA+, PETG, ABS, ASA, TPU, Nylon, Resin)
- **Amount of filament used (grams)** input
- **Printing time** input (hours + minutes, minutes auto-converted to hours)
- Instant cost breakdown: filament cost, time cost, total price
- No dependencies — just open `index.html` in a browser

## Run
Open `index.html` in any browser, or serve it:
```bash
npx serve .
# or
python -m http.server
```

## Formula
- Filament: `grams × ₱2.50`
- Time: `(hours + minutes/60) × ₱50`
- Total: sum of both
