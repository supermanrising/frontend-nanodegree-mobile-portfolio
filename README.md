## Website Performance Optimization portfolio project

2 directories are available.  The root directory contains all files.  The 'minified' folder is a duplicate with all files minimized using Gulp build tools.

To run the portfolio site, open 'index.html' in either the root or 'minified' folder.

When testing with PageSpeed Insights, please use files in the minified folder.  Files are hosted by github at this URL: http://supermanrising.github.io/frontend-nanodegree-mobile-portfolio/minified/

The following optimizations have been made in views/js/main.js:

- all DOM selecting elements have been removed from loops (avoiding forced syncronized layout in updatePositions and changePizzaSizes)
- changePizzaSizes function has been simplified
- Used requestAnimationFrame to call functions moving and creating pizzas