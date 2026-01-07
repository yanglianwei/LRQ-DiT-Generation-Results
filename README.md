# LRQ-DiT Generation Results

This repository contains the generation results of various quantization methods applied to DiT (Diffusion Transformer) models, evaluated on two benchmark datasets: **OpenSORA** and **VBench**.

## Directory Structure

LRQ-DiT-Generation-Results/
├── OpenSORA_Set/
│ ├── FP/ # Full-precision baseline
│ ├── W3A4/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/ # Our proposed method
│ ├── W3A6/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W3A8/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W4A4/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W4A6/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ └── OpenSORA_Set.txt # Metadata or prompts for OpenSORA set
├── Vbench_Set/
│ ├── FP/
│ ├── W3A4/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W3A6/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W3A8/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W4A4/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ ├── W4A6/
│ │ ├── 1.SmoothQuant/
│ │ ├── 2.Q-DIT/
│ │ ├── 3.PTQ4DT/
│ │ ├── 4.QuaRot/
│ │ ├── 5.DuQuant/
│ │ ├── 6.VDiT-Q/
│ │ └── 7.LRQ-DIT (ours)/
│ └── Vbench_Set.txt # Metadata or prompts for VBench set
└── README.md

## Notes

- **FP**: Full-precision (baseline) results.
- **WxAy**: Quantization setting where weights are quantized to *x* bits and activations to *y* bits.
- **LRQ-DiT (ours)**: Our proposed Low-Rank Quantized DiT method, consistently placed as the 7th method in each group.
- Each subfolder (e.g., `1.SmoothQuant/`) contains generated videos or evaluation metrics corresponding to that quantization technique.

For more details, please refer to our paper or contact the authors.


