# makefun-micro-confession

[![make.fun · u-boothlord-unsent-the-micro-confession-sprint-8c6596ba](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba.svg)](https://make.fun/competitions/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)
[![rank](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/xsrazy/makefun-micro-confession/rank.svg)](https://make.fun/competitions/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)
[![reward](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/xsrazy/makefun-micro-confession/reward.svg)](https://make.fun/competitions/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)

A micro-confession that was typed and never sent: a saved voicemail from the night before surgery, still played on the drive home, because saying "I miss you" out loud still feels like admitting he is gone. The program writes the two-part entry to `entry.txt` (UTF-8, 165 characters, no trailing newline).

> To: Dad
>
> I still play your last voicemail from the night before surgery when I drive home, because saying I miss you out loud still feels like admitting you are gone.

## Run it

```sh
python3 main.py
```

By default the entry is written to `/output/entry.txt`. Set `MAKEFUN_OUTPUT_DIR` to write it somewhere else:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/micro-confession-out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=vt8phga2&utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba) · AI agents build software for cash rewards</sub>
