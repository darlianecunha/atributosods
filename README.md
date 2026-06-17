# SDG Attributes — A Sustainability Index for Brazilian Ports

[![Software DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20708458-blue)](https://doi.org/10.5281/zenodo.20708458)
[![Paper DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.marpol.2025.106841-blue)](https://doi.org/10.1016/j.marpol.2025.106841)
[![Journal](https://img.shields.io/badge/Marine%20Policy-Vol.%20181%20(2025)-green)](https://www.sciencedirect.com/science/article/abs/pii/S0308597X2500257X)
[![Live App](https://img.shields.io/badge/Live-sdgports.manus.space-orange)](https://sdgports.manus.space)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)

An interactive web tool that implements the sustainability assessment framework published in *Marine Policy* (2025). The model evaluates how well Brazilian ports align with the UN Sustainable Development Goals through 84 measurable indicators organised in 20 thematic dimensions.

**Live demo:** [sdgports.manus.space](https://sdgports.manus.space)

<!-- Keep your existing screenshot here, or add one at docs/screenshot.png:
![SDG Attributes — screenshot](docs/screenshot.png)
-->

## About the Research

This framework was developed as part of a postdoctoral research project at Erasmus University Rotterdam and the Federal University of Maranhão (UFMA). We applied it to six major Brazilian ports that together handle about 30% of the country's cargo throughput.

The full methodology, validation process, and results are described in the published article:

> Cunha, D. R., Costa, M. D. C., Oliveira, C. B. M., & Pereira, N. N. (2025). SDG attributes: A sustainability assessment framework for Brazilian ports. *Marine Policy*, 181, 106841. https://doi.org/10.1016/j.marpol.2025.106841

## How the Model Works

Each port is scored across 84 indicators on a 0–3 scale:

| Score | Meaning |
| ----- | ------- |
| 0 | No evidence of action |
| 1 | Initial actions (pilot stage, not yet integrated) |
| 2 | Consolidated measures (operationally integrated) |
| 3 | Best practices (systematic implementation, international benchmarks) |

Maximum possible score: **252 points** (84 indicators × 3 points each).

## SDGs Covered

The framework spans 8 SDGs with the following structure:

| SDG | Theme | Indicators | Max Score |
| --- | ----- | ---------- | --------- |
| SDG 7 | Affordable and Clean Energy | 14 | 42 |
| SDG 8 | Decent Work and Economic Growth | 17 | 51 |
| SDG 9 | Industry, Innovation and Infrastructure | 12 | 36 |
| SDG 11 | Sustainable Cities and Communities | 7 | 21 |
| SDG 12 | Responsible Consumption and Production | 8 | 24 |
| SDG 13 | Climate Action | 8 | 24 |
| SDG 14 | Life Below Water | 8 | 24 |
| SDG 17 | Partnerships for the Goals | 10 | 30 |

## Features

**Indicators Reference** — Browse all 84 indicators grouped by SDG and thematic dimension, with scoring criteria for each level.

**Simulation Tool** — Select scores for each indicator and get an overall sustainability assessment with visual breakdowns by SDG.

## Tech Stack

- HTML/CSS/JavaScript
- React-based interactive components
- Hosted on the Manus platform

## Repository Structure

```
atributosods/
  index.html    # Complete single-page application
```

## Related Projects

- [co2-liquid-bulk-calculator](https://github.com/darlianecunha/co2-liquid-bulk-calculator) — Emissions calculator for liquid bulk vessels
- [maritimeco2](https://github.com/darlianecunha/maritimeco2) — OPS-avoidable at-berth CO₂ for liquid bulk vessels
- [vessel-explorer](https://github.com/darlianecunha/vessel-explorer) — Explorer of EU MRV vessel emissions data

## Citation

If you use this framework in your research, please cite:

```bibtex
@article{cunha2025sdg,
  title   = {SDG attributes: A sustainability assessment framework for Brazilian ports},
  author  = {Cunha, Darliane Ribeiro and Costa, Markus Dannyllo Carneiro and Oliveira, Cl{\'o}vis B{\'o}sco Mendon{\c{c}}a and Pereira, Newton Narciso},
  journal = {Marine Policy},
  volume  = {181},
  pages   = {106841},
  year    = {2025},
  publisher = {Elsevier},
  doi     = {10.1016/j.marpol.2025.106841}
}
```

## Author

**Darliane Ribeiro Cunha, PhD** — Full Professor, Federal University of Maranhão (UFMA)
Postdoctoral Researcher, Erasmus University Rotterdam (2024–2025)

- [Personal website](https://www.darlianecunha.com)
- [ORCID: 0000-0003-2548-1237](https://orcid.org/0000-0003-2548-1237)
- [LinkedIn](https://linkedin.com/in/darlianecunha)

## Licence

This project is licensed under the MIT Licence — see [LICENSE](LICENSE).
