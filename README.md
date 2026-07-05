# Biodiversity Analysis Toolkit

[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.123456.svg)](https://doi.org/10.5072/zenodo.123456)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

Analysis tools for biodiversity research data. This project demonstrates reproducible research software workflows.

> **Note:** This is a teaching/demo repository. The DOI above points to Zenodo Sandbox for demonstration purposes.

## Features

- **Citable**: Includes CITATION.cff and a DOI via Zenodo
- **Open Source**: Licensed under BSD 3-Clause
- **Documented**: README, contributing guide, and code of conduct

## Getting Started

### Prerequisites

- Python 3.9+

### Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/UC-OSPO-Network/software-demo.git
   cd software-demo
   ```

2. Install dependencies and run the analysis:
   ```bash
   pip install -r requirements.txt
   python src/analysis.py
   ```

> Want a fully reproducible, cross-platform environment (Python + R with a lockfile)?
> See the optional pixi setup on the `optional-pixi` branch.

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Code of Conduct

Please read and abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Citation

If you use this software, please cite it using the metadata in [CITATION.cff](CITATION.cff) or via the DOI badge above.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## Authors

- Tim Dennis (UCLA)
- Leigh Phan (UCLA)
- Reid Otsuji (UCSD)
- Karla Padilla (UCSD)

## Contact

For questions or feedback, please open an issue in this repository.

## Reproducible environment (pixi)

This branch adds a [pixi](https://pixi.sh) environment so the project runs identically
across machines (Python and R, pinned by a lockfile):

```bash
pixi install
pixi run python src/analysis.py
```
