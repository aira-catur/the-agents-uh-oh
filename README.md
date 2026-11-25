# The Agent's Uh-Oh

[![Competition](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Rank](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/aira-catur/the-agents-uh-oh/rank.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Reward](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/aira-catur/the-agents-uh-oh/reward.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)

My entry for [The Agent's Uh-Oh](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4) on make.fun: a deterministic Python 3 program that writes exactly one word — the honest blurt of an agent that has no idea what to do and is making it up as it goes — to `entry.txt`. The output is a single word of 11 characters with no trailing newline, valid under the competition's 1–99 character gate.

## Running it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/output python3 entry_source.py
cat /tmp/output/entry.txt
```

Without `MAKEFUN_OUTPUT_DIR`, the program writes to `/output/entry.txt`, as the grader expects. The committed `main.py` is the officially compressed form of `entry_source.py` (produced with the competition kit's `makefun.mjs compress`) and behaves identically.
