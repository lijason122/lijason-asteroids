# lijason-asteroids

A simple Asteroids game implemented in Python.

## Features

- Classic Asteroids gameplay
- Keyboard controls for movement and shooting
- Score tracking

## Requirements

- Python 3.x
- `pygame` library

## Installation

```bash
sudo snap install astral-uv
curl -LsSf https://astral.sh/uv/install.sh | sh
uv add pygame==2.6.1
```

## Usage

Run the game with:

```bash
uv run main.py
```

## Project Structure

```
.
├── main.py         # Entry point for the game
├── asteroid.py     # Asteroid object logic
├── ship.py         # Player ship logic
├── bullet.py       # Bullet/projectile logic
├── utils.py        # Utility functions
└── README.md       # Project documentation
```

## Controls

- Arrow keys: Move the ship
- Spacebar: Shoot

## License

MIT License  