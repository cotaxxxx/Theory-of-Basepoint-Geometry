> [!IMPORTANT]
> This workspace has moved to
> [basepoint-geometry/theory](https://github.com/cotaxxxx/basepoint-geometry/tree/main/theory).
> This repository is retained temporarily for migration review and is not the
> source of truth.

# Theory of Basepoint Geometry

**基点幾何論**

This repository is the publication workspace for the theory of **Basepoint Geometry**. It organizes the general theory and its two groups of particular studies into one coherent mathematical program.

> Research materials; no certification claims unless explicitly stated.

## Structure

| Part | English title | Scope |
|---|---|---|
| 総論 | [General Theory](general-theory/README.md) | Definitions, the general framework, symmetry, stability, and common theorems |
| 各論Ⅰ | [Particular Studies I](particular-studies-i/README.md) | Spheres, spheroids, ellipsoids, and their stationary-basepoint structures |
| 各論Ⅱ | [Particular Studies II](particular-studies-ii/README.md) | Shape deformation, stationary-orbit bifurcation, and symmetry breaking |

## Research hierarchy

**Basepoint Geometry** studies how a geometric object and a movable base point jointly determine an energy landscape, its stationary points, and their changes under deformation.

The present hierarchy is:

1. establish concrete results in the particular studies;
2. extract the common structures into the general theory;
3. use the resulting geometric theory as the foundation for future **Basepoint Dynamics**.

Basepoint Dynamics is the long-term destination, not a claim of the present repository.

## Repository roles

- This repository contains the paper structure and publication materials for the theory.
- [basepoint-geometry](https://github.com/cotaxxxx/basepoint-geometry) is the project-level source for research rules, canonical terminology, decisions, and general-theory seeds.
- Individual experimental repositories contain object-specific implementations, diagnostics, and evidence.

The initial rules reference is pinned to:

**cotaxxxx/basepoint-geometry@d0a77680997c768d3be5194936814bed74833fe2**

## Evidence discipline

Every numerical or computational statement must identify its derivation class and claim scope. In particular, the following are not interchangeable:

- exact derivation;
- high-precision numerical evidence;
- diagnostic evidence;
- certified enclosure.

Agreement between independent computations strengthens candidate evidence but does not by itself create a certified enclosure.

## Current status

See [STATUS.md](STATUS.md).

The repository is currently an organizational and drafting workspace. It contains no certified theorem or certified numerical enclosure unless a later document states otherwise with explicit scope and evidence.
