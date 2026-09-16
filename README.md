# Synthetic Data With Auditable Receipts

A public Grounded DI position paper on provenance-preserved reality, validation, and admission control for consequential use of synthetic or constructed information.

## Overview

This repository contains the 2026 report [Grounded DI — Synthetic Data With Receipts](Grounded_DI_Synthetic_Data_With_Receipts_2026.pdf). It examines why synthetic data quality is only one part of the governance problem and argues for preserving the distinction among observed, human-authored, formally derived, transformed, simulated, model-generated, and unknown information.

The report's central thesis is that Grounded DI's role is not to generate synthetic data. It is to govern the boundary between constructed information and consequential downstream use.

## Core Concept: Provenance-Preserved Reality

“Provenance-preserved reality” is the report's term for a machine-readable record of what kind of information an artifact contains and how it was produced. The categories do not automatically rank truth: observations can contain error, human-authored material can be wrong, and simulations can be useful. The value is in keeping those evidence types visible instead of silently treating them as interchangeable.

The paper summarizes the commercial thesis in a concise phrase: **the receipt records the decision; the control boundary is the product.**

## Technical Significance

A receipt or audit record cannot make synthetic data true. It can make origin attributable, generation reproducible where possible, downstream use bounded, and release rejectable when required evidence is missing. That framing connects provenance to validation and admission control rather than to a blanket claim about data quality.

## Published Evidence

- [Report PDF](Grounded_DI_Synthetic_Data_With_Receipts_2026.pdf)
- [Publication commit — August 7, 2026](https://github.com/Grounded-DI/Synthetic_Data_With_Auditable_Receipts-/commit/02dbb0e040e0f24b1ada8d16d4c21db5c6d40f8b)

The current repository contains the report and this README. It does not contain an executable data-generation pipeline, receipt schema implementation, test harness, or independent validation package.

## Status and Scope

**Status: PUBLIC POSITION PAPER / ARCHITECTURAL RECORD.** The report does not claim that auditability makes synthetic data correct, that all synthetic datasets share the same risks, or that a production data-control system is included here.

The report preserves a dated public argument about provenance and release control. It should not be read as a benchmark, certification, or deployment record.

No open-source license file is present in this repository.

## Evaluation and Collaboration

Organizations evaluating data lineage, synthetic-data governance, validation gates, or admission-control workflows may use the report as a research and proof-of-concept starting point. Grounded DI collaboration, integration, and licensing inquiries: [Grounded DI on GitHub](https://github.com/Grounded-DI).
