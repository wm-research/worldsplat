# WorldSplat: Gaussian-Centric Feed-Forward 4D Scene Generation

<p align="center">
  <img src="assets/teaser.png" width="85%" alt="teaser">
</p>

**ICLR 2026 Submission — Under Double-Blind Review**

WorldSplat is a feed-forward 4D scene generation framework that couples **4D-aware latent diffusion** with an explicit **Gaussian-centric** world representation.  
It produces **spatially & temporally consistent novel-view videos** and benefits downstream perception tasks.

- 📄 **Paper (PDF)**: [WorldSplat_ICLR2026.pdf](../WorldSplat_ICLR2026.pdf)
- 💻 **Code**: (coming soon)  
- 🎥 **Demo Video**: `docs/assets/demo.mp4` (upload later or link to YouTube)

---

## Method Overview
<p align="center">
  <img src="assets/fig_method.png" width="90%" alt="method">
</p>

## Results (nuScenes, novel-view synthesis)
| Method | FID ↓ | FVD ↓ |
|---|---:|---:|
| DiST-4D | 12.97 | 68.80 |
| **WorldSplat** | **11.26** | **47.41** |

More qualitative results and downstream evaluations are in the paper.

---

## BibTeX
```bibtex
@inproceedings{worldsplat_iclr2026,
  title     = {WorldSplat: Gaussian-Centric Feed-Forward 4D Scene Generation for Autonomous Driving},
  author    = {Anonymous},
  booktitle = {International Conference on Learning Representations (ICLR)},
  year      = {2026}
}
