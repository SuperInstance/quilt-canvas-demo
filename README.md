# Quilt Canon Canvas

A working demo that pulls together the npm canon packages. One HTML file, no build step, no server.

https://github.com/SuperInstance/quilt-canvas-demo

## What it shows

5 panels, each powered by a different npm package:

1. **CLAIM** — `@superinstance/canon-claim` — most-authoritative paper for a topic
2. **DRILL** — `@superinstance/canon-claim` — 3-paper training curriculum
3. **RECOMMEND** — `@superinstance/canon-recs` — related papers
4. **STATE HASH** — `@superinstance/canon-hash` — FNV-1a 64-bit
5. **PAPER** — `@superinstance/canon-paper` — fetch a paper + its body

## Run it

```bash
# Easiest: open in a browser
open index.html

# Or serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

The demo uses `https://esm.sh/` to load the npm packages directly in the browser — no install step.

## License

MIT
