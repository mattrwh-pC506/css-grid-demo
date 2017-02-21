#Dense Responsive Grid Example
- uses `repeat`, `minmax`, `auto-fill` and `fr` units to flexibly arrange different sized elements on a grid
- `repeat` is used to define repetitive columns/rows. e.g. `grid-template-columns: repeat(3, 100px)`
- `minmax` is used to define a minimum and maximum size for a track, e.g. `grid-template-rows: 100px minmax(100px, 500px)`
- `auto-fill` when used as the first arg of `repeat`, this will automatically create tracks based on whether available elements will fit in a new track if it is created on the grid.
- `fr` units translate to `fraction or fractional unit`. this can be used to space tracks proportionally to each other. e.g. `grid-template-columns: 1fr 5fr 1fr`
