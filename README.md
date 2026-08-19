<h1 align="center">Awesome 3D Token Compression <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a></h1>

<p align="center">
  A curated list of <b>3D token compression</b> methods — <b>token pruning · reduction · merging</b> — for <b>3D multimodal LLMs</b> ⚡🧊
</p>

<p align="center">
  <sub><i>Keywords: 3D token compression · 3D token pruning · 3D token reduction · 3D token merging · efficient 3D LLM · 3D VLM · 3D scene understanding</i></sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PRs-welcome-2f6fe0.svg?style=flat-square">
  <img src="https://img.shields.io/github/last-commit/higokri/Awesome-3D-Token-Pruning?style=flat-square&color=2f6fe0">
  <img src="https://img.shields.io/github/stars/higokri/Awesome-3D-Token-Pruning?style=social">
</p>

---

3D multimodal LLMs project multi-view features into world space, producing **thousands of tokens per scene** —
and the LLM backbone spends **>90%** of its compute on them. This list collects methods that **prune, merge, or
compress** those 3D visual tokens to make inference efficient without sacrificing spatial understanding.

**Legend** — ✅ code available · 🔒 code not released

## 📚 Papers

| Method | Title | Venue | Applied to | Code |
|:---|:---|:---:|:---:|:---:|
| **3DZip** | [Spatial-Aware Feature Diversity-Guided Token Compression for 3D Question Answering](https://paper.pnu-cvsp.com/3DZip/) | ECCV 2026 | LLaVA-3D | [✅](https://github.com/cvsp-lab/3DZip) |
| **CoverPrune** | [Coverage-Driven Token Pruning for 3D VLMs via Optimal Transport](https://arxiv.org/abs/2608.13226) | ECCV 2026 (Oral) | GS-Reasoner · VLM-3R | [✅](https://github.com/Brucess/CoverPrune) |
| **Merge3D** | [Efficient 3D Multimodal LLMs via Joint 2D-3D Token Merging](https://cvpr.thecvf.com/virtual/2026/poster/38939) | CVPR 2026 | Multi-view 3D MLLM | 🔒 |
| **Geo3DPruner** | [Geometry-Guided 3D Visual Token Pruning for Video-Language Models](https://arxiv.org/abs/2604.18260) | CVPR 2026 | Video-3D LLM (LLaVA-Video) | [✅](https://github.com/homothetic/Geo3DPruner) |
| **AdaToken-3D** | [Dynamic Spatial Gating for Efficient 3D Large Multimodal-Models Reasoning](https://arxiv.org/abs/2505.12782) | AAAI 2026 | LLaVA-3D | 🔒 |
| **Fast3D** | [Accelerating 3D Multi-modal Large Language Models for Efficient 3D Scene Understanding](https://arxiv.org/abs/2507.09334) | ACM MM 2025 | Chat-Scene | [✅](https://github.com/wencan25/Fast3D) |
| **DTC** | [Zero-shot 3D Question Answering via Voxel-based Dynamic Token Compression](https://cvpr.thecvf.com/virtual/2025/poster/33335) | CVPR 2025 | Multi-frame VLM | 🔒 |
| **HCC-3D** | [Hierarchical Compensatory Compression for 98% 3D Token Reduction in Vision-Language Models](https://arxiv.org/abs/2511.09883) | Preprint | GreenPLM (Phi-2/3) | 🔒 |

## 🤝 Contributing

Found a missing paper? PRs are welcome — please keep the table sorted by venue date (newest first) and follow the
existing format: `Method | Title (linked) | Venue | Applied to | Code`.

## 📄 License

[![CC0](https://licensebuttons.net/p/zero/1.0/80x15.png)](https://creativecommons.org/publicdomain/zero/1.0/) — to the extent possible under law, contributors have waived all copyright.
