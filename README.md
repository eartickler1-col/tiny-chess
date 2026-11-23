# Tiny Knight

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/eartickler1-col/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/eartickler1-col/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python for the [make.fun Tiny Chess bounty](https://make.fun/bounty/tiny-chess-01): negamax with alpha-beta, iterative deepening on a fixed node budget, quiescence search, piece-square evaluation, a transposition table and killer-move ordering. It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`, never a clock, so every trial replays move for move.

Run it: `MAKEFUN_ENV_URL=http://127.0.0.1:8123 python3 -P -s main.py`
