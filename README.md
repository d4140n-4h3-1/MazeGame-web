# Ruptura Systematis, in the browser

The web version of [Ruptura Systematis](https://github.com/d4140n-4h3-1/MazeGame), a first-person maze game in
Rust on the Fyrox engine, compiled to WebAssembly and drawn with WebGL 2.

**Play it at https://d4140n-4h3-1.github.io/MazeGame-web/**

This repository holds only the built site. It is made with `web/build.sh` in the game's repository:
the page, the game in `pkg/`, and the models, sounds and dialogue it loads in `data/`.

Needs a desktop browser with WebGL 2. Ray-traced shadows need hardware ray tracing, which browsers
do not offer, so the web version uses shadow maps.
