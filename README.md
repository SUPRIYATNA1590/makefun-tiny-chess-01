# tiny-chess-01

A compact chess engine in 4 KB of Python, built for the make.fun tiny-chess-01 bounty.

`main.py` is the entrypoint (packed with `makefun compress` from the readable
source `src.py`). It plays a full trial against the kit environment server:
alpha-beta search with a transposition table, null-move pruning, late move
reductions and quiescence, over a 0x88 board, to a fixed node budget of
100,000 nodes per move (deterministic, no wall clock).

License: MIT.
