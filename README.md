# inkling

Experiments in one shell. Each lives in its own folder, linked from the root landing page.

**Live:** https://laurogripa.github.io/inkling/

| | |
|---|---|
| [pelican-bike](pelican-bike/) | Animated SVG pelican on a bike |
| [pagoda](pagoda/) | Voxel art pagoda in a garden |

## pelican-bike

Session `01a209c7-2ad3` — «BIKE: Create pelican-riding-bike HTML».

| | |
|---|---|
| Model | Inkling 2 Mini · UD-Q4_K_XL |
| Config | [mw00/project-maya](https://github.com/mw00/project-maya/releases/tag/v1.1.75) v1.1.75 |
| Turns | 59 |
| Model time | 748.6 s (12.5 min) |
| Output tokens | 79,984 |
| Rate (model time only) | 106.8 tok/s |

Specs — MiniPC, usage measured live (`nvidia-smi`, `free`):

| | |
|---|---|
| GPU | NVIDIA GeForce RTX 3090 · 24,576 MiB · driver 580.178.04 |
| VRAM | 23.6 GiB used of 24 GiB |
| CPU | Intel Core Ultra 9 185H · 16 cores · 5.1 GHz max |
| Motherboard | AZW GTi14 |
| OS | Ubuntu 24.04.4 LTS (noble) |
| RAM | 14 GiB used of 93 GiB |

## pagoda

Session `01a20a0a-6977-725c-8cd1-e8a771976986` — «Pagoda: voxel art scene».

| | |
|---|---|
| Model | Inkling 2 Mini 262K · local/inkling |
| Server | maya-ik2 · looped MoE + DSpark drafter |
| Effort | high |
| Turns | 80 |
| Model time | 1395.4 s (23.2 min) |
| Output tokens | 120,163 |
| Rate (model time only) | 86.1 tok/s |

## Next

Edit a project folder, push — Pages redeploys on push.
