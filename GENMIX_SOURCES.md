# GenMix Sources

This document provides additional source-level notes for the mixed-source evaluation set referred to as **GenMix** in the submission.

## Overview

GenMix is constructed to complement the benchmark evaluation by introducing broader source diversity in synthetic videos.

It combines real videos from a public real-video source with synthetic videos collected from multiple heterogeneous source types.

## Source Categories

The synthetic sources in GenMix are grouped into the following categories.

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

## Why a Mixed-source Setting

The purpose of GenMix is to extend evaluation beyond a single benchmark configuration and expose the detector to a broader range of synthetic-video sources.

Compared with a a single-source or narrower-source setting, this construction increases variation in:

- generation pipelines,
- visual appearance,
- motion characteristics,
- rendering styles, and
- source provenance.

This design is intended to provide a more heterogeneous evaluation setting for testing generalization.

## Repository Support Files

The following repository files are relevant to GenMix:

- `DATASET_DETAILS.md` for the overall dataset setting and source counts,
- `DATA_ACCESS.md` for source access principles and redistribution boundaries, and
- `metadata/source_links.csv` for source-level references and access notes.

## Summary

GenMix is a mixed-source evaluation set designed to complement the benchmark setting in the submission by introducing greater source diversity in synthetic videos while documenting source provenance at the source level.
