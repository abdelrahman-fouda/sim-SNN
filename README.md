# sim-SNN (Isaac Lab + SKRL + snnTorch)


## Installation Requirements

### Software
- **OS:** Ubuntu 22.04+ (recommended) / Linux
- **Python:** 3.10+ (match Isaac Lab requirements)
- **CUDA:** (if using GPU) CUDA 11.8+ and matching NVIDIA driver
- **Isaac Lab / Isaac Sim:** (version TBD — will be pinned)
- **PyTorch:** (version pinned in `requirements.txt` / `pyproject.toml`)
- **snnTorch:** https://snntorch.readthedocs.io/en/latest/
- **SKRL:** https://skrl.readthedocs.io/en/latest/index.html

### Hardware
- CPU: x86_64
- RAM: 16GB+ (32GB recommended for sim)
- GPU: NVIDIA GPU with 8GB+ VRAM recommended (optional but strongly recommended)

## Repository Structure

```
sim-SNN/
  configs/        # experiment/config files (yaml/json)
  docs/           # extra documentation (method, design notes)
  notebooks/      # exploratory notebooks (optional)
  results/        # outputs (ignored or git-lfs depending on size)
  scripts/        # runnable entrypoints (train/eval/plot)
  slides/         # presentation slides (source + PDF)
  src/            # main python package / source
  tests/          # unit/integration tests
  README.md
```
