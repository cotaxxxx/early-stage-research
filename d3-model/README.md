# Three-Dimensional Dual-Phase Model (D3 Model)

**Manuscript:** *三次元双対位相モデル（D3 モデル）— 立方体の体対角 60° 位相、四次主モードの厳密最適性、および高次調和認証問題*  
**Edition:** v1.0 Expert Handoff Edition  
**Date:** 2026-06-16  
**Drafted by:** K. Furuta  
**Support:** ChatGPT (OpenAI)

## Scope

This project extends the dual-phase defect from planar angles to rotations in `SO(3)` and studies the cube as a concrete optimization problem.

## Proved within the manuscript

- the three-dimensional dual-phase defect and its zero-set characterization;
- scale, rotation, and symmetry invariance;
- a regular-tetrahedron exact zero;
- reduction of the cube problem to the double quotient `O\SO(3)/O`;
- the body-diagonal 60° rotation as an exact symmetry center;
- exact global optimality of that rotation for the first nonconstant octahedrally invariant harmonic mode (`ell = 4`), including
  `sum_{i,j} r_ij^4 >= 11/9`, with equality on `O R_* O`.

## Open point

The global minimizing property for the full cube defect is not proved. The remaining central problem is to certify that harmonics of degree `ell >= 6` cannot overturn the degree-four optimum.

## Numerical support reported in the manuscript

- `E_C(I) ≈ 0.04802833`
- `E_C(R_*) ≈ 0.01494550`
- positive tangent-space Hessian at the candidate in representative floating-point calculations
- global `SO(3)` numerical searches supporting the same orbit

These numerical results are not interval proofs.

## Files

- `paper/D3_model_hypothesis_paper_v1.0_ja.pdf` — manuscript binary, expected filename.
- `SHA256SUMS.txt` — registered checksum for the supplied PDF.

## Status

**Pre-peer-review hypothesis paper / expert-handoff note.** The manuscript explicitly distinguishes proved statements, numerical evidence, the central conjecture, and the remaining certification program.
