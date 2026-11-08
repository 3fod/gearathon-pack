# gearathon-pack

Resource packs for the Gearathon DiamondFire plot. The plot's `event.Join` sends one of these by its raw link; each
file is named by the first 10 characters of its SHA-1, so every version has its own URL and clients never keep a
stale cached copy.

Built from [3fod/Gearathon](https://github.com/3fod/Gearathon) (private) with `rp/build.py`. Don't edit files here by
hand: rebuild, add the new zip, and point the plot at it (see `updates/wilderness.md` section 3.2 in that repo).

| File | SHA-1 | Notes |
|---|---|---|
| `gearathon-rp-e2ef22208f.zip` | `e2ef22208f63a90bacbc7ece02ea5dd9a12dbed1` | 2026-11-08: mesa sand streaks on the real ground only, much scarcer; adds `textures/effect/height.png` |
