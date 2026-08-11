# Bruno Weber

Mechanical engineer and software developer building numerical simulations, verification-minded scientific workflows, and clear interfaces for engineering problems.

[Simulation Lab](https://brunoweber-simlab.netlify.app/) · [Grain Growth Model](https://brunoweber-simlab.netlify.app/simulations/grain-growth) · [Source code](https://github.com/brunowe/simulation-fec)

## Current focus

### [Bruno Weber - Simulation Lab](https://brunoweber-simlab.netlify.app/)

A public portfolio for interactive numerical experiments across science and engineering.

The first released experiment is the [Grain Growth Model](https://brunoweber-simlab.netlify.app/simulations/grain-growth), a qualitative two-dimensional grain-coarsening simulation built as a seeded neighbor-copy Monte Carlo Potts variant.

- Pure numerical engine separated from React and Canvas rendering
- Periodic Voronoi initialization, reproducible seeds, live metrics, and interactive controls
- React 19, Vite 8, automated CI, and production deployment on Netlify
- 86 automated tests covering the model, interface, routing, and public build
- Formulation, assumptions, limitations, and scientific references documented alongside the experiment

**Status:** experimental and qualitative. Lattice units and Monte Carlo sweeps are not physical length and time, and the model is not calibrated to a specific material.

### Transient thermal FEM for a moving laser heat source

Building the scientific foundation for a verification-first model of a moving Gaussian laser heat source on a thin metal plate.

The current research and specification phase covers:

- a critical, traceable literature review of laser-welding physics and moving heat-source models;
- a dimensionally consistent, thickness-integrated 2D heat equation and weak formulation;
- explicit SI-unit energy accounting and Gaussian source-normalization checks;
- a verification plan using energy balance, manufactured solutions, mesh/time convergence, and a compatible Rosenthal comparison;
- a planned Python implementation with FEniCSx/DOLFINx.

**Status:** research and model specification in progress. No public solver or experimental validation has been released yet.

## Selected collaboration

### [hipeerLab Platform](https://github.com/amaralc/hipeerlab-platform-fe)

Contributor to a collaborative React platform supporting a distributed COVID-19 initiative.

- 115 commits
- 37 pull requests, 31 merged
- Selected contributions: [team page (#42)](https://github.com/amaralc/hipeerlab-platform-fe/pull/42), [contribution page (#117)](https://github.com/amaralc/hipeerlab-platform-fe/pull/117), and [transparency interface (#134)](https://github.com/amaralc/hipeerlab-platform-fe/pull/134)

## Areas of work

- **Computational modeling:** heat transfer, Monte Carlo methods, finite elements, verification, and validation
- **Scientific software:** Python, numerical workflows, reproducible research, and explicit model limitations
- **Web engineering:** React, JavaScript, interactive visualization, accessibility, testing, and CI/CD

## Now

- Validating the Grain Growth Model against selected reference cases
- Preparing the transient thermal FEM implementation
- Expanding Simulation Lab with numerical experiments across science and engineering

<details>
<summary>Em português</summary>

Sou engenheiro mecânico e desenvolvedor de software. Trabalho na interseção entre simulação numérica, software científico e interfaces web para problemas de engenharia.

O [Simulation Lab](https://brunoweber-simlab.netlify.app/) já está publicado com seu primeiro experimento, um modelo qualitativo de crescimento de grão. Em paralelo, desenvolvo a base científica e o plano de verificação de um modelo FEM térmico transiente para uma fonte laser móvel.

</details>
