# nuvio-assets

Cover images and GIFs for Nuvio app collections, organized by service/category.

## Structure

Each service/category has its own folder with consistent naming:

```
streaming/{service}/
  {service}-square.png      # Square logo (1:1)
  {service}-landscape.jpg   # Landscape cover (16:9) - if available
  {service}.gif             # Animated GIF - if available

genres/{genre}/
  {genre}-landscape.png     # Wide landscape image

franchises/{franchise}/
  {franchise}-landscape.png # Wide landscape image
  {franchise}.gif           # Animated GIF - if available

directors/{director}/
  {director}-landscape.png

decades/{decade}/
  {decade}-landscape.png

studios/{studio}/
  {studio}.gif

awards/{award}/
  {award}-poster.png

world-cinema/{region}/
  {region}-landscape.png
  {region}.gif

anime/{name}/
  {name}-landscape.png
  {name}.gif

popular/{name}/
  {name}-landscape.png
  {name}.gif
```

## Usage

Raw GitHub URL pattern:
```
https://raw.githubusercontent.com/rrevanth/nuvio-assets/main/streaming/netflix/netflix.gif
https://raw.githubusercontent.com/rrevanth/nuvio-assets/main/streaming/netflix/netflix-square.png
https://raw.githubusercontent.com/rrevanth/nuvio-assets/main/genres/action/action-landscape.png
```

## Sources

- Streaming logos (square): [fusion-starter-kit](https://github.com/itsrenoria/fusion-starter-kit) by orangebyte
- Genre/Decade/Director images: [fusion-starter-kit](https://github.com/itsrenoria/fusion-starter-kit) by dannyrutledge & mousa.a
- Streaming GIFs & franchise GIFs: [Nuvio Covers](https://nuvioapp.space/covers) community uploads
