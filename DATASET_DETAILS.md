
# Dataset Details

This document provides additional dataset details for the anonymous submission.

## GenBuster-200K

GenBuster-200K is the publicly released dataset suite used in BusterX.

In this work, we use the **benchmark split** of GenBuster-200K for the main evaluation reported in the paper.

GenBuster-200K also provides a separate **test split**. In our experiments, this split is used **only for threshold calibration** of score-based training-free baselines such as D3 and ReStraV.

No threshold tuning is performed on the GenBuster benchmark split or on the mixed-source evaluation set described below.

## GenMix

In addition to the benchmark setting, we construct a mixed-source evaluation set referred to as **GenMix**.

GenMix contains:

- **1,000 real videos** sampled from **Vript**, and
- **914 synthetic videos** collected from multiple source types.

The synthetic portion includes:

- videos associated with **closed-source generation systems**,
- videos associated with **open-source generation models**, and
- synthetic videos drawn from a **publicly released dataset source**.

This mixed-source construction complements the benchmark setting used in the main paper by introducing broader source diversity in synthetic videos.

## Synthetic Source Composition of GenMix

The per-source synthetic counts are:

- **Emu**: 121
- **Gen-4.5**: 60
- **NeverEnds**: 118
- **Sora2**: 165
- **Veo3.1**: 132
- **VideoCrafter2**: 118
- **VideoPhy2**: 101
- **VideoPoet**: 99

These sources sum to **914 synthetic videos** in total.

## Evaluation Usage Notes

The datasets are used with the following principles:

- The **GenBuster-200K benchmark split** is used for the main evaluation in the paper.
- The **GenBuster-200K test split** is used only for threshold calibration of selected score-based training-free baselines.
- No threshold tuning is performed on the **GenBuster benchmark split**.
- No threshold tuning is performed on **GenMix**.

## Summary

Overall, the supplementary dataset setting includes:

- a benchmark evaluation on **GenBuster-200K**, and
- an additional mixed-source evaluation on **GenMix**, which combines real videos from **Vript** with synthetic videos from multiple heterogeneous sources.
