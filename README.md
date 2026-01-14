
Overleaf View Mode of paper: https://www.overleaf.com/read/xgghcyzgbrbv#368c5b



ABSTRACT

Variational Quantum Algorithms are a vital part of quantum computing. It is a blend of quantum and classical methods for tackling tough problems in machine learning, chemistry, and combinatorial optimization. Yet as these algorithms scale up, they cannot overcome the barren-plateau phenomenon. As systems grow, gradients can vanish so quickly that training deep or randomly initialized circuits becomes nearly impossible. 
To overcome the barren plateau problem, we introduce a \textcolor{red}{two-stage optimization framework}. First comes the convex initialization stage. Here, we shape the quantum energy landscape,  the Hilmaton landscape, into a smooth, low-energy basin. This step makes gradients easier to spot and keeps noise from derailing the process. Once we have gotten a stable gradient flow, we move to the second stage: nonconvex refinement. In this phase, we  let the algorithm wander through different energy minima, making the model more expressive.  Finally, we used our  two-stage solution to perform quantum cryptanalysis of quantum key distribution protocol(i.e., BB84) to determine the optimal cloning strategies. The simulation results showed that our proposed two-stage solution outperforms its random initialization counterpart.



Reference

Puig, Ricard, et al. "Variational quantum simulation: a case study for understanding warm starts." PRX Quantum 6.1 (2025): 010317.

Skolik, Andrea, et al. "Layerwise learning for quantum neural networks." Quantum Machine Intelligence 3.1 (2021): 5.

Sellier, Jean Michel, and Alexandre Martini. "On Training Spiking Neural Networks by Means of a Novel Quantum Inspired Machine Learning Method." Applied AI Letters 6.2 (2025): e114.

Coyle, Brian et al. “Variational Quantum Cloning: Improving Practicality for Quantum Cryptanalysis.” ArXiv abs/2012.11424 (2020): n. pag.

Sellier JM. On a quantum inspired approach to train machine learning models. Applied AI Letters. 2023 Dec;4(4):e89.

Cerezo et al., “Cost function-dependent barren plateaus in shallow parametrized quantum circuits,” Nat. Commun. (2021).

McClean et al., “Barren plateaus in quantum neural network training landscapes,” Nat. Commun. (2018).

Holmes et al., “Connecting expressibility to trainability in quantum machine learning,” PRL (2022).

Stęchły, Michał. "Introduction to variational quantum algorithms." arXiv preprint arXiv:2402.15879 (2024).

Du, Yuxuan, et al. "Quantum machine learning: A hands-on tutorial for machine learning practitioners and researchers." arXiv preprint arXiv:2502.01146 (2025).

Chen, Samuel Yen-Chi et al. “Variational Quantum Circuits for Deep Reinforcement Learning.” IEEE Access 8 (2019): 141007-141024.

**pip install Qiskit**
**pip install pennyLane**










