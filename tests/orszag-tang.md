---
layout: page
title: Orszag-Tang Vortex
published: false
---

[Back to all tests](../tests)

## Description

The Orszag-Tang vortex is a standard 2D MHD test problem that models the transition to supersonic MHD turbulence.
It exercises shock capturing, shock-shock interactions, and the divergence-free constraint on the magnetic field.

Since AGILE is a fully 3D code, we run this as an extruded 2D problem: the initial conditions are uniform in the $z$-direction and the domain is only a few cells deep. Results are taken from a 2D slice in the $xy$-plane.

## AGILE setup

| Parameter | Value |
|-----------|-------|
| Domain | $[0, 1]^3$ |
| Resolution | ... |
| Boundary conditions | Periodic |
| $\gamma$ | $5/3$ |
| Solver | ... |
| Final time | ... |

## Results

<!-- Add images here, e.g.:
![Pressure at t=0.5](../assets/tests/orszag-tang/pressure_t05.png)
-->

*Coming soon.*

## References

- Orszag, S. A. & Tang, C.-M. (1979), *J. Fluid Mech.*, 90, 129
