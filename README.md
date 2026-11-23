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
| `gearathon-rp-05b78beb96.zip` | `05b78beb9619ed8e767448f67f706a7c3c8e68c7` | 2026-11-08: foliage in our own style: leaf fringes and tufts (purple pale oak), dead bush bones, sand pebbles |
| `gearathon-rp-98d57ac380.zip` | `98d57ac3808554000f6717a4369a7d8bc3fe3ae4` | 2026-11-08: pixel clouds, Bare Skies style sky, our sun and moon, low border fog |
| `gearathon-rp-28a0da767f.zip` | `28a0da767f5514f675215fd4af322962449094cc` | 2026-11-08: higher clouds, darker nights, moon fix |
| `gearathon-rp-5bff49fb8c.zip` | `5bff49fb8cf53071703379d71a30c1755a2f2ef4` | 2026-11-08: foliage batch 2, softer clouds |
| `gearathon-rp-b4e832cd9e.zip` | `b4e832cd9e33a01ad22e713f6dc65b6af108fa49` | 2026-11-08: plains bugs: ladybugs, beetles, moths, gnats |
| `gearathon-rp-5dc8696359.zip` | `5dc869635957287d4d57ae549239fae9c77b8c3c` | 2026-11-08: Goose's Foliage (MIT), steady fog tint, continuous night fade |
| `gearathon-rp-43ea73895f.zip` | `43ea73895f338dec4452667f50c05ce63a61a73e` | 2026-11-08: without Goose's lily pads, cacti and dead bush plants |
| `gearathon-rp-60d026151f.zip` | `60d026151fe218ad44bd348f3fd871a4c0899ef9` | 2026-11-08: chunkier 1.5-block tumbleweed |
| `gearathon-rp-abed12dfdd.zip` | `abed12dfdd3cc074bccb52c6db198c41792e22c7` | 2026-11-15: caves rework: new mesa/frost plant art, cave-aware post effect |
| `gearathon-rp-60bbdcb0b4.zip` | `60bbdcb0b4ecff1aec32f58cdeac92e909a8bc10` | 2026-11-18: terrain v11, v11 caves (forest grotto, fossil canyons, overgrown mines, blight blend), cave-aware effects |
| `gearathon-rp-e3d57d2e96.zip` | `e3d57d2e9624aab9ebd2981ca286f3cfafd817fa` | 2026-11-23: terrain v19, HUD round 4: held-name fade fix, backpack slot under the hotbar, stripped inventory screen |
| `gearathon-rp-f1baf78da9.zip` | `f1baf78da906fb00191b16e0f048ef9d38e4d182` | 2026-11-23: terrain v19, Round 5: inventory tray, icons, model moved; loadout; rarity; pickup flight |
| `gearathon-rp-d87bbfd597.zip` | `d87bbfd5975bea865d57f28b49ff8bab0ad97f35` | 2026-11-23: terrain v19, Round 6: no dialogs, custom clicks, spinning picture, model opens loadout |
| `gearathon-rp-8d79c45d57.zip` | `8d79c45d57119524b857afa22a980bbfadd7636f` | 2026-11-23: terrain v19, Round 7: hints fit, slower spin, rarity tooltips, details colours |
| `gearathon-rp-2e909a6026.zip` | `2e909a6026906c07033918b42bcca631feef25d4` | 2026-11-23: terrain v19, Fix: text near the bottom stretched into long lines |
| `gearathon-rp-1ef674f289.zip` | `1ef674f289ca553610eef4960cdcdef8bf553ab4` | 2026-11-23: terrain v19, Fix: chat error box stretched into a line |
