<div align="center">

# Awesome 3D Token Compression [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

**A curated list of token compression methods — pruning · merging · reduction — for 3D multimodal LLMs.** ⚡🧊

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2f6fe0.svg?style=flat-square)](#-contributing)
[![Last Commit](https://img.shields.io/github/last-commit/higokri/Awesome-3D-Token-Compression?style=flat-square&color=2f6fe0)](https://github.com/higokri/Awesome-3D-Token-Compression/commits)
[![Stars](https://img.shields.io/github/stars/higokri/Awesome-3D-Token-Compression?style=flat-square&color=ffd33d)](https://github.com/higokri/Awesome-3D-Token-Compression/stargazers)

<sub><i>Keywords: 3D token compression · 3D token pruning · 3D token reduction · 3D token merging · efficient 3D LLM · 3D VLM · 3D scene understanding</i></sub>

</div>

---

3D multimodal LLMs lift multi-view features into world space, producing **thousands of tokens per scene** — and the
LLM backbone spends **>90%** of its compute on them. This list tracks methods that **prune, merge, or compress** those
3D visual tokens to make inference efficient **without sacrificing spatial understanding**.

> **Legend** &nbsp;·&nbsp; Code: ✅ available · 🔒 not released

## Papers

### 2026

| Method | Title | Venue | Backbone | Code |
|:---|:---|:---:|:---:|:---:|
| **3DZip** | [Spatial-Aware Feature Diversity-Guided Token Compression for 3D QA](https://paper.pnu-cvsp.com/3DZip/) <br><sub>Changwoo Baek et al.</sub> | ECCV&nbsp;2026 | LLaVA-3D · Video-3D&nbsp;LLM · SR-3D | [✅](https://github.com/cvsp-lab/3DZip) |
| **CoverPrune** | [Coverage-Driven Token Pruning for 3D VLMs via Optimal Transport](https://arxiv.org/abs/2608.13226) <br><sub>Peng Ling et al.</sub> | ECCV&nbsp;2026 <br><sub>Spotlight</sub> | GS-Reasoner · VLM-3R | 🔒 |
| **Merge3D** | [Efficient 3D Multimodal LLMs via Joint 2D-3D Token Merging](https://cvpr.thecvf.com/virtual/2026/poster/38939) <br><sub>Tianbo Pan et al.</sub> | CVPR&nbsp;2026 | Multi-view 3D&nbsp;MLLM | 🔒 |
| **Geo3DPruner** | [Geometry-Guided 3D Visual Token Pruning for Video-Language Models](https://arxiv.org/abs/2604.18260) <br><sub>Han Li et al.</sub> | CVPR&nbsp;2026 | Video-3D&nbsp;LLM (LLaVA-Video) | 🔒 |
| **Efficient3D** | [A Unified Framework for Adaptive and Debiased Token Reduction in 3D MLLMs](https://github.com/sol924/Efficient3D) <br><sub>Yuhui Lin et al.</sub> | CVPR&nbsp;2026 <br><sub>Findings</sub> | Chat-Scene | [✅](https://github.com/sol924/Efficient3D) |
| **HCC-3D** | [Hierarchical Compensatory Compression for 98% 3D Token Reduction in VLMs](https://arxiv.org/abs/2511.09883) <br><sub>Liheng Zhang et al.</sub> | AAAI&nbsp;2026 | GreenPLM (Phi-2/3) | [✅](https://github.com/lihengzhang02/HCC-3D) |

### 2025

| Method | Title | Venue | Backbone | Code |
|:---|:---|:---:|:---:|:---:|
| **Fast3D** | [Accelerating 3D Multi-modal LLMs for Efficient 3D Scene Understanding](https://arxiv.org/abs/2507.09334) <br><sub>Wencan Huang et al.</sub> | ACM&nbsp;MM&nbsp;2025 | Chat-Scene | [✅](https://github.com/wencan25/Fast3D) |
| **AdaToken-3D** | [Dynamic Spatial Gating for Efficient 3D Large Multimodal-Models Reasoning](https://arxiv.org/abs/2505.12782) <br><sub>Kai Zhang et al.</sub> | IROS&nbsp;2025 | LLaVA-3D | 🔒 |
| **DTC** | [Zero-shot 3D Question Answering via Voxel-based Dynamic Token Compression](https://cvpr.thecvf.com/virtual/2025/poster/33335) <br><sub>Hsiang-Wei Huang et al.</sub> | CVPR&nbsp;2025 | Multi-frame VLM | 🔒 |

## 🤝 Contributing

Contributions are very welcome! To add a paper, open a PR that:

1. Places the entry in the correct **year** section, sorted by **venue date (newest first)**.
2. Follows the row format: `**Method** | [Title](link) | Venue | Backbone | Code`.
3. Links code with ✅ (or marks 🔒 if unreleased).

## 📄 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
