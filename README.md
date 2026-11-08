# TidalMesh: Adaptive Mesh Transformers for Ocean Forecasting

**Status: code released.**

This repository contains the implementation for the paper:

> **TidalMesh: Adaptive Mesh Transformers for Ocean Forecasting**  
> Victoria Ramos, Priya Raman, Sofia Alvarez  
> ICLR 2026

The released implementation covers the model, the data pipeline and the training/evaluation scripts used in the experiments.

## Repository layout

- `src/` - model, data pipeline, training and evaluation code
- `data/` - dataset preparation helpers and manifests
- `experiments/` - experiment configs and analysis notebooks

## Getting started

```bash
pip install -r requirements.txt
python -m src.train --config configs/default.yaml
```

## Citation

If you use this code, please cite the paper above.
