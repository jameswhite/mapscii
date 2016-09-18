# termap - Terminal Map

Discover the world in your console - render vector tile maps from any source!

## TODOs
* [ ] mapping of view to tiles to show
* [ ] tile request system
  * [ ] from local mbtiles
  * [ ] from remote url
* [ ] label drawing
* [ ] lat/lng-center + zoom based viewport
* [ ] TileSource class (abstracting URL, mbtiles, single vector tile source)
* [ ] zoom while keeping center
* [ ] API
  * [ ] setCenter
  * [ ] setZoom
* [x] accurate mouse drag&drop
* [x] handle console resize

## Wishlist
* node-gyp binding to [libdrawille](https://github.com/Huulivoide/libdrawille) for speed refactor possibilities + filled polygons
