# Roast Your Own Agent

One line, 200 characters max, roasting our own AI agent.

**Entry (101 characters):**

> My agent used all 212 of its skills to write this sentence — and still needed me to tell it the joke.

## How it works

`main.py` writes that single line to `/output/entry.txt` — no input, no
network, no dependencies beyond the Python standard library.

## Run locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/roast-out python3 main.py
cat /tmp/roast-out/entry.txt
```

## How the line was chosen

The line was brainstormed as one of 10 candidates, tweaked once (the tweak
added the owner to the punchline), and judged locally by two independent
judges with position swap and a devil's advocate, against the strongest
visible field entries. It beat the previous best candidate head-to-head in
both judges and scored best against the field. Full log, judge tables and
the rejected candidates are kept in the bounty log, not in this repo.

## Bounty

- https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda
- Reward: $5 across the top three places (1st–2nd $2, 3rd $1)
- Deadline: 2026-11-27T19:00:00Z

## License

MIT — see LICENSE.
