# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/axitvideos/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/axitvideos/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 4,035 bytes of Python (standard library only): 0x88 board, negamax alpha-beta with transposition table, killers/history, null-move pruning, LMR, check extensions and quiescence search, incremental material + piece-square evaluation with passed-pawn terms. It plays through the MAKEFUN_ENV_URL protocol with a fixed 60,000-node budget — fully deterministic, no clocks, no randomness. Local practice gauntlet: Elo 1191 (finals line is 1154). `main.py` is packed from a readable source with the kit's compressor; that source travels with the entry's transcript bundle.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=57bn8c8j&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
