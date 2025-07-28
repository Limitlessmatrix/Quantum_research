# Quantum Computing Sources Collection

A comprehensive collection of sources for quantum computing research, with a focus on quantum algorithms for drug discovery and molecular simulation.

## Table of Contents
- [Foundational Books](#foundational-books)
- [Seminal Papers](#seminal-papers)
- [Core Quantum Algorithms](#core-quantum-algorithms)
- [Quantum Algorithm Theory](#quantum-algorithm-theory)
- [VQE and Optimization Algorithms](#vqe-and-optimization-algorithms)
- [QAOA Research](#qaoa-research)
- [NISQ Era and Error Mitigation](#nisq-era-and-error-mitigation)
- [Quantum Chemistry and Drug Discovery](#quantum-chemistry-and-drug-discovery)
- [Protein Folding Applications](#protein-folding-applications)
- [Hybrid Quantum-Classical Approaches](#hybrid-quantum-classical-approaches)
- [Quantum Machine Learning](#quantum-machine-learning)
- [Industry Applications](#industry-applications)
- [Benchmarking and Metrics](#benchmarking-and-metrics)
- [Review Articles and Surveys](#review-articles-and-surveys)
- [Educational Resources](#educational-resources)

---

## Foundational Books

1. **Quantum Computation and Quantum Information**
   - Authors: Michael A. Nielsen, Isaac L. Chuang
   - Year: 2010
   - Publisher: Cambridge University Press
   - Description: The foundational textbook covering nearly all aspects of quantum computing, including QFT, Shor's algorithm, and Grover's algorithm

---

## Seminal Papers

1. **Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer**
   - Author: Peter W. Shor
   - Year: 1994
   - Journal: SIAM Journal on Computing
   - URL: [arXiv:quant-ph/9508027](http://arxiv.org/pdf/quant-ph/9708016)
   - Description: The seminal paper introducing Shor's algorithm for integer factorization

2. **A fast quantum mechanical algorithm for database search**
   - Author: Lov K. Grover
   - Year: 1996
   - Journal: Proceedings of the 28th Annual ACM Symposium on Theory of Computing
   - Description: Original paper introducing Grover's algorithm and amplitude amplification

3. **A variational eigenvalue solver on a quantum processor**
   - Authors: Alberto Peruzzo, Jarrod McClean, Peter Shadbolt, et al.
   - Year: 2014
   - Journal: Nature Communications
   - Description: Introduced the Variational Quantum Eigensolver (VQE)

4. **A Quantum Approximate Optimization Algorithm**
   - Authors: Edward Farhi, Jeffrey Goldstone, Sam Gutmann
   - Year: 2014
   - URL: [arXiv:1411.4028](https://arxiv.org/abs/1411.4028)
   - Description: Proposed the Quantum Approximate Optimization Algorithm (QAOA)

---

## Core Quantum Algorithms

### Quantum Fourier Transform
1. **Quantum Fourier Transform - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Quantum_Fourier_transform

2. **Shor's Algorithm and the QFT**
   - URL: https://www.ryanlarose.com/uploads/1/1/5/8/115879647/shor2-qft.pdf

3. **Quantum Fourier Transform - Berkeley Course**
   - URL: https://courses.edx.org/c4x/BerkeleyX/CS191x/asset/chap5.pdf

4. **Why Does Shor's Algorithm Need a QFT?**
   - URL: https://benjaminwhiteside.com/2019/12/05/why-does-shors-algorithm-need-a-qft-part-i/

### Shor's Algorithm
1. **Shor's Algorithm - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Shor%27s_algorithm

### Grover's Algorithm and Amplitude Amplification
1. **Grover's Algorithm - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Grover%27s_algorithm

2. **Amplitude Amplification - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Amplitude_amplification

3. **Ultimate Guide to Amplitude Amplification**
   - URL: https://www.numberanalytics.com/blog/ultimate-guide-amplitude-amplification-quantum-algorithms

4. **Introduction to Amplitude Amplification - PennyLane**
   - URL: https://pennylane.ai/qml/demos/tutorial_intro_amplitude_amplification

5. **Grover's Algorithm Tutorial - Qiskit**
   - URL: https://qiskit-community.github.io/qiskit-algorithms/tutorials/06_grover.html

---

## Quantum Algorithm Theory

1. **Quantum Algorithms Overview**
   - URL: https://arxiv.org/html/2407.05178v1

2. **Quantum Algorithms - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Quantum_algorithm

3. **Quantum Computing and Quantum Algorithms**
   - URL: https://quantumalgorithms.org/quantum-computing-and-quantum-algorithms.html

4. **Quantum Complexity Theory - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Quantum_complexity_theory

5. **The Ultimate Guide to Quantum Algorithms**
   - URL: https://www.spinquanta.com/news-detail/the-ultimate-guide-to-quantum-algorithms

6. **Quantum Algorithms: A First Example**
   - URL: https://leftasexercise.com/2018/10/15/quantum-algorithms-a-first-example/

---

## VQE and Optimization Algorithms

### Variational Quantum Eigensolver (VQE)
1. **Variational Quantum Eigensolver - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Variational_quantum_eigensolver

2. **VQE Explained - MindSpore**
   - URL: https://www.mindspore.cn/mindquantum/docs/en/r0.6/vqe_for_quantum_chemistry.html

3. **VQE Guide - Number Analytics**
   - URL: https://www.numberanalytics.com/blog/variational-quantum-eigensolver-vqe-guide

4. **VQE for Quantum Chemistry**
   - URL: https://arxiv.org/pdf/2111.05176

5. **Chemical Applications of VQE**
   - URL: https://pubs.aip.org/aip/apr/article/12/3/031304/3351224/Chemical-applications-of-variational-quantum

### Specific VQE Applications
1. **Adaptive Variational Algorithm for Molecular Simulations**
   - URL: https://www.nature.com/articles/s41467-019-10988-2

2. **VQE with Reduced Circuit Complexity**
   - URL: https://www.nature.com/articles/s41534-022-00599-z

3. **Evaluating VQE Approaches**
   - URL: https://www.mdpi.com/1420-3049/30/1/119

4. **Ground State Calculations Using IBM Qiskit**
   - URL: https://pubs.aip.org/aip/adv/article/14/3/035047/3278854/

---

## QAOA Research

1. **Quantum Approximate Optimization Algorithm Review**
   - URL: https://www.researchgate.net/publication/371605386_A_Review_on_Quantum_Approximate_Optimization_Algorithm_and_its_Variants

2. **QAOA Performance Analysis**
   - URL: https://arxiv.org/pdf/2405.00781

3. **QAOA Can Require Exponential Time**
   - URL: https://www.researchgate.net/publication/391677130_The_Quantum_Approximate_Optimization_Algorithm_Can_Require_Exponential_Time_to_Optimize_Linear_Functions

4. **QAOA with Quantum Error Detection**
   - URL: https://www.researchgate.net/publication/384115567_Performance_of_Quantum_Approximate_Optimization_with_Quantum_Error_Detection

---

## NISQ Era and Error Mitigation

1. **NISQ Era Challenges**
   - URL: https://dev.to/vaib/unlocking-quantum-machine-learning-tackling-noise-in-the-nisq-era-3gc1

2. **NISQ is Dead - Critical Analysis**
   - URL: https://jackkrupansky.medium.com/nisq-is-dead-a-dying-dead-end-with-no-prospects-for-a-brighter-future-or-practical-quantum-5933d37fa1b6

3. **Error Mitigation in the NISQ Era**
   - URL: https://www.mdpi.com/2227-7390/12/14/2235

4. **Error-Mitigated Quantum Simulation**
   - URL: https://www.nature.com/articles/s41534-023-00784-8

5. **Pushing NISQ Boundaries**
   - URL: https://communities.springernature.com/posts/pushing-the-boundaries-of-nisq-with-error-mitigation

6. **Decoherence in Quantum Computing**
   - URL: https://www.spinquanta.com/news-detail/decoherence-in-quantum-computing-everything-you-need-to-know

---

## Quantum Chemistry and Drug Discovery

### Core Molecular Simulation Papers
1. **Molecular Electronic Structure Calculation via Quantum Computer**
   - URL: https://arxiv.org/html/2303.09911v4

2. **Quantum Algorithms for Quantum Molecular Systems: A Survey**
   - URL: https://wires.onlinelibrary.wiley.com/doi/full/10.1002/wcms.70020

3. **Qubit-Efficient Encoding for Quantum Simulations**
   - URLs: 
     - https://link.aps.org/doi/10.1103/PhysRevResearch.4.023154
     - https://arxiv.org/abs/2110.04112

### Drug Discovery Applications
1. **Quantum Computing Makes Waves in Drug Discovery**
   - URL: https://www.stjude.org/research/progress/2025/quantum-computing-makes-waves-in-drug-discovery.html

2. **How Quantum Computing is Changing Drug Development**
   - URL: https://www.weforum.org/stories/2025/01/quantum-computing-drug-development/

3. **Quantum Computing's Potential for Drug Discovery**
   - URL: https://www.sciencedirect.com/science/article/abs/pii/S1359644621002750

4. **Quantum-Machine-Assisted Drug Discovery**
   - URL: https://arxiv.org/html/2408.13479v2

5. **Advancing Drug Discovery with Quantum Computing**
   - URL: https://nhsjs.com/2025/advancing-drug-discovery-with-quantum-computing-breaking-artificial-intelligence-barriers/

---

## Protein Folding Applications

1. **Resource-Efficient Quantum Algorithm for Protein Folding**
   - URLs:
     - https://www.nature.com/articles/s41534-021-00368-4
     - https://arxiv.org/abs/1908.02163

2. **Quantum Computing Solves Complex Protein Folding**
   - URL: https://quantumzeitgeist.com/quantum-computing-solves-complex-protein-folding-and-optimisation-problems/

3. **Perspective on Protein Structure Prediction Using Quantum Computers**
   - URLs:
     - https://pubs.acs.org/doi/10.1021/acs.jctc.4c00067
     - https://pmc.ncbi.nlm.nih.gov/articles/PMC11099973/

---

## Hybrid Quantum-Classical Approaches

1. **Microsoft and Quantinuum Create 12 Logical Qubits**
   - URL: https://azure.microsoft.com/en-us/blog/quantum/2024/09/10/microsoft-and-quantinuum-create-12-logical-qubits-and-demonstrate-a-hybrid-end-to-end-chemistry-simulation/

2. **Hybrid Quantum-Classical Computing for Chemical Systems**
   - URL: https://www.admissions.caltech.edu/explore-more/news/new-hybrid-quantumclassical-computing-approach-used-to-study-chemical-systems

3. **Hybrid Quantum Algorithms for Monte Carlo**
   - URL: https://research.google/blog/hybrid-quantum-algorithms-for-quantum-monte-carlo/

4. **Hybrid Quantum Computing Pipeline for Drug Discovery**
   - URL: https://www.nature.com/articles/s41598-024-67897-8

5. **End-to-End Quantum Algorithm Construction**
   - URL: https://aws.amazon.com/blogs/quantum-computing/constructing-end-to-end-quantum-algorithm/

---

## Quantum Machine Learning

1. **Machine Learning in QM/MM Molecular Dynamics**
   - URLs:
     - https://pubs.acs.org/doi/10.1021/acs.jctc.0c01112
     - https://pubmed.ncbi.nlm.nih.gov/33818085/

2. **Hybrid Quantum-Classical Optimization for Deep Learning**
   - URL: https://www.researchgate.net/post/Can_hybrid_quantum-classical_optimization_techniques_significantly_accelerate_deep_neural_network_training_in_high-dimensional_settings

---

## Industry Applications

1. **Microsoft Azure Quantum Elements**
   - URL: https://quantum.microsoft.com/en-us/quantum-elements/product-overview

2. **IonQ's Accelerated Roadmap**
   - URL: https://ionq.com/blog/ionqs-accelerated-roadmap-turning-quantum-ambition-into-reality

3. **IBM Quantum Advantage Era**
   - URL: https://www.ibm.com/quantum/blog/quantum-advantage-era

4. **Quantum Computing in Biopharma**
   - URL: https://www.lek.com/insights/hea/us/ei/quantum-computing-biopharma-future-prospects-and-strategic-insights

5. **How Quantum Computing is Transforming Drug Discovery**
   - URL: https://www.pharmafocuseurope.com/articles/how-quantum-computing-is-transforming-drug-discovery

---

## Benchmarking and Metrics

### Quantum Volume
1. **Quantum Volume - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Quantum_volume

2. **Quantum Volume - Quera Glossary**
   - URL: https://www.quera.com/glossary/quantum-volume

3. **Quantum Volume Tutorial - PennyLane**
   - URL: https://pennylane.ai/qml/demos/quantum_volume

4. **Quantum Volume Experiments - Qiskit**
   - URL: https://qiskit-community.github.io/qiskit-experiments/manuals/verification/quantum_volume.html

### Other Metrics
1. **Randomized Benchmarking - Wikipedia**
   - URL: https://en.wikipedia.org/wiki/Randomized_benchmarking

2. **Randomized Benchmarking Tutorial - Qiskit**
   - URL: https://qiskit-community.github.io/qiskit-experiments/manuals/verification/randomized_benchmarking.html

3. **Circuit Depth Guide**
   - URL: https://www.numberanalytics.com/blog/ultimate-guide-to-quantum-circuit-depth

4. **Quantum Fidelity**
   - URLs:
     - https://www.quera.com/glossary/fidelity
     - https://www.spinquanta.com/news-detail/quantum-fidelity

---

## Review Articles and Surveys

1. **Quantum Algorithms: An Overview**
   - Authors: Artur Ekert, Patrick Hayden, Hitoshi Inamori
   - Year: 2008
   - Journal: AI-Inspired Biology: A Compendium of Papers

2. **Hybrid Quantum-Classical Algorithms**
   - Authors: Suguru Endo, Zhenyu Cai, Simon C. Benjamin, Xiao Yuan
   - Year: 2021
   - Journal: Journal of the Physical Society of Japan

3. **Quantum Algorithms for Chemistry and Materials Science**
   - URL: https://www.researchgate.net/publication/346952175_Quantum_Algorithms_for_Quantum_Chemistry_and_Quantum_Materials_Science

4. **Chemical Reviews on Quantum Computing**
   - URLs:
     - https://pubs.acs.org/doi/10.1021/acs.chemrev.9b00829
     - https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00678

---

## Educational Resources

1. **Microsoft Quantum Education**
   - URL: https://quantum.microsoft.com/en-us/insights/education/concepts/quantum-algorithms

2. **Introduction to Quantum Applications**
   - URL: https://introtoquantum.org/essentials/applications-overview/

3. **Understanding Quantum Algorithms - Complete Guide**
   - URL: https://medium.com/@caraque465/day-15-ii-understanding-quantum-algorithms-a-complete-guide-with-code-examples-0bcdacc1d0c0

4. **Qiskit Circuit Documentation**
   - URL: https://quantum.cloud.ibm.com/docs/api/qiskit/1.0/circuit

---

## Additional Resources

### Quantum Advantage Research
1. **Quantum Advantage Era Analysis**
   - URL: https://thequantuminsider.com/2025/07/23/taking-advantage-researchers-offer-a-measured-path-toward-quantum-advantage/

2. **QAOA Surpasses Classical Heuristics**
   - URL: https://quantumzeitgeist.com/quantum-computing-qaoaamplitude-amplification-surpasses-classical-heuristics-in-optimization-problems/

### Specialized Topics
1. **Quantum Computing for Financial Mathematics**
   - URL: https://www.siam.org/publications/siam-news/articles/quantum-computing-for-financial-mathematics/

2. **Quantum Computing in Medicine**
   - URL: https://pmc.ncbi.nlm.nih.gov/articles/PMC11586987/

3. **Quantum Query Complexity Guide**
   - URL: https://www.numberanalytics.com/blog/quantum-query-complexity-guide

### Recent Developments (2024-2025)
1. **Quantum Algorithms Call to Action**
   - URL: https://quantumfrontiers.com/2025/04/20/quantum-algorithms-a-call-to-action/

2. **Today's Quantum Computers Could Aid Molecular Simulation**
   - URL: https://thequantuminsider.com/2025/07/15/study-suggests-todays-quantum-computers-could-aid-molecular-simulation/

---

## How to Use This Collection

This collection is organized by topic to facilitate research in specific areas of quantum computing. Each source includes:
- Title
- Authors (where applicable)
- Year (where applicable)
- URL or publication information
- Brief description of relevance

For researchers focusing on specific applications:
- **Drug Discovery**: See sections on Quantum Chemistry, Protein Folding, and Industry Applications
- **Algorithm Development**: Focus on Core Algorithms, VQE, and QAOA sections
- **NISQ Implementation**: Check NISQ Era, Error Mitigation, and Hybrid Approaches
- **Benchmarking**: Refer to the Benchmarking and Metrics section

---

## Contributing

To add new sources to this collection, please follow this format:
```markdown
1. **Title of Source**
   - Authors: [if applicable]
   - Year: [if applicable]
   - Journal/Publisher: [if applicable]
   - URL: [direct link]
   - Description: [brief description of relevance]
```

---

## License

This is a curated collection of publicly available sources. Individual sources retain their original licenses and copyrights.
