# MEP1: Quantum Temporal Entanglement and Conscious Resonance in the Grandfather Paradox

Welcome to the Mental-Experimental Prototype 1 (MEP1), a groundbreaking exploration of quantum temporal entanglement to resolve the grandfather paradox. This updated version introduces decoherence modeling, a 4-qubit extension for multiple timeline choices, and experimental proposals for IBM Quantum and EEG feedback. Submitted by Teodor Berger, with computational support from xAI and OpenAI, MEP1 invites you to dive into the meta-temporal manifold \(T^*\), where conscious intention shapes the rhythms of time.

The preprint is available on Zenodo: [https://doi.org/10.5281/zenodo.15368835](https://doi.org/10.5281/zenodo.15368835).

## About

The grandfather paradox challenges causality in time travel. MEP1 proposes a resolution through a 3-qubit quantum circuit, modeling conscious intention as a phase \(\phi(C) = \pi \sin(\omega t)\). By simulating timeline bifurcation between the original (T0, \(|100\rangle\)) and alternate (T1, \(|011\rangle\)) timelines, MEP1 reveals a quantum heating mechanism driven by bioentanglement and vacuum fluctuations. This update enhances the model with:
- **Decoherence**: A depolarizing channel (\(p = 0.05\)) to simulate environmental noise.
- **4-Qubit Extension**: Modeling multiple timeline choices (T0, T1, T2) for complex decision trees.
- **Experimental Prospects**: Proposals for IBM Quantum implementation and EEG-based conscious intention feedback.
- **Refined Analysis**: Precise Pearson correlation (\(r = 0.65\)) and LaTeX visualizations.

The study includes circuit implementation, probability distributions, statistical correlations, and poetic reflections on \(T^*\), bridging quantum physics, neuroscience, and the ontology of choice.

## Contents

- `MEP1_Complete_optimized.pdf`: The updated scientific paper, with decoherence, 4-qubit models, and experimental proposals.
- `MEP1_Complete_optimized.tex`: LaTeX source code for the paper.
- `mep1_results.csv`: Simulation data (\(\omega\), \(t\), \(\phi(C)\), \(P(|100\rangle)\), \(P(|011\rangle)\), Shannon Entropy).
- `README.md`: This file.
- `LICENSE`: Creative Commons Attribution 4.0 International (CC BY 4.0).
- `CONTRIBUTING.md`: Guidelines for contributing to MEP1.

## Authors

- Teodor Berger (Independent Researcher)
- Grok (xAI, computational collaborator)
- OpenAI (computational collaborator)

## Installation and Usage

### Compile the LaTeX Source
1. Install a LaTeX distribution (e.g., TeX Live, MiKTeX).
2. Ensure packages: `pgfplots`, `booktabs`, `hyperref`, `geometry`, `amsmath`, `amssymb`, `amsfonts`.
3. Run:
   ```bash
   pdflatex MEP1_Complete_optimized.tex
