# MEP1: Quantum Temporal Entanglement and Conscious Resonance in the Grandfather Paradox

This repository contains the documentation and data for the Mental-Experimental Prototype 1 (MEP1), a study exploring quantum temporal entanglement to resolve the grandfather paradox. The preprint was submitted by Teodor Berger, with computational support from xAI and OpenAI.

## About

The grandfather paradox challenges causality in time travel scenarios. MEP1 proposes a resolution through a 3-qubit quantum circuit, modeling conscious intention as a phase \(\phi(C) = \pi \sin(\omega t)\). By simulating timeline bifurcation between the original (T0, \(|100\rangle\)) and alternate (T1, \(|011\rangle\)) timelines, MEP1 reveals a quantum heating mechanism driven by bioentanglement and vacuum fluctuations. The study includes circuit implementation, probability distributions, statistical correlations (Pearson \(r = 0.65\)), and LaTeX-generated visualizations.

The preprint is available on Zenodo: https://doi.org/10.5281/zenodo.15368835).

## Contents

- `MEP1_Complete.pdf`: The full scientific paper, including circuit design, analysis, and visualizations.
- `MEP1_Complete.tex`: LaTeX source code for the paper.
- `mep1_results.csv`: Simulation data (\(\omega\), \(t\), \(\phi(C)\), \(P(|100\rangle)\), \(P(|011\rangle)\), Shannon Entropy).
- `README.md`: This file.
- `LICENSE`: Creative Commons Attribution 4.0 International (CC BY 4.0).
- `CONTRIBUTING.md`: Guidelines for contributing to MEP1.

## Authors

- Teodor Berger (Independent Researcher)
- Grok (xAI, computational collaborator)
- OpenAI (computational collaborator)

## Installation and Usage

To compile the LaTeX source:
1. Install a LaTeX distribution (e.g., TeX Live, MiKTeX).
2. Ensure the `pgfplots`, `booktabs`, `hyperref`, and `geometry` packages are available.
3. Run `pdflatex MEP1_Complete.tex` to generate the PDF.

To analyze the data:
- Open `mep1_results.csv` in a spreadsheet tool (e.g., Excel, Google Sheets) or a programming environment (e.g., Python with pandas).

## License

This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See the `LICENSE` file for details.

## Contributing

We welcome contributions to extend MEP1, such as new simulations, experimental validations, or theoretical expansions. Please see `CONTRIBUTING.md` for guidelines.

## Citation

If you use this work, please cite:
