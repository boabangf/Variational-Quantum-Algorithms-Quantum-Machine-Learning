
Overleaf View Mode of paper: https://www.overleaf.com/read/xgghcyzgbrbv#368c5b

Chakraborty, Shantanav, Aditya Morolia, and Anurudh Peduri. "Quantum regularized least squares." Quantum 7 (2023): 988.

Du, Yuxuan, et al. "A grover-search based quantum learning scheme for classification." new Journal of Physics 23.2 (2021): 023020.

Coyle, Brian et al. “Variational Quantum Cloning: Improving Practicality for Quantum Cryptanalysis.” ArXiv abs/2012.11424 (2020): n. pag.



QIML-based intrusion / anomaly detection for PQC transitions

Quantum-inspired kernel learning for malware / traffic classification

QIML for adaptive PQC parameter and policy selection


Under construction: https://colab.research.google.com/drive/1eAFJnlj84ypAcmPcmxo8pQa3J_GioeVI?usp=sharing

DataSets

load_wine

Mnist

OptdigitsData

**Quantum Pipeline**

Train PQC-3 surrogate with regularized LS (convex)

Obtain stable parameter basin

Promote to PQC-3 (cubic interactions)

Fine-tune with full nonlinear expressivity

**This avoids:**

Barren plateaus (quantum)

Vanishing gradients (deep learning)

Parameter Scaling in PQC-1 and PQC-3



ABSTRACT

Variational Quantum Algorithms (VQAs) represent a cornerstone of near-term quantum computing, enabling hybrid quantum–classical optimization for high-dimensional learning, chemistry, and combinatorial problems. However, their scalability is severely constrained by the barren plateau phenomenon, a regime where gradients vanish exponentially with system size, preventing effective training of deep or randomly initialized circuits. In this work, we introduce a two-stage optimization framework designed to overcome barren plateaus and improve convergence stability in quantum and quantum-inspired models. The proposed method begins with a convex initialization stage, which shapes the quantum energy manifold (Hilmaton landscape) into a smooth, low-energy basin to enhance gradient visibility and suppress noise-induced instability. Once stable gradient flow is established, the algorithm transitions to a nonconvex refinement stage that introduces structured oscillatory regularization, enabling exploration of multiple energy minima and improving model expressivity. This staged approach emulates the physical evolution of quantum systems from ordered to interference-rich states, providing a principled pathway to maintain gradient information throughout training. Numerical experiments  demonstrate that the framework mitigates gradient vanishing, enhances optimization stability, and preserves generalization performance across varying circuit depths. The results highlight a scalable route toward trainable variational quantum architectures resilient to barren plateau effects. 







Reference
Puig, Ricard, et al. "Variational quantum simulation: a case study for understanding warm starts." PRX Quantum 6.1 (2025): 010317.

Skolik, Andrea, et al. "Layerwise learning for quantum neural networks." Quantum Machine Intelligence 3.1 (2021): 5.

Sellier, Jean Michel, and Alexandre Martini. "On Training Spiking Neural Networks by Means of a Novel Quantum Inspired Machine Learning Method." Applied AI Letters 6.2 (2025): e114.

Sellier JM. On a quantum inspired approach to train machine learning models. Applied AI Letters. 2023 Dec;4(4):e89.

Cerezo et al., “Cost function-dependent barren plateaus in shallow parametrized quantum circuits,” Nat. Commun. (2021).

McClean et al., “Barren plateaus in quantum neural network training landscapes,” Nat. Commun. (2018).

Holmes et al., “Connecting expressibility to trainability in quantum machine learning,” PRL (2022).

Stęchły, Michał. "Introduction to variational quantum algorithms." arXiv preprint arXiv:2402.15879 (2024).

Du, Yuxuan, et al. "Quantum machine learning: A hands-on tutorial for machine learning practitioners and researchers." arXiv preprint arXiv:2502.01146 (2025).

Chen, Samuel Yen-Chi et al. “Variational Quantum Circuits for Deep Reinforcement Learning.” IEEE Access 8 (2019): 141007-141024.


**Telecommunication Applications Reference**

**pip install Qiskit**










