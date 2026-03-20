
# GenMix Sources

This document provides additional source-level notes for the mixed-source evaluation set referred to as **GenMix** in the submission.

## Overview

GenMix is constructed to complement the benchmark evaluation by introducing broader source diversity in synthetic videos.

It contains:

- **1,000 real videos** sampled from **Vript**, and
- **914 synthetic videos** collected from multiple source types.

The synthetic portion includes sources associated with:

- closed-source generation systems,
- open-source models,
- community-hosted sources, and
- publicly released dataset sources.

## Source Categories

The synthetic sources in GenMix are grouped into the following categories:

### Closed-source Systems

The following sources are treated as closed-source systems in this repository:

- Emu
- Gen-4.5
- Sora2
- Veo3.1
- VideoPoet

For these sources, the repository provides source-level references to official public pages, project pages, or showcase pages where applicable.

### Open-source Models

The following source is treated as an open-source generation model:

- VideoCrafter2

For this source, the repository provides a source-level reference to the official public project page.

### Community-hosted Source

The following source is treated as community-hosted:

- NeverEnds

For this source, the repository provides a source-level reference to the official public community entry point used as the source-level access reference in this repository.

### Dataset-derived Source

The following source is treated as dataset-derived:

- VideoPhy2

For this source, the repository provides a source-level reference to the corresponding public dataset or project page.

## Per-source Synthetic Counts

The synthetic portion of GenMix contains the following per-source counts:

- **Emu**: 121
- **Gen-4.5**: 60
- **NeverEnds**: 118
- **Sora2**: 165
- **Veo3.1**: 132
- **VideoCrafter2**: 118
- **VideoPhy2**: 101
- **VideoPoet**: 99

These counts sum to **914 synthetic videos** in total.

## Why a Mixed-source Setting

The purpose of GenMix is to extend evaluation beyond a single benchmark configuration and expose the detector to a broader range of synthetic-video sources.

Compared with a single-source or narrower-source setting, this construction increases variation in:

- generation pipelines,
- visual appearance,
- motion characteristics,
- rendering styles, and
- source provenance.

This design is intended to provide a more heterogeneous evaluation setting for testing generalization.

## Repository Support Files

The following repository files are relevant to GenMix:

- `DATASET_DETAILS.md` for the overall dataset setting,
- `DATA_ACCESS.md` for source access principles and redistribution boundaries,
- `metadata/genmix_source_counts.csv` for the structured per-source count table, and
- `metadata/source_links.csv` for source-level references and access notes.

## Summary

GenMix is a mixed-source evaluation set designed to complement the benchmark setting in the submission by introducing greater source diversity in synthetic videos while documenting source provenance at the source level.
