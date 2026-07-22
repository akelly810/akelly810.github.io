---
layout: page
title: Publications
---

## 2026
- **Astrophysics on GPUs: introducing AGILE 1.0**, Porth, O., **Kelly, A.**, Willocx, O., Wu, H., Vos, J., Zhou, Y., Olivares Sánchez, H. R., Oostrum, L., Hidding, J., Azizi, V., Xia, C., Keppens, R., & Teunissen, J. <span class="pub-badge">Submitted</span> *RAS Techniques and Instruments*, 2026.
  [arXiv](https://arxiv.org/abs/2607.19277){:.pub-link}
  <details class="pub-abstract"><summary>Abstract</summary>
  <p>We present AGILE, a GPU-enabled adaptive mesh refinement (AMR) framework for the solution of (near-)conservation laws which occur in astro- and solar-physical applications. AGILE is written in modern Fortran 2003, inherits part of its modules and mesh handling from MPI-AMRVAC, and achieves excellent GPU performance via OpenACC offloading. We here discuss the design decisions which enable AGILE to perform cost-efficient and scalable deeply nested AMR simulations with moderate block sizes of e.g. 16³ cells. AGILE currently implements several physics modules, i.e. hydrodynamics, frozen-field hydrodynamics, magnetohydrodynamics and special-relativistic hydrodynamics, and can easily be extended further through its modular design. Besides strong scaling tests to up to 2048 GPUs and standard benchmarks which show consistent performance across a large range of devices and problem sizes, we demonstrate AGILE's capabilities by means of state-of-the-art science applications with all currently available physics modules.</p>
  </details>

- **foap4: Adaptive mesh refinement with OpenACC, MPI, and p4est**, Teunissen, J., Olivares Sánchez, H. R., Vos, J., Oostrum, L., Hidding, J., Azizi, V., Zhou, Y., Wu, H., **Kelly, A.**, Willocx, O., Xia, C., Keppens, R., & Porth, O. <span class="pub-badge">Submitted</span> *Computer Physics Communications*, 2026.
  [arXiv](https://arxiv.org/abs/2605.07612){:.pub-link}
  <details class="pub-abstract"><summary>Abstract</summary>
  <p>GPUs and other accelerators are increasingly used for scientific computing. In the future, we want to add GPU support to parallel adaptive mesh refinement (AMR) codes written in Fortran. To understand which changes are necessary to obtain good performance we have developed foap4, an AMR framework implemented in Fortran that uses OpenACC, MPI, and the p4est library. We discuss the design and implementation of the framework. Several benchmark problems are considered, in which Euler's equations of gas dynamics are solved using explicit time integration. These benchmarks are performed in both 2D and 3D, using static and adaptive meshes, for varying problem sizes on different hardware. Our results show that AMR simulations can be carried out efficiently on GPUs with OpenACC and MPI, even when using relatively small grid blocks of 8³ or 16³ cells.</p>
  </details>

- **Thermal instability in coronal loops: Linking eigenvalue spectra to time-dependent evolution**, **Kelly, A.**, Keppens, R., & De Jonghe, J., <span class="pub-badge pub-badge--first">First author</span> *Astronomy & Astrophysics* (2026).
  [DOI](https://doi.org/10.1051/0004-6361/202659934){:.pub-link} [arXiv](https://arxiv.org/abs/2604.24315){:.pub-link}
  <details class="pub-abstract"><summary>Abstract</summary>
  <p>Cool, dense condensations such as coronal rain and prominences suggest that coronal plasma can undergo runaway radiative cooling. Connecting this behaviour to linear thermal modes requires us to fully understand the deeper connection between eigenvalue spectra and actual time-dependent evolution. We aim to clarify this intricate link for a simplified, coronal-only model of a stratified coronal loop by combining spectral, linear initial-value, and nonlinear simulations of the same loop setup. We study waves and instabilities, as well as temporal evolutions for a 1D hydrostatic, thermally balanced loop with optically thin radiation and prescribed heating. The non-adiabatic spectrum is computed with our open-source Legolas code. We demonstrate our newly developed boundary value-initial value solver Legolas-IVP, where linear evolutions are performed for controlled perturbations, and fully equivalent nonlinear runs are carried out with MPI-AMRVAC. The spectrum contains discrete acoustic modes and a thermally unstable branch including a thermal continuum. Linear initial-value experiments with isochoric, isobaric, and isentropic pulses highlight how the polarisation of the eigenmodes demonstrates physically consistent behaviour expected from the eigenspectrum. Even in the linear stage, thermal imbalance drives siphon-like flows toward the cooling region. Growth rates from Legolas-IVP agree with spectral predictions and are reproduced in MPI-AMRVAC, which follows the condensation through runaway cooling to chromospheric temperatures, with the cool dense blob sliding under gravity toward the loop footpoint. The spectral-linear-nonlinear investigation demonstrates a direct link between thermal eigenmodes and condensation dynamics, providing a basis for extending to fully 3D MHD models.</p>
  </details>

## 2025
- **The Hydrodynamic Thermal Continuum, with Applications to Stratified Atmospheres and 1D Coronal Loop Models**, Keppens, R., De Jonghe, J., **Kelly, A.**, Brughmans, N., & Goedbloed, H., *The Astrophysical Journal* (2025).
  [DOI](https://doi.org/10.3847/1538-4357/adea43){:.pub-link} [arXiv](https://arxiv.org/abs/2506.23591){:.pub-link}
  <details class="pub-abstract"><summary>Abstract</summary>
  <p>Using both analytical and numerical means, we demonstrate that linear stability analysis of a hydrodynamic stratified atmosphere or a 1D coronal loop model in non-adiabatic settings features a thermal continuum corresponding to highly localized eigenfunctions. This thermal continuum can be precomputed, involving the net heat-loss function and its partial derivatives, and is the generalization of the thermal instability introduced by Parker (1953). We account for a thermal imbalance, directly affecting thermal instability growth rates. We present completely general equations that govern all eigenmodes, including non-adiabatically affected p- and g-modes of the stratified settings. We intend to clarify how linear thermal instability is relevant for solar loops that show spontaneous in-situ condensations, and eliminate recent confusion on specific isochoric routes to linear instability alongside other thermal instability channels. The thermal continuum, previously identified as a crucial ingredient in magnetohydrodynamic eigenmode spectra for coronal loops and atmospheres, drives multithermal aspects across our universe, such as forming solar coronal rain and prominences, or cold cloud creation in intracluster to interstellar medium environments.</p>
  </details>

## Talks
- **Coronal Loops Workshop XII**, Northumbria University, Newcastle (8–11 Jun 2026).
  *"Thermal instability in coronal loops: linking eigenvalue spectra to time-dependent evolution"*

- **FNRS Contact Group *Astronomie & Astrophysique*** (14 Oct 2025).
  *"Thermal instability and condensation formation in coronal loops"*

- **KU Leuven CmPA Seminar** (23 May 2025).
  *"Time-dependent simulation of thermal instability in 1D coronal loop models"*
