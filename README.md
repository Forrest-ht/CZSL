# Vision-Guided Prototype Expansion and Mutual Contrast for Compositional Zero-Shot Learning

Official repository for the paper:

**Vision-Guided Prototype Expansion and Mutual Contrast for Compositional Zero-Shot Learning**

## Overview

Compositional Zero-Shot Learning (CZSL) aims to recognize unseen attribute-object compositions by transferring knowledge from seen compositions.

This project focuses on two key challenges in CZSL:

- **Prototype sparsity**, where a single attribute prototype is insufficient to capture diverse cross-object visual manifestations
- **Projected domain drift**, where visual features may drift away from appropriate semantic regions during training

To address these issues, the proposed framework introduces:

- **Vision-guided Explanation Matching Module (VEMM)** for attribute prototype expansion
- **Mutual contrastive learning** for reducing projected domain drift

## Status

🚧 **Code release is planned after paper acceptance.**

This repository is currently maintained as the project homepage for the paper  
**“Vision-Guided Prototype Expansion and Mutual Contrast for Compositional Zero-Shot Learning”**.

To support transparency and reproducibility, the full implementation, pretrained checkpoints, and detailed usage instructions will be released after the paper is officially accepted.

## Planned Release Contents

The public release will include:

- training and inference code
- data preprocessing scripts
- experiment configuration files
- pretrained checkpoints
- evaluation scripts
- instructions for reproducing the main results

## Repository Structure

The repository will be organized as follows:

```text
.
├── configs/
├── datasets/
├── models/
├── scripts/
├── tools/
├── train.py
├── test.py
├── requirements.txt
└── README.md


## Repository Structure

Experiments are conducted on standard CZSL benchmarks, including:
	•	MIT-States
	•	UT-Zappos50K

## Training

python train.py --config configs/[your_config].yaml

## Evaluation

python test.py --config configs/[your_config].yaml --checkpoint [path_to_checkpoint]

Citation

If you find this work useful, please cite our paper:

@article{
  title={Vision-Guided Prototype Expansion and Mutual Contrast for Compositional Zero-Shot Learning},
  journal={The Visual Computer},
  year={2026}
}
