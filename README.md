# S3G-Net: Lightweight Banded Network for Real-Time Speech Enhancement
### Objective results on VoiceBank+DEMAND (VB+DEMAND) test set.

| Model | Params (M) | MACs (G) | Causal | PESQ | CSIG | CBAK | COVL | STOI |
|------|------------|----------|--------|------|------|------|------|------|
| Noisy | – | – | – | 1.97 | 3.34 | 2.44 | 2.63 | 0.921 |
| xLSTM-SENet | 2.20 | – | No | 3.48 | 4.74 | 3.93 | 4.22 | 0.960 |
| MBTU-SE | 0.40 | – | No | 3.39 | 4.65 | 3.83 | 4.12 | 0.950 |
| Mamba-SEUNet | 6.21 | 9.09 | No | 3.59 | 4.80 | 4.02 | 4.32 | 0.960 |
| RNNoise | 0.06 | 0.04 | Yes | 2.33 | 3.40 | 2.51 | 2.84 | 0.922 |
| DCCRN | 3.70 | 14.36 | Yes | 2.79 | 3.74 | 3.13 | 2.75 | 0.938 |
| TSRM | 2.63 | – | Yes | 2.98 | 4.36 | 3.58 | 3.70 | – |
| FRCRN | 10.27 | 12.30 | Yes | 3.21 | 4.23 | 3.64 | 3.73 | 0.942 |
| DeepFilterNet2 | 1.78 | 0.35 | Yes | 3.08 | 4.30 | 3.40 | 3.70 | 0.943 |
| CCFNet+ | 0.62 | 1.47 | Yes | 3.03 | 4.27 | 3.55 | 3.61 | 0.950 |
| FSPEN | 0.096 | 0.09 | Yes | 2.97 | – | – | – | 0.942 |
| LiSenNet | 0.037 | 0.06 | Yes | 3.07 | – | – | – | 0.939 |
| **Proposed S³G-Net** | **0.030** | **0.063** | **Yes** | **3.607** | **4.36** | **3.29** | **3.92** | **0.938** |
