# SHRIKE: Multi-Modal Scene Graph with Kolmogorov-Arnold Experts for Audio-Visual Question Answering

[![arXiv](https://img.shields.io/badge/arXiv-2511.23304-b31b1b.svg)](https://arxiv.org/abs/2511.23304)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Official implementation of the paper **"Multi-Modal Scene Graph with Kolmogorov-Arnold Experts for Audio-Visual Question Answering"**.

> **Code release in progress.**
> The full code, model checkpoints, and the constructed multi-modal scene graph dataset will be made publicly available soon. Please watch or star this repository to be notified when they are released.

## Overview

SHRIKE addresses Audio-Visual Question Answering (AVQA), where a model must extract and fuse question-relevant cues from complex audio-visual scenes in order to answer a given question. It introduces two main components:

- **Multi-modal scene graph** — a visually grounded, structured representation that explicitly models the objects in a scene and their relationships, capturing the structural information within video that prior methods overlook.
- **KAN-based Mixture of Experts** — a Kolmogorov-Arnold Network (KAN) MoE applied at the temporal integration stage, enabling finer-grained modeling of cross-modal interactions in the question-aware fused audio-visual representation and stronger temporal reasoning.

SHRIKE achieves state-of-the-art performance on the **MUSIC-AVQA** and **MUSIC-AVQA v2** benchmarks.

## Method

<!-- Uncomment once the figure is added under assets/
![Method Overview](assets/method.png)
-->

## Dataset

As part of this work, we construct a **multi-modal scene graph dataset** that provides structured, visually grounded annotations of the objects and their relationships in audio-visual scenes, used to build the scene-graph representation in SHRIKE.

<!-- Fill in the specifics, e.g.:
- Base data / benchmark it is built on
- Number of videos, frames, or annotated scene graphs
- Object and relation categories
- Annotation format (e.g., JSON schema with an example)
-->

The dataset will be released together with the code and model checkpoints.

## Release Checklist

- [ ] Multi-modal scene graph dataset
- [ ] Model checkpoints
- [ ] Training code
- [ ] Evaluation code
- [ ] Data preprocessing scripts

## Citation

If you find this work useful, please consider citing:

```bibtex
@misc{fu2025shrike,
  title         = {Multi-Modal Scene Graph with Kolmogorov-Arnold Experts for Audio-Visual Question Answering},
  author        = {Zijian Fu and Changsheng Lv and Mengshi Qi and Huadong Ma},
  year          = {2025},
  eprint        = {2511.23304},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2511.23304}
}
```

## Contact

For questions, please open an issue or contact the corresponding author.

## License

This project is released under the [MIT License](LICENSE).
