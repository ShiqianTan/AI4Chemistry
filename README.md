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
- [Ab initio quantum chemistry with neural-network wavefunctions](https://www.nature.com/articles/s41570-023-00516-8) [2023] - Nature Review Chemistry
- [Toward Orbital-Free Density Functional Theory with Small Data Sets and Deep Learning](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00812) [2022] - JCTC, orbitral-free DFT
- [Pushing the frontiers of density functionals by solving the fractional electron problem](https://www.science.org/doi/10.1126/science.abj6511) [2021] - Science, DFT, DM21
- [Deep-neural-network solution of the electronic Schrödinger equation](https://www.nature.com/articles/s41557-020-0544-y) [2020] - Nature Chemistry
- [Solving the quantum many-body problem with artificial neural networks](https://www.science.org/doi/10.1126/science.aag2302) [2017] - Science, The first application of NN to represent many-body wavefunctions
- [Backflow Transformations via Neural Networks for Quantum Many-Body Wave Functions](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.226401) [2019] - PRL

## ML force fields
- [Generalized Neural-Network Representation of High-Dimensional Potential-Energy Surfaces](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401) [2007] - Pioneering work
- [Learning local equivariant representations for large-scale atomistic dynamics](https://www.nature.com/articles/s41467-023-36329-y) [2023] - Nature Communication
- [E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials](https://www.nature.com/articles/s41467-022-29939-5) [2022] - Nature Communication
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

## Cheminformatic software
- RDKit - free
- Open Babel - free
- CODESSA - commercial
- DRAGON - commercial
