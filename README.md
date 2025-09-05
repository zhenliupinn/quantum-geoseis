# quantum-geoseis
**quantum-geoseis** is an open-source research platform for quantum intelligence in seismic inversion and reservoir characterization, based on [Qiskit](https://qiskit.org/) and licensed under Apache 2.0.

This repository provides code and experiments from the study:
**"Application of Quantum Neural Networks and Variational Quantum Regression in Seismic Inversion"**  
Zhen Liu\*, Junhua Zhang. China University of Petroleum (East China)

📄 **[Download the paper (PDF)](https://imageevent.aapg.org/portals/26/abstracts/2025/4301526.pdf)**  
*(Presented at IMAGE 2025 Conference, Houston, US)*

## Citation
If you use this code or reference the results, please cite:  
"Zhen Liu, Junhua Zhang. Application of Quantum Neural Networks and Variational Quantum Regression in Seismic Inversion. IMAGE 2025 Conference, 2025, Houston, US. https://imageevent.aapg.org/portals/26/abstracts/2025/4301526.pdf"

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

## Overview
This project explores the application of Quantum Neural Networks (QNN) and Variational Quantum Regression (VQR) in seismic inversion, leveraging quantum computing’s advantages in superposition, entanglement, and interference.
QNN utilizes parameterized quantum circuits to capture complex relationships in seismic data, while VQR targets regression tasks with quantum-enhanced modeling.

* Experiments are implemented via Qiskit on classical simulators and are successfully executed on IBM Quantum hardware (Kyiv, Brisbane, Sherbrooke, etc.).
* Both QNN and VQR are tested on synthetic seismic data from the Marmousi2 model.
* Results show strong data-fitting and promising generalization, demonstrating the feasibility of quantum intelligence for geophysical inversion.

## IBM Quantum Hardware Support
All core quantum circuits in this repository can be executed on real IBM Quantum devices (tested on IBM Quantum Kyiv, Brisbane, Sherbrooke, and more).
See the tutorials for practical instructions on running your seismic inversion tasks on IBM’s cloud-based quantum hardware.

**⚠️ Warning: Please ensure your account has enough compute time credits; otherwise, premium access may cost up to $96 USD per minute.**

## Key Features
* Quantum Neural Networks (QNN): Variational quantum circuits that emulate classical neural networks, adapted for regression and data modeling.
* Variational Quantum Regression (VQR): Quantum circuit architectures optimized for regression, with a focus on feature encoding and nonlinear mapping.
* Hybrid Training: Classical optimization algorithms (Adam, SPSA) for quantum circuit parameter tuning.
* Benchmarks: Real seismic inversion tasks using normalized Marmousi2 synthetic data as testbed.

## Main Findings
* QNN achieves rapid and stable convergence, effectively fitting training data and demonstrating some generalization on test sets.
* VQR displays a more complex convergence process, with initial fluctuations but good overall accuracy.
* Both models show that quantum intelligence can be applied to seismic inversion and have potential for more efficient subsurface imaging as quantum hardware matures.
## Getting Started
This repository is under active development.
Core code, tutorials, and experimental notebooks will be released soon!

**Requirements (planned):**
* Python >= 3.12
* Qiskit >= 1.3.1
* qiskit-machine-learning >= 0.8.2

## License
This project is licensed under the Apache License 2.0.
See LICENSE
 for details.
The code builds upon Qiskit, which is © IBM 2017–2025, Apache 2.0.

For questions, feedback, or collaboration, please open an issue or contact the maintainer.
