# gearathon-pack

Resource packs for the Gearathon DiamondFire plot. The plot's `event.Join` sends one of these by its raw link; each
file is named by the first 10 characters of its SHA-1, so every version has its own URL and clients never keep a
stale cached copy.

Built from [3fod/Gearathon](https://github.com/3fod/Gearathon) (private) with `rp/build.py`. Don't edit files here by
hand: rebuild, add the new zip, and point the plot at it (see `updates/wilderness.md` section 3.2 in that repo).

| File | SHA-1 | Notes |
|---|---|---|
| `gearathon-rp-e2ef22208f.zip` | `e2ef22208f63a90bacbc7ece02ea5dd9a12dbed1` | 2026-11-08: mesa sand streaks on the real ground only, much scarcer; adds `textures/effect/height.png` |
| `gearathon-rp-98a19d97e4.zip` | `98a19d97e4a3672278d740aa8a4812c2933de4d1` | 2026-11-08: mesa sand: always-on sparse lines; heat shimmer toned down |
| `gearathon-rp-eed04aeebe.zip` | `eed04aeebe2473e820ed0ba427ecc3c48b6cb0e0` | 2026-11-08: mesa sand: fainter, thinner, pointed wisps of varied length, a bit slower; blight: perlin ground fog |
| `gearathon-rp-0f7546b8fc.zip` | `0f7546b8fc00031039d776735745fb7b166f01ec` | 2026-11-08: blight ground fog: faint, settles in hollows, soft top, near only (fixes the wash-out in eed04aeebe) |
| `gearathon-rp-9edf837eff.zip` | `9edf837eff6ff0eb4832f6afd0795a0a8889b762` | 2026-11-08: blight ground fog: recalibrated to be visible (~30% flat, ~50% hollows, lighter tint) |
| `gearathon-rp-09886eb6ad.zip` | `09886eb6ad06dfea1dae9aafcd3a299f3415d9de` | 2026-11-08: blight ground fog: haze-coloured murk (no spotlight look), soft edges at steps, thinner layer |
| `gearathon-rp-4fa7788389.zip` | `4fa77883890fff134de04c2edcb957f3a2cb25a7` | 2026-11-08: TEST: blight ground fog pixels 1/4 block (revert to 09886eb6ad if it looks bad) |
| `gearathon-rp-78fb6c585b.zip` | `78fb6c585bcd26745e84e0f90325863d7e162c8a` | 2026-11-08: tumbleweed redo (1.5-block twig ball + invisible carrier), probe check tolerances, chunkier blight fog pixels kept |
