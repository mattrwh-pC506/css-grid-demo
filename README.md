# CSS Grid Layout (a.k.a Grid)

## Introduction
- Unlike Flexbox, which is one-dimensional, Grid is two-dimensional. It gives us the ability to setup a grid and place elements on it with precision.
- Similar to flexbox, the source order of the grid items doesn’t matter. Placement is declared in CSS making it easy to rearrange based on viewport size.
- It allows us to decouple layout definition from markup (e.g., bootstrap grid's `.row > .col-md-1` etc.)
- Grid does not completely replace flexbox, though it can be used as a lightweight replacement for simple use cases. Overall, though, flexbox and grid can and should be used together. Grid is best used to define major layouts and Flexbox is best for aligning UI elements.
 - "working from the content out (flexbox) vs. working from the grid definition in". Grid defines a structure which controls how elements are placed whereas with flex, content display is controlled on a track by track basis.. [for more info](https://rachelandrew.co.uk/archives/2016/03/30/should-i-use-grid-or-flexbox/)

## History
- Specs were first published as a draft in April 2011, with the majority of the publishers being from Microsoft.
- IE 10 was first browser to implement the spec (-ms prefix), and today both IE 11 and Edge have -ms prefixed implementations.

## Terminology
- https://css-tricks.com/snippets/css/complete-guide-grid/#grid-terminology
- **Grid container:** `display: grid`
- **Grid item:** direct children of grid container
- **Grid line:** dividing lines of grid
- **Grid track:** space between two adjacent lines
- **Grid cell:** space between two adjacent vertical and horizontal lines (single unit)
- **Grid Area:** space surrounded by four grid lines, can span multiple tracks


## Resources
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Grid By Example](http://gridbyexample.com/examples/)
- [Flexible Sized Grids](https://rachelandrew.co.uk/archives/2016/04/12/flexible-sized-grids-with-auto-fill-and-minmax/)
- [Rachel Andrew Blog](https://rachelandrew.co.uk/archives/)
- [alligator.io](https://alligator.io/css) - has some ok grid examples
- [Browser Support](http://caniuse.com/#feat=css-grid)
