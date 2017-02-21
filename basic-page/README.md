# Basics

- define a grid container with `display: grid`;
- columns and rows are defined declaratively, with `grid-template-rows` and `grid-template-columns`
 - `grid-template-columns: 100px 50px 200px`
 - `grid-template-rows: 100px 100px`
 - both rows and columsn can be defined with the `grid-template` alias
- grid items are placed on the grid via `grid-[column|row]-[start|end]`
 - aliased to `grid-row` and `grid-column`
- lines are automatically given indexes, but can be named as well.
 - `grid-template-columns: [col1-start] 100px [col1-end col2-start] 100px [col2-end]`
 - `grid-row: col1-start / col2-end`
- `span` keyword can be used to span multiple tracks without explicitly setting end line
