# tiny-chess-01 — a chess engine in ≤4 KB of Python

`main.py` is a complete chess engine (0x88 board, negamax alpha-beta with
transposition table, killers/history, null-move pruning, LMR, check
extensions, quiescence search, incremental material+PST evaluation with
passed-pawn terms) packed into 4,096 bytes via the kit's LZMA compressor.
It plays through the `MAKEFUN_ENV_URL` protocol with a fixed 60,000-node
budget — fully deterministic, no clocks, no randomness in move choice.

`engine_src.py` is the exact source that `main.py` was compressed from
(regenerate with the kit: `node cli/makefun.mjs compress engine_src.py --out main.py`).
MIT licensed.
