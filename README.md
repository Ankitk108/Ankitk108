<h1 align="center">
  Hi, I'm Ankit <img src="./assets/waving-hand.svg" width="38" alt="Waving hand" />
</h1>

<p align="center">
  <strong>Quantum-assisted scientific machine learning · Computational physics · Scientific visualization</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&center=true&vCenter=true&width=700&lines=Physics+%7C+Quantum+Computing+%7C+Machine+Learning;Quantum+Machine+Learning+%7C+Scientific+Computing;Building+interactive+tools+for+understanding+physics;Researching+where+physics+meets+computation" alt="Physics, quantum computing, machine learning, and scientific computing" />
</p>

<p align="center">
  <img src="./assets/quantum-banner.svg" width="100%" alt="Animated quantum wave connecting physics, computation, and intuition" />
</p>

<p align="center">
  <i>I build computational experiments that make difficult physics observable—and report what they reveal, even when the result is negative.</i>
</p>

<p align="center">
  <a href="mailto:ankitkash2002@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email Ankit" /></a>
  <a href="https://www.linkedin.com/in/ankit-kashyap-368a78257"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Ankit on LinkedIn" /></a>
  <a href="https://github.com/Ankitk108?tab=followers"><img src="https://img.shields.io/github/followers/Ankitk108?label=Follow&style=flat-square&logo=github" alt="Follow Ankit on GitHub" /></a>
</p>

I'm a physics master's student at **IISER Mohali**. My work focuses on a practical question: how can computation help us test, visualize, and understand physical systems that resist simple intuition?

## Featured Research: QAPINN-CFD

**[QAPINN-CFD](https://github.com/Ankitk108/qapinn-cfd)** is a controlled, multi-seed comparison of classical physics-informed neural networks and quantum-assisted PINNs for the viscous Burgers equation.

| Model | Mean relative L2 | Mean training time | Trainable parameters |
| --- | ---: | ---: | ---: |
| Classical PINN | **0.0214** | **791 s** | 50,049 |
| QAPINN · 4 qubits · depth 2 | 0.4769 | 4,237 s | **41** |
| QAPINN · 4 qubits · depth 4 | 0.4376 | 7,629 s | **65** |

**Finding:** the hybrid models achieved dramatic parameter reduction, but not better accuracy or wall-clock performance on PennyLane's analytic simulator. Greater circuit depth modestly improved hybrid accuracy while increasing runtime and memory. The evidence supports parameter efficiency—not quantum advantage.

<p align="center">
  <a href="https://github.com/Ankitk108/qapinn-cfd/blob/master/report/final_report.md"><strong>Read the report</strong></a>
  ·
  <a href="https://github.com/Ankitk108/qapinn-cfd"><strong>Explore the code</strong></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ankitk108/qapinn-cfd/master/results/plots/burgers/loss_curves.png" width="820" alt="Training-loss comparison for classical PINN and QAPINN configurations" />
</p>

The framework uses matched sampling and loss definitions, end-to-end second-order automatic differentiation, fixed seeds, configuration-locked runs, diagnostic plots, and explicit accuracy gates. Failed or incomplete configurations remain visible rather than being filtered out after evaluation.

## Selected Computational Work

### Real-Space Topological Invariants

**[Real-Space Topological Invariants Visualization Suite](https://github.com/Ankitk108/real-space-topology-suite)** computes the Bott index and spectral localizer for finite topological systems without relying on momentum-space or Bloch-wave methods. It is designed for disorder, open boundaries, and broken translational symmetry.

[**Source code →**](https://github.com/Ankitk108/real-space-topology-suite) · [**Interactive demo →**](https://ankitk108.github.io/real-space-topology-suite/)

### Interactive Physics Tools

| Project | What becomes observable | Try it |
| --- | --- | --- |
| [Quantum State Visualizer](https://github.com/Ankitk108/Quantum-State-Visualizer) | Qubit states, gates, amplitudes, probabilities, and Bloch-sphere geometry | [Live demo](https://ankitk108.github.io/Quantum-State-Visualizer/) |
| [Quantum Channel Visualization](https://github.com/Ankitk108/Quantum-Channel-Visualization) | How bit-flip, phase-flip, and depolarizing noise deform the Bloch sphere | [Live demo](https://ankitk108.github.io/Quantum-Channel-Visualization/) |
| [Vicsek Model Simulation](https://github.com/Ankitk108/Vicsek-Model-Simulation) | Collective motion and noise-driven ordering in active-particle systems | [Live demo](https://ankitk108.github.io/Vicsek-Model-Simulation/) |

### Community Software

**[VectorHue](https://github.com/Ankitk108/VectorHue)** is a browser-based design utility for IISER Mohali student clubs. It provides structure-aware asset editing, reusable presets, and high-resolution transparent exports. [Try the live app →](https://ankitk108.github.io/VectorHue/)

## Technical Focus

| Area | Tools | Applied to |
| --- | --- | --- |
| **Scientific ML & quantum** | Python, PyTorch, NumPy, SciPy, PennyLane, Qiskit | PINNs, PDEs, variational circuits, automatic differentiation, numerical experiments |
| **Scientific visualization** | JavaScript, Three.js, Plotly.js, Canvas, HTML/CSS | Interactive quantum, topology, and collective-dynamics tools |
| **Reproducible research** | Git, Linux, Jupyter, pytest, YAML | Multi-seed studies, configuration-locked runs, validation, and traceable results |

## Beyond the Code

- 🥇 **1st place, Bets & Bytes — Insomnia'24 Hackathon**, building autonomous poker bots
- 🌐 **Lead Developer and former Convener, Curie Club at IISER Mohali**, developing its website and automating event and attendance workflows

## Public Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ankitk108&theme=tokyonight" alt="Ankit's public GitHub contribution activity" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ankitk108/Ankitk108/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ankitk108/Ankitk108/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/Ankitk108/Ankitk108/output/github-contribution-grid-snake.svg" alt="Animated snake moving through Ankit's public GitHub contribution grid" />
</picture>

## Contact

I welcome conversations about quantum computing, scientific machine learning, computational physics, and research software. **[Email me](mailto:ankitkash2002@gmail.com)** or connect with me on **[LinkedIn](https://www.linkedin.com/in/ankit-kashyap-368a78257)**.
