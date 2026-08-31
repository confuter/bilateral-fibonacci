# bilateral-fibonacci

Interactive browser tool for exploring the bilateral Fibonacci sequence and its derived cumulative, folded, braided, pair‑fold, and pair‑braid forms.

## Open

Download or clone the repository, then open:

```text
interactive_bilateral_fibonacci.html
```

No server or build step is required. The page uses the Plotly CDN, so an internet connection is needed.

## Features

- Change the number of terms `n` on each side of zero
- Show or hide individual sequences
- Show or hide the left, right, upper, and lower halves of the graph
- Show mirrored values for every sequence
- Rotate the graph through 0°, 90°, 180°, and 270°
- Flip the x-axis or y-axis
- Toggle linear and symlog views
- Toggle dark and light backgrounds
- Change each sequence colour
- Change each sequence between solid, dashed, and dotted lines
- Export and import configuration as JSON
- Download the current view as PNG
- Zoom, pan, and reset the view

## Sequences

The tool includes the following named sequences:

- `+0±`
- `−0∓`
- `Σ(+0±)`
- `Σ(−0∓)`
- `Fib`
- `ΣFib`
- `folded₀`
- `Σfold`
- `braided₀`
- `Σbraid`
- `pair-fold`
- `pair-braid`

`Σ` denotes the cumulative sum of a sequence.

## Notes

- Settings are saved automatically in the browser using `localStorage`.
- Use **Export JSON** to save a copy of the current configuration.
- Use **Import JSON** to load a saved configuration.
- Double-click the graph or use the home icon in the Plotly toolbar to reset zoom.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)


This is concise but complete for a single-file repo.
