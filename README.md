# Residual Transformation Tool — CANONICAL v1.0.2a

Canonical framework baseline for residual-driven research, validation, governance, and deployment preparation.

## Status

This repository is ready as a **framework baseline**.

It canonizes:
- the frozen condensed v1.0 architecture
- subject-aware measured input
- subject comparison
- preflight audit / hardening
- the current-master workflow

It does **not** claim that all live sample blockers are solved.

Known open sample-state blocker:
- `SET-003`

## Core workflow

measurement -> residual -> transformation -> validation -> governance -> deployment

## Core principle

Residual is treated as a guidance signal, not only as error.

Observed - Expected = Residual

The framework uses residuals to:
- detect mismatch
- guide transformation
- accumulate evidence
- govern promotion
- gate deployment-oriented interpretation

## Canonical workbook architecture

- `README`
- `Inputs`
- `Research_Runs`
- `Residuals`
- `Settings`
- `Packages`
- `Validation_Loop`
- `Governance`
- `Deployment`
- `Dashboard`
- `Subjects`
- `Subject_Comparison`
- `Preflight_Audit`

## Repository layout

- `bootstrap/`
  Reusable session/bootstrap package

- `workbooks/canonical/`
  Canonical workbook and preflight master

- `workbooks/fallback/`
  Earlier baseline and fallback workbook variants

- `docs/`
  GitHub-facing framework documentation

- `release_notes/`
  Canonical release notes

## Recommended default artifact

Use:

`workbooks/canonical/Residual_Transformation_Tool_CANONICAL_v1_0_2a.xlsx`

If you want the explicit preflight-first working file, use:

`workbooks/canonical/residual_transformation_tool_current_master_v1_0_2a_preflight.xlsx`

## Recommended startup pattern

1. Open the canonical workbook.
2. Open `Preflight_Audit`.
3. Confirm the `Dashboard`.
4. Identify the current blocker.
5. Enter or review measured runs.
6. Proceed only after critical preflight checks pass.

## Subject-aware support

The framework supports reusable `Subject_ID` linkage for future projects, allowing measured runs to be tied to:

- devices
- samples
- people
- material batches
- locations
- custom entities

This allows future subject-specific comparison without rebuilding the architecture.

## Canonicalization boundary

Canonicalization applies to:
- structure
- workflow
- gating logic
- status model
- hardening layers

Canonicalization does not assert that unresolved operational blockers are solved.

## Permissions / licensing

This repository is intentionally **unlicensed**.

No license is granted.
No permission to use, copy, modify, distribute, or commercialize is granted except where such rights exist independently under applicable law.

## Included artifacts

- `workbooks/canonical/Residual_Transformation_Tool_CANONICAL_v1_0_2a.xlsx`
- `workbooks/canonical/residual_transformation_tool_current_master_v1_0_2a_preflight.xlsx`
- `bootstrap/residual_research_bootstrap_v1_0.zip`
- `release_notes/Residual_Transformation_Tool_CANONICAL_v1_0_2a_RELEASE_NOTES.md`
- `workbooks/fallback/residual_transformation_tool_current_master_v1_0_2.xlsx`
- `workbooks/fallback/residual_transformation_tool_v1_0_debugged.xlsx`
- `workbooks/fallback/residual_transformation_tool_v1_0_1_subject_ready.xlsx`
- `workbooks/fallback/residual_transformation_tool_v1_0_2_subject_comparison_fixed.xlsx`

## Missing at packaging time

- none
