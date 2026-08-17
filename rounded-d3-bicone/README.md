# Rounded D3-Bicone Reproducibility Package

**Manuscript:** *A Certified O(2)-to-D3 Splitting of a Stationary Circle for a Cone-Volume-Weighted Radial-Normal Angle Functional*  
**Author:** Katsushi Furuta  
**Affiliation:** Independent Researcher, Japan

## Package scope

The supplied archive contains the manuscript LaTeX source, bibliography, figures, deterministic figure generator, exact symbolic audits, Arb/Acb interval-certificate scripts, machine-readable outputs, and reproducibility documentation accompanying the manuscript.

The package README reports the certified local stationary-point sequence

`7 -> 4 -> 7 -> 4 -> 1`

and the exact equatorial area formula

`Area(B_epsilon) = pi (1 - 4 epsilon^2)`.

## Reproducibility status recorded in the supplied package

`REPRODUCIBILITY_REPORT.md` records all three symbolic audits as `PASSED` and all three interval certificates as `CERTIFIED`. It also reports a separate cross-version rerun and independent finite-difference checks as corroboration.

The package explicitly limits its claims to a local classification near the central base point and organizing parameter value; it does not claim global branch continuation, global nonexistence of additional stationary points, a new abstract singularity type, or a general theorem for arbitrary convex-body families.

## Files

- `supplement/Furuta_Bicone_D3_Supplement.zip` — supplied source and reproducibility archive, expected filename.
- `SHA256SUMS.txt` — registered checksum for the supplied archive.

## Integrity

The archive itself contains `MANIFEST.sha256` for its distributed internal files.
