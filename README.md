# Bruno Weber

Mechanical engineer and software developer working at the intersection of computational modeling, scientific Python, and front-end engineering. I build verification-minded numerical workflows and clear interfaces for technical problems.

## Current focus

### `laser-welding-thermal-fem` — research and specification in progress

Building the scientific foundation for a verification-first model of a moving Gaussian laser heat source on a thin metal plate.

The current phase covers:

- a critical, traceable literature review of laser-welding physics and moving heat-source models;
- a dimensionally consistent, thickness-integrated 2D heat equation and weak formulation;
- explicit SI-unit energy accounting and Gaussian source-normalization checks;
- a verification plan using energy balance, manufactured solutions, mesh/time convergence, and a compatible Rosenthal comparison;
- a planned Python implementation with FEniCSx/DOLFINx.

The scope is deliberately conduction-focused, with explicit limits around melting, liquid flow, and keyhole physics. No solver or public repository has been released yet; implementation and experimental validation are later milestones.

## Selected work

### [Cooling Schedule Explorer](https://github.com/brunowe/simulation-fec/pull/26)

A front-end case study exploring how engineering inputs can be translated into a clear, interactive thermal schedule.

- React 19, Vite 8, and p5.js 2
- Accessible controls, responsive layout, 12 automated tests, and GitHub Actions CI
- Deliberately illustrative and non-predictive
- Status: [modernization in draft PR #26](https://github.com/brunowe/simulation-fec/pull/26)

### [hipeerLab Platform](https://github.com/amaralc/hipeerlab-platform-fe)

Contributor to a collaborative platform supporting a distributed COVID-19 initiative.

- 115 commits
- 37 pull requests, 31 merged
- Selected contributions: [team page (#42)](https://github.com/amaralc/hipeerlab-platform-fe/pull/42), [contribution page (#117)](https://github.com/amaralc/hipeerlab-platform-fe/pull/117), and [transparency interface (#134)](https://github.com/amaralc/hipeerlab-platform-fe/pull/134)

## Areas of work

- Computational modeling: heat transfer, finite elements, verification, and validation
- Scientific software: Python, numerical workflows, and reproducible technical research
- Front-end engineering: React, JavaScript, interactive visualization, and accessibility

## Em português

Sou engenheiro mecânico e desenvolvedor de software. Trabalho na interseção entre modelagem computacional, software científico em Python e interfaces web. Meu foco atual é a pesquisa e especificação de um projeto de FEM térmico transiente para soldagem a laser; a implementação e o repositório público virão em etapas posteriores.
