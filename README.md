# AI4Chemistry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A curated list of awesome papers, tools, authors, books, blogs and other resources related to AI4Chemistry or AI4Materials.

Inspired by [awesome-python](https://awesome-python.com) and [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry).

## Table of contents

- [Awesome AI for chemistry](#ai4chemistry-)
  - [Publication statistics](#publication-statistics)
  - [Review](#review)
  - [Materials](#materials)
  - [Machine learning Algorithm](#machine-learning-algorithm)
  - [Cheminformatic software](#cheminformatic-software)

## Machine learning algorithm
- [Machine Learning: A Review of the Algorithms and Its Applications](https://link.springer.com/chapter/10.1007/978-3-030-29407-6_5) [2019]

## Review
- [Cross-disciplinary perspectives on the potential for artificial intelligence across chemistry](https://pubs.rsc.org/en/content/articlelanding/2025/cs/d5cs00146c) [2025]
- [Generative Models as an Emerging Paradigm in the Chemical Sciences](https://pubs.acs.org/doi/10.1021/jacs.2c13467) [2023]
- [A Survey on ensemble learning under the era of deep learning](https://link.springer.com/article/10.1007/s10462-022-10283-5) [2022]
- [Machine Learning for Molecular Simulation](https://www.annualreviews.org/content/journals/10.1146/annurev-physchem-042018-052331) [2020]
- [Data Reduction Techniques for Simulation, Visualization and Data Analysis](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13336) [2018]
- [Materials discovery and design using machine learning](https://www.sciencedirect.com/science/article/pii/S2352847817300515) [2017]

## Representation learning
- [Element similarity in high-dimensional materials representations](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00121k)[2023]


## Materials

### Ionic Liquids
- [Online chemical modeling environment (OCHEM): web platform for data storage, model development and publishing of chemical information](https://link.springer.com/article/10.1007/s10822-011-9440-2) [2021] - Dataset
- [ILThermo](https://ilthermo.boulder.nist.gov/) - Dataset
- [Vaporization enthalpy prediction of ionic liquids based on back-propagation artificial neural network](https://www.sciencedirect.com/science/article/pii/S2666952825000202#sec2) [2025] - 3150 data points, Vaporization enthalpy prediction
- [Large-Scale Screening for High Conductivity Ionic Liquids via Machine Learning Algorithm Utilizing Graph Neural Network-Based Features](https://pubs.acs.org/doi/full/10.1021/acs.jced.3c00709) [2024] - 5700 data points, conductivity, GNN+XGBoost
- [Rapid and Accurate Prediction of the Melting Point for Imidazolium-Based Ionic Liquids by Artificial Neural Network](https://www.mdpi.com/2624-8549/6/6/94) [2024] - 280 data points, melting point
- [Machine learning coupled with group contribution for predicting the electrical conductivity of ionic liquids with experimental accuracy](https://www.sciencedirect.com/science/article/pii/S0378381224000013?via%3Dihub#sec0014) [2024] - 7598, electrical conductivity
- [Generalizing property prediction of ionic liquids from limited labeled data: a one-stop framework empowered by transfer learning](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00040k) [2023] - Transformer-CNN, diverse ILs properties
- [ILTox: A Curated Toxicity Database for Machine Learning and Design of Environmentally Friendly Ionic Liquids](https://pubs.acs.org/doi/10.1021/acs.estlett.3c00106?ref=PDF) [2023] - 6700 data points, Toxicity
- [Benchmarking machine learning methods for modeling physical properties of ionic liquids](https://www.sciencedirect.com/science/article/pii/S0167732222001532?via%3Dihub) [2022]
- [A review of group contribution models to calculate thermodynamic properties of ionic liquids for process systems engineering](https://www.sciencedirect.com/science/article/pii/S0263876222003823?via%3Dihub) [2022] - Review
- [Predictive molecular thermodynamic models for ionic liquids](https://aiche.onlinelibrary.wiley.com/doi/10.1002/aic.17575) [2022] - Review
- [Comparison of molecular and structural features towards prediction of ionic liquid ionic conductivity for electrochemical applications](https://www.sciencedirect.com/science/article/pii/S0167732222021596?via%3Dihub#s0080) [2022] - Benchmark
- [Predicting CO2 Absorption in Ionic Liquids with Molecular Descriptors and Explainable Graph Neural Networks](https://pubs.acs.org/doi/10.1021/acssuschemeng.2c05985?ref=PDF) [2022] - CO2 Absorption in Ionic Liquids, GNN 
- [A review on machine learning algorithms for the ionic liquid chemical space](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc01000j) [2021] - Review
- [Application of Artificial Intelligence-based predictive methods in Ionic liquid studies: A review](https://www.sciencedirect.com/science/article/pii/S0378381220304477?via%3Dihub) [2021] - Review
- [Beware of proper validation of models for ionic Liquids](https://www.sciencedirect.com/science/article/pii/S0167732221024478?via%3Dihub) [2021] - Melting point temperature, Transformer-CNN
- [Neural recommender system for the activity coefficient prediction and UNIFAC model extension of ionic liquid-solute systems](https://aiche.onlinelibrary.wiley.com/doi/10.1002/aic.17171) [2021] - 41553 data points, activity coefficient prediction, GNN
- [Viscosity of Ionic Liquids: An Extensive Database and a New Group Contribution Model Based on a Feed-Forward Artificial Neural Network](https://pubs.acs.org/doi/10.1021/ci500206u?ref=PDF) [2014] - Group contribution method

## Pretraining model
- [Molecular contrastive learning of representations via graph neural networks](https://www.nature.com/articles/s42256-022-00447-x) [2022] - MolCLR (Molecular Contrastive Learning of Representations via Graph Neural Networks)
- [Mol-BERT: An Effective Molecular Representation with BERT for Molecular Property Prediction](https://onlinelibrary.wiley.com/doi/10.1155/2021/7181815) [2021] - BERT
- [SMILES-BERT: Large Scale Unsupervised Pre-Training for Molecular Property Prediction](https://dl.acm.org/doi/10.1145/3307339.3342186) [2019] - BERT

## Quantum Chemistry
- [Ab-initio variational wave functions for the time-dependent many-electron Schrödinger equation](https://www.nature.com/articles/s41467-024-53672-w) [2024] - Nature Communication
- [Accurate computation of quantum excited states with neural networks](https://www.science.org/doi/10.1126/science.adn0137) [2024] - Science, Exicted State
- [A deep equivariant neural network approach for efficient hybrid density functional calculations](https://www.nature.com/articles/s41467-024-53028-4) [2024]
- [Ab initio quantum chemistry with neural-network wavefunctions](https://www.nature.com/articles/s41570-023-00516-8) [2023] - Nature Review Chemistry
- [Toward Orbital-Free Density Functional Theory with Small Data Sets and Deep Learning](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00812) [2022] - JCTC, orbitral-free DFT
- [Pushing the frontiers of density functionals by solving the fractional electron problem](https://www.science.org/doi/10.1126/science.abj6511) [2021] - Science, DFT, DM21
- [Deep-neural-network solution of the electronic Schrödinger equation](https://www.nature.com/articles/s41557-020-0544-y) [2020] - Nature Chemistry
- [Solving the quantum many-body problem with artificial neural networks](https://www.science.org/doi/10.1126/science.aag2302) [2017] - Science, The first application of NN to represent many-body wavefunctions
- [Backflow Transformations via Neural Networks for Quantum Many-Body Wave Functions](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.226401) [2019] - PRL

## ML force fields
- [Generalized Neural-Network Representation of High-Dimensional Potential-Energy Surfaces](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401) [2007] - Pioneering work
- [Fast and flexible long-range models for atomistic machine learning](https://pubs.aip.org/aip/jcp/article/162/14/142501/3342834/Fast-and-flexible-long-range-models-for-atomistic) [2025]
- [Learning local equivariant representations for large-scale atomistic dynamics](https://www.nature.com/articles/s41467-023-36329-y) [2023] - Nature Communication
- [E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials](https://www.nature.com/articles/s41467-022-29939-5) [2022] - Nature Communication
- [A universal graph deep learning interatomic potential for the periodic table](https://www.nature.com/articles/s43588-022-00349-3) [2022]
- [Physics-Inspired Structural Representations for Molecules and Materials](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00021) [2021] - Review
- [Gaussian Process Regression for Materials and Molecules](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00022) [2021] - Review
- [Machine Learning Force Fields](https://pubs.acs.org/doi/10.1021/acs.chemrev.0c01111) [2021] - Review
- [Machine Learning Force Fields: Recent Advances and Remaining Challenges](https://pubs.acs.org/doi/10.1021/acs.jpclett.1c01204) [2021] - perspective

## Inverse design
- [Has generative artificial intelligence solved inverse materials design?](https://www.cell.com/matter/fulltext/S2590-2385(24)00242-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS259023852400242X%3Fshowall%3Dtrue) [2024]
- [Machine learning-aided generative molecular design](https://www.nature.com/articles/s42256-024-00843-5) [2024]
- [Scientific discovery in the age of artificial intelligence](https://www.nature.com/articles/s41586-023-06221-2) [2023] - Nature
- [Art and the science of generative AI](https://www.science.org/doi/10.1126/science.adh4451) [2023] - Science
- [Discovering and understanding materials through computation](https://www.nature.com/articles/s41563-021-01015-1) [2021]
- [Structure prediction drives materials discovery](https://www.nature.com/articles/s41578-019-0101-8) [2019]
- [Inverse design in search of materials with target functionalities](https://www.nature.com/articles/s41570-018-0121) [2018]

## Generative model
### GAN
- [Generative Adversarial Networks for Crystal Structure Prediction](https://pubs.acs.org/doi/10.1021/acscentsci.0c00426) [2020]
- [MolGAN: An implicit generative model for small molecular graphs](https://arxiv.org/abs/1805.11973) [2018]
- [Reinforced Adversarial Neural Computer for de Novo Molecular Design](https://pubs.acs.org/doi/10.1021/acs.jcim.7b00690) [2018]
- [Objective-Reinforced Generative Adversarial Networks (ORGAN) for Sequence Generation Models](https://arxiv.org/abs/1705.10843) [2017] - Pioneering work of using generative work in chemistry

### VAE
- [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114) [2013] - Pioneering work
- [WyCryst: Wyckoff inorganic crystal generator framework](https://www.cell.com/matter/abstract/S2590-2385(24)00305-9?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2590238524003059%3Fshowall%3Dtrue) [2024]
- [Deep generative design of porous organic cages via a variational autoencoder](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00154g) [2023]
- [An invertible crystallographic representation for general inverse design of inorganic crystals with targeted properties](https://www.cell.com/matter/fulltext/S2590-2385(21)00625-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2590238521006251%3Fshowall%3Dtrue) [2022]
- [The Usual Suspects? Reassessing Blame for VAE Posterior Collapse](https://arxiv.org/abs/1912.10702) [2019]
- [Inverse Design of Solid-State Materials via a Continuous Representation](https://www.cell.com/matter/fulltext/S2590-2385(19)30175-4?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2590238519301754%3Fshowall%3Dtrue) [2019]
- [Constrained Graph Variational Autoencoders for Molecule Design](https://arxiv.org/abs/1805.09076) [2018]
- [Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules](https://pubs.acs.org/doi/10.1021/acscentsci.7b00572) [2018] - Pioneering work in molecule generation

### Flow model
- [Unified Generative Modeling of 3D Molecules via Bayesian Flow Networks](https://arxiv.org/abs/2403.15441) [2024]
- [FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions](https://arxiv.org/abs/2410.23405) [2024]
- [Normalizing Flows for Probabilistic Modeling and Inference](https://arxiv.org/abs/1912.02762) [2019] - Pioneering work

### Diffusion model
- [A generative model for inorganic materials design](https://www.nature.com/articles/s41586-025-08628-5) [2025] - Nature
- [Con-CDVAE: A method for the conditional generation of crystal structures](https://www.sciencedirect.com/science/article/pii/S2950463524000036?via%3Dihub) [2024]
- [Deep learning generative model for crystal structure prediction](https://www.nature.com/articles/s41524-024-01443-y) [2024]
- [Space Group Constrained Crystal Generation](https://arxiv.org/abs/2402.03992) [2024]
- [Equivariant 3D-conditional diffusion model for molecular linker design](https://www.nature.com/articles/s42256-024-00815-9) [2024]
- [Guided diffusion for inverse molecular design](https://www.nature.com/articles/s43588-023-00532-0) [2023]
- [Scalable Diffusion for Materials Generation](https://arxiv.org/abs/2311.09235) [2023]
- [Crystal Diffusion Variational Autoencoder for Periodic Material Generation](https://arxiv.org/abs/2110.06197) [2021] - Pioneering work in crystal materials generation
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) [2020] - Pioneering work

### Autogressive model
- [MatterGPT: A Generative Transformer for Multi-Property Inverse Design of Solid-State Materials](https://arxiv.org/abs/2408.07608) [2024]
- [AtomGPT: Atomistic Generative Pretrained Transformer for Forward and Inverse Materials Design](https://pubs.acs.org/doi/10.1021/acs.jpclett.4c01126) [2024]
- [Language models can generate molecules, materials, and protein binding sites directly in three dimensions as XYZ, CIF, and PDB files](https://arxiv.org/abs/2305.05708) [2024]
- [Crystal structure generation with autoregressive large language modeling](https://www.nature.com/articles/s41467-024-54639-7) [2024]
- [GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation](https://arxiv.org/abs/2001.09382) [2020]

### Reality consideration
- [It Takes Two to Tango: Directly Optimizing for Constrained Synthesizability in Generative Molecular Design](https://arxiv.org/abs/2410.11527) [2024]
- [Molecular Generative Model via Retrosynthetically Prepared Chemical Building Block Assembly](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202206674) [2023]
- [Chemistry-intuitive explanation of graph neural networks for molecular property prediction with substructure masking](https://www.nature.com/articles/s41467-023-38192-3) [2023]
- [From Black Boxes to Actionable Insights: A Perspective on Explainable Artificial Intelligence for Scientific Discovery](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01642) [2023]
- [Computer-aided multi-objective optimization in small molecule discovery](https://www.cell.com/patterns/fulltext/S2666-3899(23)00001-6?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2666389923000016%3Fshowall%3Dtrue) [2023]
- [Interpretable machine learning for knowledge generation in heterogeneous catalysis](https://www.nature.com/articles/s41929-022-00744-z) [2022]
- [Explainable graph neural networks for organic cages](https://pubs.rsc.org/en/content/articlelanding/2022/dd/d1dd00039j) [2022]
- [Materials Precursor Score: Modeling Chemists’ Intuition for the Synthetic Accessibility of Porous Organic Cage Precursors](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00375) [2021]
- [Drug discovery with explainable artificial intelligence](https://www.nature.com/articles/s42256-020-00236-4) [2020]

### Others
- [Exploration of crystal chemical space using text-guided generative artificial intelligence](https://chemrxiv.org/engage/chemrxiv/article-details/6728e27cf9980725cf118177) [2024]
- [Closing the Execution Gap in Generative AI for Chemicals and Materials: Freeways or Safeguards](https://mit-genai.pubpub.org/pub/681kpeoa/release/1) [2024] - Blog
- [Generative Hierarchical Materials Search](https://arxiv.org/abs/2409.06762) [2024]
- [Generative Models as an Emerging Paradigm in the Chemical Sciences](https://pubs.acs.org/doi/10.1021/jacs.2c13467) [2023] - Review
- [Dismai-Bench: benchmarking and designing generative models using disordered materials and interfaces](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00100a) [2024] - Benchmarking
- [matbench-genmetrics: A Python library for benchmarking crystal structure generative models using time-based splits of Materials Project structures](https://joss.theoj.org/papers/10.21105/joss.05618) [2024] - Benchmarking
- [Fine-Tuned Language Models Generate Stable Inorganic Materials as Text](https://arxiv.org/abs/2402.04379) [2024]
- [Molecular Sets (MOSES): A Benchmarking Platform for Molecular Generation Models](https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2020.565644/full) [2020] - Benchmarking

## Bayeysian optimization
- [System-Aware Neural ODE Processes for Few-Shot Bayesian Optimization](https://arxiv.org/abs/2406.02352) [2024]
- [A survey and benchmark of high-dimensional Bayesian optimization of discrete sequences](https://arxiv.org/abs/2406.04739) [2024]
- [Race to the bottom: Bayesian optimisation for chemical problems](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00234a) [2024]
- [Bayesian reaction optimization as a tool for chemical synthesis](https://www.nature.com/articles/s41586-021-03213-y) [2021] - Nature
- [Practical Bayesian Optimization of Machine Learning Algorithms](https://arxiv.org/abs/1206.2944) [2012]

## LLM for chemistry or materials
- [A review of large language models and autonomous agents in chemistry](https://pubs.rsc.org/en/content/articlelanding/2025/sc/d4sc03921a) [2025] - Review
- [34 Examples of LLM Applications in Materials Science and Chemistry: Towards Automation, Assistants, Agents, and Accelerated Scientific Discovery](https://arxiv.org/pdf/2505.03049) [2025]
- [AlchemBERT: Exploring Lightweight Language Models for Materials Informatics](https://chemrxiv.org/engage/chemrxiv/article-details/6781a6b481d2151a02a3212e) [2025]
- [Large Language Models as Molecular Design Engines](https://pubs.acs.org/doi/10.1021/acs.jcim.4c01396) [2024]
- [Leveraging large language models for predictive chemistry](https://www.nature.com/articles/s42256-023-00788-1) [2024]
- [Augmenting large language models with chemistry tools](https://www.nature.com/articles/s42256-024-00832-8) [2024]
- [Foundational Large Language Models for Materials Research](https://arxiv.org/abs/2412.09560) [2024]
- [Scientific Large Language Models: A Survey on Biological & Chemical Domains](https://arxiv.org/abs/2401.14656) [2024]
- [A survey on multimodal large language models](https://academic.oup.com/nsr/article/11/12/nwae403/7896414?login=false) [2024]
- [Chemical language modeling with structured state space sequence models](https://www.nature.com/articles/s41467-024-50469-9) [2024]
- [Fine-tuning GPT-3 for machine learning electronic and functional properties of organic molecules](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc04610a) [2024] - GPT3
- [Large Language Models as Master Key: Unlocking the Secrets of Materials Science with GPT](https://arxiv.org/abs/2304.02213) [2023]
- [Catalyst Energy Prediction with CatBERTa: Unveiling Feature Exploration Strategies through Large Language Models](https://pubs.acs.org/doi/10.1021/acscatal.3c04956?ref=PDF) [2023] - CatBERTa

## Self-Driving Laboratory
- [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) [2024] - Review

## Multi-task learning
- [Boosting Tree-Assisted Multitask Deep Learning for Small Scientific Datasets](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01184) [2020]

## AI for Materials symposium or conference
- [AI4Mat-ICLR 2025](https://sites.google.com/view/ai4mat/home) [2025]
- [AI4Mat-2023 workshop at NeurIPS 2023](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd90010c) [2023]

## Cheminformatic software
- RDKit - free
- Open Babel - free
- CODESSA - commercial
- DRAGON - commercial
