# LinkReview

- Here we collect all the works that may be useful for writing our paper
- We divide these works by topic in order to structure them

> [!NOTE]
> This review table will be updated, so it is not a final version.
>
> Ill fix the format later
<!-- 
| Topic | Title | Year | Authors | Paper | Code | Summary |
| :--- | :--- | :---: | :--- | :---: | :---: | :--- |
| Topic #1 | Paper Title | Publishing Year | Author #1 et al. | [arXiv/DOI]() | [GitHub]() | Short summary to be inserted in the Related Work section |
|  | TODO | TODO | TODO | TODO | TODO | TODO | -->


| Number | Title | URL | Date | Score | Flag | Notes / Summary |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Accelerating scientific discovery with Co-Scientist | https://www.nature.com/articles/s41586-026-10644-y | 19 May 2026 | 3 |  | agents continuously generating, critiquing and refining hypotheses |
| 2 | AI co-mathematician: Accelerating mathematicians with agentic AI | https://arxiv.org/pdf/2605.06651 | 13 May 2026 | 2 |  | AI agents to pursue open-ended researc<br>mirrors human collaborative workflow |
| 3 | QED: An Open-Source Multi-Agent System for Generating Mathematical Proofs on Open Problems | https://arxiv.org/pdf/2604.24021 | 26 Jun 2026 | 3 |  | QED successfully produced original, nontrivial, and complete solutions to 5 research projects in algebraic geometry, fluid PDE, probability, and inverse problems. QED was operated fully automatically, and no expert guidance was provided during the run |
| 4 | Learning Interestingness in Automated Mathematical Theory Formation | https://arxiv.org/pdf/2511.14778 | 5 Nov 2025 | 4 | yes | github.com/trishullab/Fermat<br>algorithms for automatic theory formation<br>learning an<br>interestingness heuristic for selecting mathematical concepts to develop<br>sequential nature of mathematical discovery, where an agent iteratively expands<br>a body of knowledge by making choices about<br>definitions, conjectures, and proof attempt |
| 5 | AlphaEvolve: A coding agent for scientific and algorithmic discovery | https://arxiv.org/pdf/2506.13131 | 16 Jun 2025 | 2 |  | Using an evolutionary approach, continuously receiving feedback from one or more evaluators, AlphaEvolve iteratively improves the algorithm |
| 6 | Mathematical discoveries from program search with large language models | https://www.nature.com/articles/s41586-023-06924-6 | 14 December 2023 | 2 |  | FunSearch searches for programs that describe how to solve a problem, rather than what the solution is |
| 7 | Automatic Concept Formation in Pure Mathematics | https://www.ijcai.org/Proceedings/99-2/Papers/018.pdf | 1999 | 4 | yes | Using a set of production rules to derive a new concept from old ones and a set of measures for the interestingness of a concept, HR's best first search bases new concepts on the most interesting old ones. As it invents new definitions, HR uses empirical evidence to spot conjectures. Recently we have interfaced HR with the O T T E R theorem prover, [McCune, 1990], to prove some of the conjectures HR makes. When O T T E R fails, HR invokes the M A C E model finder, [McCune, 1994], to find a counter-example. The proofs from O T T E R help HR to assess the concepts involved in the conjectures, and the models given by M A C E provide further empirical evidence for future conjectures. |
| 8 | Discovering multiscale deep formulas in complex systems via neural-guided lambda calculus | https://www.nature.com/articles/s41467-026-74299-z | 16 June 2026 | -100 | no | TRASH |
| 9 | Think like a Scientist: Physics-guided LLM Agent for Equation Discovery | https://arxiv.org/pdf/2602.12259 | 24 Feb 2026 | 3 | yes | However, most existing LLM-based systems try to guess equations directly from data, without modeling the multi step reasoning process that scientists often follow The agent coordinates physics-based tools to extract intermediate structure and uses these results to configure symbolic regression engines such as PySINDy and PySR, including their function libraries and structural constraints. |
| 10 | The Float Wall and the Physics Pantheon: A 30-Billion Scale Benchmark for Zero-Bias Physical Discovery in Artificial Neural Networks | https://arxiv.org/pdf/2601.06117 | 15 Mar 2026 | 5 | yes | useful datasets, useful views |
| 11 | The FM Agent | https://arxiv.org/pdf/2510.26144 | 28 Feb 2026 | 3 |  | t FM Agent, a novel and general-purpose multi-agent framework that leverages a synergistic combination of LLM-based reasoning and large-scale evolutionary search to address complex real-world challenges. |
| 12 | MECA: A Mechanism-Centered Agent for Constructing Well-Specified and Valuable Mathematical Conjectures | https://arxiv.org/pdf/2607.27709 | 30 Jul 2026 | 2 |  |  |
| 13 | SYMBOLIC PHYSICS LEARNER: DISCOVERING GOVERNING EQUATIONS VIA MONTE CARLO TREE SEARCH | https://arxiv.org/pdf/2205.13134 | 2 Feb 2023 | 5 | yes | The key concept is to interpret mathematical operations and system state variables by computational rules and symbols, establish symbolic reasoning of mathematical formulas via expression trees, and employ a Monte Carlo tree search (MCTS) agent to explore optimal expression trees based on measurement data. The MCTS agent obtains an optimistic selection policy through the traversal of expression trees, featuring the one that maps to the arithmetic expression of underlying physics |
| 14 | AI Feynman: a Physics-Inspired Method for Symbolic Regression | https://arxiv.org/pdf/1905.11481 | 15 Apr 2020 | 4 | yes | We apply it to 100 equations from the Feynman Lectures on Physics, and it discovers all of them |
| 15 | LearnPhy: Progressive Hints to Incentivize Model Learning for Olympiad Physics | https://dl.acm.org/doi/full/10.1145/3788149.3788207 | 19 March 2026 | 2 |  | First, we construct a comprehensive dataset for high-difficulty multimodal physics reasoning. Our dataset, comprising PhysMCoT8K and PhysMCQ, contains both high-school and Olympiad-level questions. |
| 16 | A-SR: Self-Evolving Agentic LLMs for Symbolic Regression via Hierarchical Coordination | https://arxiv.org/pdf/2608.04872 | 6 Aug 2026 | 4 |  |  |
| 17 | Fine-Tuning Small Reasoning Models for Quantum Field Theory | https://arxiv.org/pdf/2604.18936 | April 22, 2026 | 5 | yes |  |
| 18 | AI Feynman: a Physics-Inspired Method for Symbolic Regression | https://arxiv.org/pdf/1905.11481 | April 15, 2020 | 5 | yes |  |
| 19 | Qwen2.5-Coder Technical Report | https://arxiv.org/pdf/2409.12186 | 12 Nov 2024 | 4 |  |  |
| 20 | SymbolicGPT: A Generative Transformer Model for Symbolic Regression | https://arxiv.org/pdf/2106.14131 | 27 Jun 2021 | 5 | yes | In this work, we explore an alternative approach to symbolic regression by considering it as a task in language modelling. Symbolic mathematics behaves as a language in its own right, with well-formed mathematical expressions treated as valid “sentences” in this language. |
| 21 | Symbolic Expression Transformer: A Computer Vision Approach for Symbolic Regression | https://arxiv.org/pdf/2205.11798 | 15 Jun 2022 | 5 | yes | The absence of large-scale benchmark datasets for comprehensive evaluation. Most existing methods are only benchmark on no more than hundreds of expressions (Table I). A large-scale dataset will help enrich the expression diversities and speed up the methodology development To address these issues, inspired by the fact that human beings can infer a function based on its curve, we proposed the Symbolic Expression Transformer (SET) from the CV view by representing sampled data as images |
| 22 | Learning From Graph-Structured Data: Addressing Design Issues and Exploring Practical Applications in Graph Representation Learning | https://arxiv.org/pdf/2411.07269 | 9 Nov 2024 | 1 |  |  |
| 23 | KAN: Kolmogorov–Arnold Networks | https://arxiv.org/pdf/2404.19756 | 9 Feb 2025 | 3 | yes | KANs are a newer architecture based on the Kolmogorov-Arnold representation theorem. They replace the fixed activation functions on nodes with learnable univariate functions on edges. This structure is inherently more interpretable, as the learned functions can be directly inspected and potentially symbolically regressed, offering a promising path toward automated law discovery |
| 24 | LORA: LOW-RANK ADAPTATION OF LARGE LANGUAGE MODELS | https://arxiv.org/pdf/2106.09685 | 16 Oct 2021 | 5 |  |  |
| 25 | Making the Most of your Model: Methods for Finetuning and Applying Pretrained Transformers | https://arxiv.org/pdf/2408.16241 | 29 Aug 2024 | 4 |  |  |
| 26 | Dynamic Adaptation of LoRA Fine-Tuning for Efficient and Task-Specific Optimization of Large Language Models | https://arxiv.org/pdf/2501.14859 | Submitted on 24 Jan 2025 | 4 |  |  |
| 27 | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | https://arxiv.org/pdf/1810.04805 | 24 May 2019 | 2 |  |  |
| 28 | RoBERTa: A Robustly Optimized BERT Pretraining Approach | https://arxiv.org/pdf/1907.11692 | 26 Jul 2019 | 2 |  |  |
| 29 | Interpretable Scientific Discovery with Symbolic Regression: A Review | https://arxiv.org/pdf/2211.10873 | 2 May 2023 | 4 |  |  |
| 30 | Genetic Programming Theory and Practice: A Fifteen-Year Trajectory | https://arxiv.org/pdf/2402.00425 | 1 Feb 2024 | 3 |  |  |
| 31 | Attention Is All You Need | https://arxiv.org/pdf/1706.03762 | 2 Aug 2023 | 3 |  |  |
| 32 | Evolving Code with A Large Language Model | https://arxiv.org/pdf/2401.07102 | 13 Jun 2024 | 3 |  |  |
| 33 | Symbolic Regression via Neural Networks | https://arxiv.org/pdf/2605.04337 | 5 May 2026 | 4 |  |  |
| 34 | Lean Meets Theoretical Computer Science: Scalable Synthesis of Theorem Proving Challenges in Formal-Informal Pairs |	https://arxiv.org/pdf/2508.15878 | 18 May 2026 | 3 |  |  |
| 35 | The Lean 4 Theorem Prover and Programming Language (System Description) | https://lean-lang.org/papers/lean4.pdf	| 4 |  |  |
| 36 | A Comprehensive Survey of the Lean 4 Theorem Prover: Architecture, Applications, and Advances | https://arxiv.org/pdf/2501.18639	| 3 |  |  |