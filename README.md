# Synthetic Data With Auditable Receipts

Grounded DI's 2026 position paper proposes provenance receipts and admission controls for consequential use of synthetic or constructed information.

## Overview

This repository contains the 2026 report [Grounded DI — Synthetic Data With Receipts](Grounded_DI_Synthetic_Data_With_Receipts_2026.pdf). It examines why synthetic data quality is only one part of the governance problem and argues for preserving the distinction among observed, human-authored, formally derived, transformed, simulated, model-generated, and unknown information.

The report proposes a control boundary that records where information came from and determines when constructed information can enter a consequential workflow.

## Core Concept: Provenance-Preserved Reality

“Provenance-preserved reality” is the report's term for a machine-readable record of what kind of information an artifact contains and how it was produced. The categories do not automatically rank truth: observations can contain error, human-authored material can be wrong, and simulations can be useful. The value is in keeping those evidence types visible instead of silently treating them as interchangeable.

The paper summarizes the commercial thesis in a concise phrase: **the receipt records the decision; the control boundary is the product.**

## Technical Significance

The proposed receipt records origin and generation method. Validation and admission rules can then hold a downstream release when required evidence is missing.

## Published Evidence

- [Report PDF](Grounded_DI_Synthetic_Data_With_Receipts_2026.pdf)
- [Publication commit — August 7, 2026](https://github.com/Grounded-DI/Synthetic_Data_With_Auditable_Receipts-/commit/02dbb0e040e0f24b1ada8d16d4c21db5c6d40f8b)

The current repository contains the report and this README. It does not contain an executable data-generation pipeline, receipt schema implementation, test harness, or independent validation package.

## Status and Scope

**Status: PUBLIC POSITION PAPER / ARCHITECTURAL RECORD.** The PDF presents the control design and its argument for preserving evidence type and origin.

No open-source license file is present in this repository.

## Evaluation and Collaboration

Organizations evaluating data lineage, synthetic-data governance, validation gates, or admission-control workflows can use the report to define a controlled technical evaluation. Grounded DI collaboration, integration, and licensing inquiries: [Grounded DI on GitHub](https://github.com/Grounded-DI).
