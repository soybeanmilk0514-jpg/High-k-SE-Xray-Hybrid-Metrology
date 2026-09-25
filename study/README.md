# Study Notes

## SE

Spectroscopic Ellipsometry measures polarization change rather than film thickness directly.

Typical measured quantities:

- Ψ: amplitude-ratio related parameter
- Δ: phase-difference related parameter

A virtual optical model is fit to the measured response.

## Inverse Problem

If multiple model parameters generate similar signals, the fitting problem becomes ill-posed.

Examples of coupled parameters:

- thickness
- refractive index
- extinction coefficient
- roughness

## XRR

X-ray Reflectivity uses low-angle reflected X-ray intensity.

In the project it was connected to:

- critical angle → density-related information
- Kiessig fringes → thickness
- reflectivity decay → roughness

## Feed-forward Constraint

An independently measured structural parameter is inserted into another model as a fixed or strongly constrained value.

This reduces the number of free variables.

## Fixed vs Floating

- Fixed: held constant during fitting
- Floating: optimized by the fitting algorithm

Fewer floating variables do not automatically guarantee a correct model, but independent physical constraints can reduce non-unique solutions.

## Cross-Validation

The presentation used STEM as a physical reference in the published case study to show why numerical fit quality and physical correctness must be evaluated separately.
