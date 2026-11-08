# Float

Code for Maelstrom Robotics' MATE Floats! vertical profiling float (2027 season, RANGER).

The float is a second robot with no tether. It dives on its own, holds depth, logs sensor data on the way up, and sends that data to a receiver at the pool deck. Full rules are in MATE's Float Preview Mission: https://materovcompetition.org/2027 (summary in [docs/rules.md](docs/rules.md)).

## What's in here

| Folder | What goes there |
|---|---|
| `firmware/` | Code that runs on the float's microcontroller: sensors, depth control, logging, sending packets |
| `receiver/` | Code that runs on a laptop at the pool deck: receive packets, show them, graph the data |
| `docs/` | Rules summary, design notes, decisions |

Nothing is decided yet: board, sensors, radio and language are still being discussed in #software. Add your notes to `docs/` instead of picking silently.

## How we work

See [CONTRIBUTING.md](CONTRIBUTING.md).
