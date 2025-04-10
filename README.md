# TERRA Spaceflight Analysis

**Lead Developer**: Kirill Grigorev  
**Institution**: Weill Cornell Medicine

This repository contains the consolidated notebook used in the analysis for:

> **Al-Turki, T.M., Maranon, D.G., Nelson, C.B., et al.**  
> *Telomeric RNA (TERRA) increases in response to spaceflight and high-altitude climbing*.  
> *Communications Biology* **7**, Article number: 698 (2024).  
> [https://doi.org/10.1038/s42003-024-06014-x](https://doi.org/10.1038/s42003-024-06014-x)

---

## Repository Overview

This repository hosts a single Jupyter notebook used for the comprehensive analysis of TERRA repeat motifs in RNA-seq data across multiple contexts:
- SpaceX Inspiration4 astronaut blood samples
- NASA Twins Study data
- High-altitude climbing samples (Mt. Everest)
- Simulated microgravity samples
- Ionizing radiation cell culture studies

Key features of the analysis include:
- Telomeric motif detection (`UUAGGG`, `UUAGG`, etc.) via k-mer enrichment
- Mann–Whitney U test comparisons across experimental groups
- Pearson correlation analysis of motif co-occurrence
- Visualization of longitudinal expression patterns

---

## Files

- `202504-I4-TERRA-consolidated_V2.ipynb`: Core analysis notebook (Jupyter)
- `202504-I4-TERRA-consolidated.html`: Rendered version of the notebook (for quick preview)

---

## Citation

If you use this notebook or its derived analysis in your work, please cite the paper above.
