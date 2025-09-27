# WorldSplat: Gaussian-Centric Feed-Forward 4D Scene Generation for Autonomous Driving

<p align="center">
  <img src="docs/assets/teaser.png" alt="WorldSplat Teaser" width="100%">
</p>

> [Project Page](https://wm-research.github.io/worldsplat) | [arXiv (coming soon)](https://arxiv.org/abs/xxxx.xxxxx)  

WorldSplat is a **feed-forward 4D scene generation framework** designed for autonomous driving.  
It introduces a **Gaussian-centric representation** that directly produces controllable 4D Gaussians from multi-modal latent diffusion features, enabling **spatially and temporally consistent novel-view driving videos** under user-defined trajectory shifts.

---

## 🚀 Highlights

- **4D-aware Latent Diffusion**  
  Integrates RGB, depth, and motion information to create a unified multi-modal latent space.

- **Feed-forward Gaussian Decoder**  
  Predicts pixel-aligned 3D Gaussians and performs **dynamic–static decomposition** to construct controllable 4D scenes.

- **High-fidelity Novel View Rendering**  
  Generates multi-track driving videos with **improved temporal consistency** via an enhanced diffusion refinement stage.

- **Downstream Benefits**  
  The generated data improves perception tasks such as **3D object detection** and **BEV map segmentation**.

---

## 📦 Code Availability

🚧 **Code is coming soon!**  
We are cleaning up the implementation and will release the full training and inference pipeline shortly.  
Stay tuned and watch this repository for updates.

---

## 📑 Citation

If you find this work useful, please cite:

```bibtex
@misc{zhu2026worldsplat,
  title        = {WorldSplat: Gaussian-Centric Feed-Forward 4D Scene Generation for Autonomous Driving},
  author       = {Ziyue Zhu and Zhanqian Wu and Zhenxin Zhu and Lijun Zhou and Haiyang Sun and Bing Wang and Kun Ma and Guang Chen and Hangjun Ye and Jin Xie and Jian Yang},
  year         = {2026},
  note         = {Under review at the International Conference on Learning Representations (ICLR) 2026},
  url          = {https://github.com/wm-research/worldsplat}
}

