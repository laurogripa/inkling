# Pelican on a Bike

One animated SVG. One static site. No build, no assets.

**Live:** https://laurogripa.github.io/inkling-pelican-bike/

## What it is

A hand-drawn pelican on a red bicycle, animated by a tiny inline script: spokes spin, the road scrolls, the rider bobs, legs pedal. Page layout: art left, specs right.

## The run

Session `01a209c7-2ad3` — «BIKE: Create pelican-riding-bike HTML».

| | |
|---|---|
| Model | `local/inkling` — Inkling 2 Mini |
| Config | [mw00/project-maya](https://github.com/mw00/project-maya/releases/tag/v1.1.75) v1.1.75 |
| Turns | 59 |
| Model time | 748.6 s (12.5 min) |
| Output tokens | 79,984 |
| Rate (model time only) | 106.8 tok/s |

## Specs

Box it ran on: MiniPC. Usage measured live (`nvidia-smi`, `free`).

| | |
|---|---|
| GPU | NVIDIA GeForce RTX 3090 · 24,576 MiB · driver 580.178.04 |
| CPU | Intel Core Ultra 9 185H · 16 cores · 5.1 GHz max |
| Motherboard | AZW GTi14 |
| OS | Ubuntu 24.04.4 LTS (noble) |
| VRAM | 23.6 GiB used of 24 GiB |
| RAM | 14 GiB used of 93 GiB |

## Files

| | |
|---|---|
| `index.html` | the whole site — SVG, inline loop, specs panel |
| `README.md` | this file |

## Next

Edit `index.html`, push — Pages redeploys on push.
