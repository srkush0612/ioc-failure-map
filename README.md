# IoC failure map

Interactive multi-agent failure map comparing decisions with and without IoC across five use cases and four failure classes.

[Open the live prototype](https://srkush0612.github.io/ioc-failure-map/#/matrix)

## Deployment

GitHub Pages serves `index.html` from the root of the `main` branch. The page is self-contained, with its fonts, styles, and scripts included.

To update it, rebuild the matrix in the source project, replace `index.html` with the generated `standalone-matrix.html`, then push to `main`.

## Local preview

Open `index.html` in a browser, or serve this directory with any static web server. Individual detail views use hash routes, such as `#/matrix/supply/sf3`.
