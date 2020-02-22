## Asteroids (C based game) - live [here](https://marciobbj.github.io/web-assembly-playground/platform/web/index.html)

#### To compile ASTEROIDS code type inside root directory:
* `emcc -o index.html platform/web/asteroids/asteroids/*.c -Wall -g -lm -s USE_SDL=2`

#### To play it in localhost (port 8000) type:
* `emrun --no_browser --port 8000 platform/web/index.html -s FORCE_FILESYSTEM=1`
___
