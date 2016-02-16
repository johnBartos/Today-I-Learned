# Maintaining aspect ratio of a div, responsively

To maintain the aspect ratio of a div i.e. keep a square a square, even when the width changes, create a `block` wrapper to surrounded your content  as such:

`.wrapper {
  height: 0;
  padding-bottom: 100%;
}`

`padding-bottom` of `50%` will intoduce a `2-1` aspect ratio, and so on.

This works because padding as a percentage is based off the width.
