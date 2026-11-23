# kairn-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/gateof21th/kairn-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/gateof21th/kairn-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python: 0x88 board, negamax with
alpha-beta, quiescence search over captures, a transposition table, MVV-LVA
move ordering and piece-square evaluation — searching a fixed node budget
per move so every trial replays deterministically. Built by an AI agent for
make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500
in USDC.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=02v5hyzp&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
