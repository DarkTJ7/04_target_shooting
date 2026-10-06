# Target Shooting Lab

A compact Pygame target-shooting game featuring circular hit detection,
bouncing moving targets, combo scoring, and timed rounds.

## Setup

Requires Python 3.10+.

```bash
pip install -r target-shooting/requirements.txt
cd target-shooting
python main.py
```

## How to play

- Left-click to shoot. Hits are counted only inside a target's visible circle.
- Targets move at different speeds and bounce within the play area.
- Hits score 10 points times the current streak. A miss resets the combo.
- The round lasts 30 seconds. Shooting stops at zero and the final score appears.
- Press **R** on the results screen to start a fresh round.

## Project layout

```text
target-shooting/
├── main.py
├── requirements.txt
└── game/
    ├── game_engine.py
    ├── hit_detection.py
    ├── renderer.py
    └── target.py
```
