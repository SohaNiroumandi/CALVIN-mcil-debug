# CALVIN MCIL Reproduction (Debug Dataset)

This repo contains my attempt at reproducing results from  
**[CALVIN: A Benchmark for Language-Conditioned Policy Learning](https://arxiv.org/pdf/2112.03227.pdf)**.

## Setup
- Used the official CALVIN GitHub repo: https://github.com/mees/calvin
- Environment: MacBook Air (CPU only)
- Dataset: Debug split (1.3 GB)

## Training Command
See `run_command.txt` for the exact command used.

## Results
- Training ran for 2 epochs on CPU.
- Logs saved in `training_logs/metrics.csv`.

## Notes
- Disabled rollout and tsne callbacks (too heavy for CPU).
- Reduced batch size to 8.
- Limited train batches and validation batches for faster run.

