# Compute in Transit 01 — Compute in Transit: the Idea and the Budget

What it means to compute on data while it crosses a link, what Optalysys's photonic link module (Kundu et al., arXiv:2608.21536) is reported to do, and the arithmetic that decides what fits: operations per byte at line rate (0.40 to 3.96 on a QSFP56 link for a "tens of GFLOPs" claim), whether the optical transform is charged against that budget, the published operation set and what it lacks, precision, energy per bit, and placement at an endpoint, in the link or in a switch. It ends with five tests any candidate must pass and a first placement of the data movements of LLM training and inference, with an interactive budget calculator.

Topics: Compute in transit, Operations per byte, Photonic link module, Published operation set, Placement, Five tests.

**Live site:** https://brendanjameslynskey.github.io/CiT_01_Compute_in_Transit/

Part of the [Compute in Transit series](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit). Every number comes from [analysis/results.md](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit/blob/main/analysis/results.md), written by [analysis/cit_budget.py](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit/blob/main/analysis/cit_budget.py), or from a source cited on the slide; claimed and illustrative figures are labelled as such. Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/LLM_Hub_Compute_in_Transit/#glossary). Sister series: [Fourier Optics for Inference](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference), [LLM Inference Simulators](https://github.com/BrendanJamesLynskey/LLM_Hub_Inference_Simulators), [FHE Accelerator Simulators](https://github.com/BrendanJamesLynskey/FHE_Hub_Accelerator_Simulators).

Licence: CC BY 4.0.
