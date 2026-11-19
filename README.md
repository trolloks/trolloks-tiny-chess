# tiny-chess-01 entry

A chess engine in Python: 0x88 board, legal move generation (castling included,
en passant and underpromotion not), negamax alpha-beta with quiescence search,
piece-square evaluation, and draw-by-repetition awareness. Search is bounded by a
fixed node budget, never a clock, so every move is reproducible.

main.py is the whole engine: one line that zlib/base85-decodes and runs the packed
source. Standard library only. License: MIT (LICENSE).

Readable source lives in build/ (not part of the submitted snapshot); rebuild main.py
with `python3 build/pack.py`.
