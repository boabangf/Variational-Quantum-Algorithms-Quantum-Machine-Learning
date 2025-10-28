ABSTRACT

Variational Quantum Algorithms (VQAs) represent a cornerstone of near-term quantum computing, enabling hybrid quantum–classical optimization for high-dimensional learning, chemistry, and combinatorial problems. However, their scalability is severely constrained by the barren plateau phenomenon, a regime where gradients vanish exponentially with system size, preventing effective training of deep or randomly initialized circuits. In this work, we introduce a two-stage optimization framework designed to overcome barren plateaus and improve convergence stability in quantum and quantum-inspired models. The proposed method begins with a convex initialization stage, which shapes the quantum energy manifold (Hilmaton landscape) into a smooth, low-energy basin to enhance gradient visibility and suppress noise-induced instability. Once stable gradient flow is established, the algorithm transitions to a nonconvex refinement stage that introduces structured oscillatory regularization, enabling exploration of multiple energy minima and improving model expressivity. This staged approach emulates the physical evolution of quantum systems from ordered to interference-rich states, providing a principled pathway to maintain gradient information throughout training. Numerical experiments  demonstrate that the framework mitigates gradient vanishing, enhances optimization stability, and preserves generalization performance across varying circuit depths. The results highlight a scalable route toward trainable variational quantum architectures resilient to barren plateau effects. 
















Reference


Sellier JM. On a quantum inspired approach to train machine learning models. Applied AI Letters. 2023 Dec;4(4):e89.

Cerezo et al., “Cost function-dependent barren plateaus in shallow parametrized quantum circuits,” Nat. Commun. (2021).

McClean et al., “Barren plateaus in quantum neural network training landscapes,” Nat. Commun. (2018).

Holmes et al., “Connecting expressibility to trainability in quantum machine learning,” PRL (2022).

Stęchły, Michał. "Introduction to variational quantum algorithms." arXiv preprint arXiv:2402.15879 (2024).


