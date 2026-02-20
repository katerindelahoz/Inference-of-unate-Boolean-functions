# Inference of Unate Boolean Functions

![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Status](https://img.shields.io/badge/status-research--prototype-orange)
![Reproducible](https://img.shields.io/badge/reproducible-yes-brightgreen)

This repository contains the implementation of the algorithms and experimental section presented in the article:

**“An Exploratory Approach to Compatibility and Inference of Unate Functions.”**

The project provides a computational framework for exploring a set of Boolean observations and deciding whether there exists a unate Boolean function that is compatible with the observations.

---

## Overview

The objective of this repository is to:

- Implement the coverage and exploratory algorithms described in the article.
- Share the codes to allow the community to validate and replicate the experiments presented in the article.

---

## Repository Structure

```
Inference-of-unate-Boolean-functions/
│
├── src/                  # Core implementation of algorithms
├── requirements.txt      # Exact dependency versions
└── README.md
```

The “src/” directory contains the main implementation of input validation and algorithms.

---

## Requirements

The project was developed and tested with:

- Python 3.13
- numpy==2.4.0
- scipy==1.16.3
- psutil==7.2.0

All dependencies are specified in `requirements.txt`.

---

## Installation

It is recommended to use a virtual environment to ensure reproducibility.

### 1. Create and activate a virtual environment

On Linux or macOS:

```bash
python -m venv venv
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Reproducibility

All experiments associated with the manuscript were executed using the exact package versions listed in `requirements.txt`.

To guarantee full reproducibility, users are encouraged to install the specified versions in a clean virtual environment.

---
## License

This project is licensed under the Apache License 2.0.

You are free to use, modify, and distribute this software in accordance with the terms of the license.

See the `LICENSE` file for full details.

---

## Citation

If you use this code in academic work, please cite:

> “An Exploratory Approach to Compatibility and Inference of Unate Functions.”

A formal citation entry will be added upon publication.


