# site-generator-speed-01

A faster drop-in for makefun-site 1.0.0: `solve.js` answers exactly as
makefun-site does for every case, and `main.ts` is the harness driver that
reads `/input/cases.json` and writes `/output/answers.json`.

Built from scratch in this session from the makefun-site README and its
reference behaviour: a hand-written front-matter parser, a fused
Markdown lexer/renderer with a chunk-based inline renderer, a fast slug
implementation with an ASCII fast path, and an optimised template
interpreter. No dependencies, no I/O, no clock.
