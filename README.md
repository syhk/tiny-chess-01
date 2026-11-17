# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/syhk/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/syhk/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta with quiescence search, transposition table, MVV-LVA + killer move ordering, tapered material + piece-square evaluation, and a fixed 120k-node budget per move (no clock, no randomness — fully deterministic). Practice Elo ~1490, above the sunfish-4k house baseline (~1325). `main.py` is the self-contained compressed entrypoint (4,084 bytes); the readable source is kept locally and is not part of this submission.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8123 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kjeq30q1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
