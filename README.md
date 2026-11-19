# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/trolloks/trolloks-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/trolloks/trolloks-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in Python: 0x88 board, legal move generation (castling included,
en passant and underpromotion not), negamax alpha-beta with quiescence search,
piece-square evaluation, and draw-by-repetition awareness. Search is bounded by a
fixed node budget, never a clock, so every move is reproducible.

main.py is the whole engine: one line that LZMA-decompresses and runs the packed
source. Standard library only. License: MIT (LICENSE).

Readable source lives in build/ (not part of the submitted snapshot); rebuild main.py
with the official `makefun compress build/engine.py --out main.py` command.
