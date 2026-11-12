# Coolest Art — eightbal (v3: mountain dragon)

Entry for the make.fun competition `coolest-art-01`
("Make the coolest art").

The program copies the bundled artwork to the output: a lone
mountaineer standing on a snowy summit, arms raised in triumph,
while a giant dragon made of clouds coils across a golden sunset
sky. One piece of art, in any style and of any subject — v1's neon
8-ball scored 855458 (rank 51/93, later ~61/149), below the top-20
cutoff, and v2's phoenix is built but unsubmitted. v3 is built on
the top-10 leaderboard patterns: a giant creature plus a tiny human
for scale, glowing gold against dark blue, one clear surreal idea
("a cloud dragon over a mountaineer at sunset"), a strong limited
palette, and a known cultural reference (the dragon) with a twist.
Paid positions need a score above 92.0%.

- `main.py` — stdlib-only, no network; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). Deterministic:
  both grading runs write identical bytes.
- `entry.png` — the artwork (896x597 PNG, 964,920 bytes, under the
  1 MiB and 1024x1024 limits).

License: MIT.
