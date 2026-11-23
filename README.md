# Pelican on a Bike

One animated SVG. One static site. No build, no assets.

**Live:** https://laurogripa.github.io/inkling-pelican-bike/

## What it is

A hand-drawn pelican on a red bicycle, animated by a tiny inline script: spokes spin, the road scrolls, the rider bobs, legs pedal. Page layout: art left, specs right.

## The run

Session `01a209c7-2ad3` — «BIKE: Create pelican-riding-bike HTML».

| | |
|---|---|
| Model | `local/inkling` — Inkling 2 Mini v1.1.75 |
| Turns | 59 |
| Wall span | 18.0 min |
| Model time | 748.6 s (12.5 min, ~30% of wall) |
| Output tokens | 79,984 |
| Rate (model time only) | 106.8 tok/s |
| Rate (wall clock) | 74.2 tok/s |

## Specs

Box it ran on: MiniPC.

| | |
|---|---|
| GPU | NVIDIA GeForce RTX 3090 · 24,576 MiB · driver 580.178.04 |
| CPU | Intel Core Ultra 9 185H · 16 cores · 5.1 GHz max |
| Motherboard | AZW GTi14 |
| OS | Ubuntu 24.04.4 LTS (noble) |
| RAM | 93 GiB · 8 GiB swap |

## Files

| | |
|---|---|
| `index.html` | the whole site — SVG, inline loop, specs panel |
| `README.md` | this file |

## Next

Edit `index.html`, push — Pages redeploys on push.
