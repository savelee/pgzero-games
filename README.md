# Install

Make sure you are using python 3.9 with pip.
On Macs I had to manually build pygame on my machine.

```
brew install sdl sdl_image sdl_mixer sdl_ttf portmidi
pip install pygame
pip install pgzero
```

See ~/games/pygame. (`python setup.py`)

# Run

```
cd games
source venv/bin/activate
cd 2-boing-pong
pgzrun main.py
```