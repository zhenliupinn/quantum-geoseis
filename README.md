# quantum-geoseis

**quantum-geoseis** is an open-source platform for quantum intelligence in seismic inversion and geophysical data science, based on [Qiskit](https://qiskit.org/) and licensed under Apache 2.0.

This platform is designed to accelerate the integration of quantum machine learning with geophysical inversion, supporting reproducible research, benchmarking, and community-driven innovation.

This repository provides core codes, tutorials, and benchmarks from:

**"Application of Quantum Neural Networks and Variational Quantum Regression in Seismic Inversion"**  
Zhen Liu\*, Junhua Zhang. China University of Petroleum (East China)

📄 **[Download the paper (PDF)](https://imageevent.aapg.org/portals/26/abstracts/2025/4301526.pdf)**  
*(Presented at IMAGE 2025 Conference, Houston, US)*  
*Supported by the SEG (Society of Exploration Geophysicists) Travel Grant. Grateful thanks to SEG!*

---

## Overview

`quantum-geoseis` provides a unified platform for:

- **Quantum Neural Networks (QNN):** Variational quantum circuits for regression, classification, and geophysical data modeling.
- **Variational Quantum Regression (VQR):** Specialized quantum regression pipelines for seismic inversion.
- **Hybrid & Modular Workflows:** Easily integrate quantum-classical hybrid algorithms and extend to new geophysical applications.
- **IBM Quantum Hardware Support:** All circuits can be executed on real IBM Quantum devices (tested on IBM Quantum Kyiv, Brisbane, Sherbrooke, and more).

⚠️ **Warning:** Please ensure your IBM Quantum account has enough compute time credits; otherwise, premium access may cost up to **$96 USD per minute**.

---

## Platform Features

- **Extensible Modules:** Easily add new quantum models, geophysical workflows, or benchmarks.
- **Community-driven:** Contributions, issues, and collaborative development are highly encouraged.
- **Reproducible Experiments:** All main results can be reproduced using our provided notebooks and datasets.
- **Benchmarks:** Standardized seismic inversion tasks based on normalized Marmousi2 synthetic data.

---

## Main Findings

- QNN achieves rapid and stable convergence, effectively fitting training data and demonstrating some generalization on test sets.
- VQR displays a more complex convergence process, with initial fluctuations but good overall accuracy.
- Both models show that quantum intelligence can be applied to seismic inversion and have potential for more efficient subsurface imaging as quantum hardware matures.

---

## Getting Started

This repository is under active development.  
Core code, tutorials, and experimental notebooks will be released soon!

**Requirements (planned):**
- Python >= 3.12
- Qiskit >= 1.3.1
- qiskit-machine-learning >= 0.8.2

See `docs/` for user guides, API documentation, and contribution instructions (coming soon).

---

## License

This project is licensed under the Apache License 2.0.  
See [LICENSE](./LICENSE) for details.  
The code builds upon Qiskit, which is © IBM 2017–2025, Apache 2.0.

---

## Citation

If you use this platform or reference the results, please cite:  
`Zhen Liu, Junhua Zhang. Application of Quantum Neural Networks and Variational Quantum Regression in Seismic Inversion. IMAGE 2025 Conference, 2025, Houston, US. https://imageevent.aapg.org/portals/26/abstracts/2025/4301526.pdf`

**BibTeX:**
```bibtex
@inproceedings{liu2025qnn-vqr-seismic,
  author    = {Zhen Liu and Junhua Zhang},
  title     = {Application of Quantum Neural Networks and Variational Quantum Regression in Seismic Inversion},
  booktitle = {IMAGE 2025 Conference},
  year      = {2025},
  address   = {Houston, US},
  url       = {https://imageevent.aapg.org/portals/26/abstracts/2025/4301526.pdf}
}
```

## Community & Contribution

We welcome issues, feature requests, pull requests, and discussions!
See CONTRIBUTING.md (coming soon) for guidelines, or open an issue to start a conversation.

## Pioneering the next generation of quantum geophysical intelligence — join us!

**This platform is under active development. Stay tuned!**
