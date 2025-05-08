# Scenario Generation

This repository contains an **implementation of the paper**:  
"[Generating Scenarios for Complex Systems](https://proceedings.neurips.cc/paper_files/paper/2023/file/d95cb79a3421e6d9b6c9a9008c4d07c5-Paper-Conference.pdf)"  
presented at NeurIPS 2023.

The project focuses on reproducing and extending the techniques described in the paper to simulate and analyze scenarios for complex systems. Using Jupyter Notebooks, this repository provides an interactive and modular framework for experimentation.

## Table of Contents

- [Overview](#overview)
- [Paper Summary](#paper-summary)
- [Features](#features)
- [Data Source](#data-source)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project implements the methods described in the NeurIPS 2023 paper *"Generating Scenarios for Complex Systems"*. The implementation enables users to:

- Reproduce the experiments and results presented in the paper.
- Explore extensions and customizations of the proposed methods.
- Analyze generated scenarios visually and interactively using Jupyter Notebooks.

## Paper Summary

The referenced paper introduces a novel approach to generating scenarios for complex systems by leveraging advanced modeling techniques. Key contributions include:

- A robust framework for scenario generation.
- Methods to ensure diversity and plausibility in generated scenarios.
- Applications in simulation, testing, and decision-making processes.

For more details, see the full paper [here](https://proceedings.neurips.cc/paper_files/paper/2023/file/d95cb79a3421e6d9b6c9a9008c4d07c5-Paper-Conference.pdf).

## Features

- 📘 **Reproducible Implementation**: Step-by-step replication of the NeurIPS 2023 paper's results.
- ⚡ **Modular Design**: Easily adapt and extend the methods for new use cases.
- 📊 **Interactive Visualization**: Analyze scenarios directly within Jupyter Notebooks.
- 🧪 **Experimentation Ready**: Tools to experiment with variations and custom scenarios.

## Data Source

The data used in this project can be found at the [Argoverse Motion Forecasting Dataset](https://argoverse.github.io/user-guide/datasets/motion_forecasting.html). This dataset provides high-quality motion forecasting data that is critical for generating and testing scenarios.

## Getting Started

To get started with this repository:

1. Clone the repository:
   ```bash
   git clone https://github.com/marceauPailhas/scenario_generation.git
   cd scenario_generation
   ```

2. Install dependencies (see [Installation](#installation)).

3. Explore the provided Jupyter Notebooks to reproduce the paper's experiments or create custom scenarios.

## Installation

This project requires Python and Jupyter Notebook. Follow these steps to set up your environment:

1. Install Python (version 3.8 or later is recommended).
2. Install Jupyter Notebook:
   ```bash
   pip install notebook
   ```
3. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

4. Install project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open one of the provided notebooks (e.g., `scenario_generation.ipynb`).

3. Follow the notebook instructions to reproduce experiments or generate custom scenarios.

4. Modify and extend the code to explore new ideas and applications.

## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your feature or fix description"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the authors of the paper *"Generating Scenarios for Complex Systems"* for their groundbreaking work, and to the Argoverse team for providing the [motion forecasting dataset](https://argoverse.github.io/user-guide/datasets/motion_forecasting.html). 
