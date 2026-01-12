## Applied Deep Learning Researcher (and Enjoyer!)
Hello, Welcome to my page! 🤗

Think of this page as a very general overview of the kinds of things that are interesting to me as well as some (*light*) discussion about previous projects.

## Education:
In progress: 
- Master's in Computer Science

Completed:
- Bachelor's in Computer Science

## Papers/Textbooks I am reading currently:
- [A Log-space Algorithm for Canonization of Planar Graphs](https://arxiv.org/abs/0809.2319)
- [Computational Optimal Transport](https://arxiv.org/pdf/1803.00567)


## Papers I have read:
- [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907)
- [De novo design of protein structure and function with RFdiffusion](https://www.nature.com/articles/s41586-023-06415-8)
- [SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks](https://arxiv.org/abs/2006.10503)
- [MAPE-PPI: Towards Effective and Efficient Protein-Protein Interaction Prediction via Microenvironment-Aware Protein Embedding](https://arxiv.org/abs/2402.14391)
- [Generative Adversarial Nets](https://arxiv.org/pdf/1406.2661)
- [Atomic context-conditioned protein sequence design using LigandMPNN](https://www.biorxiv.org/content/10.1101/2023.12.22.573103v1)
- [Robust deep learning–based protein sequence design using ProteinMPNN](https://www.science.org/doi/10.1126/science.add2187)
- [Deep Learning Model for Efficient Protein–Ligand Docking with Implicit Side-Chain Flexibility](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.2c01436)
- [GAABind: a geometry-aware attention-based network for accurate protein–ligand binding pose and binding affinity prediction](https://academic.oup.com/bib/article/25/1/bbad462/7473491)
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) (The Classic, of course)
- [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [Towards Predicting Equilibrium Distributions for Molecular Systems with Deep Learning](https://arxiv.org/abs/2306.05445)
- [Generative Modeling of Molecular Dynamics Trajectories](https://arxiv.org/abs/2409.17808v1)
- [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114) (Another Timeless Classic)
- [Combining Bayesian optimization with sequence- or structure-based strategies for optimization of peptide-binding protein](https://chemrxiv.org/engage/chemrxiv/article-details/6480388be64f843f4173003a)
- [Evolutionary-scale prediction of atomic-level protein structure with a language model](https://www.science.org/doi/10.1126/science.ade2574)
- [Protein Discovery with Discrete Walk-Jump Sampling](https://arxiv.org/abs/2306.12360)
- [Monte Carlo Methods](https://link.springer.com/book/10.1007/978-981-13-2971-5) (specifically chapter 11) 
- [Beyond Weisfeiler-Lehman: A Quantitative Framework for GNN Expressiveness](https://openreview.net/pdf?id=HSKaGOi7Ar)
- [Spherical Bessel Functions](https://arxiv.org/pdf/2102.02634)
- [DeepRank: a deep learning framework for data mining 3D protein-protein interfaces](https://www.nature.com/articles/s41467-021-27396-0)
- [Neural Network Potentials: A Concise Overview of Methods](https://arxiv.org/abs/2107.03727)
- [Wasserstein GAN](https://arxiv.org/abs/1701.07875)
- [GADIFF: a transferable graph attention diffusion model for generating molecular conformations](https://academic.oup.com/bib/article/26/1/bbae676/7934647)


## Previous Positions
- Research Assistant @ ASU Trans-AI-Lab
- ASU iGEM Team Lead
- Research Assistant/Software Developer @ BioProteanLab


## Current Position
- Research Assistant/Machine Learning Engineer @ Singharoy Lab in Biodesign Institute


## What's in my Repository?
- As of now, there are mostly mall projects and packages that I have tinkered around with to modify for my purposes.
- There are a few fully custom repositories, such as ConvolutionalSelfAttention and openBind; but also lots of half-finished and abandoned works like Grid2Demand.
  - I don't anticipate going back and finishing them, as the position I once filled in those projects is now passed on to someone else.
- Regardless, I will go into a brief interlude on what these projects [ConvlutionalSelfAttention](https://github.com/patjiang/ConvolutionalSelfAttention), [openBind](https://github.com/patjiang/openBind) represent.


### ConvolutionalSelfAttention
This is the more recent of my "finished" projects. The entire idea behind this project was implementing and understanding a framework which is widely adopted and used. The main motivation behind this adaptation of Nvidia's blog post in 2024 is actually providing salient visualizations, and also compare against methodologies I wanted to see. Overall, the purpose of the project was also to publicise and provide a basis implementation for the interesting framework they proposed. I think in the future, I may revisit this work, and add mroe commentary on which parts work and don't work.
- Main Pros
  - Implementing this project gave me a taste of what general benchmarking was like, and helped me develop the logic behind some of the benchmarking scripts I have developed for a project I did for a surveillance company. I am not sure if I could share the code, but I would love to discuss it.
- Main Cons
  - I truly underestimated how long this would take. What I thought would bhe a 1-2 week short project, eventually dragged onto a 3-4 week behemoth. Yeah, 3-4 weeks is not too long, but between research and classes, it felt like a slog, and I almost gave up a few times. Overall, I now have a greater appreciation to those who do benchmarking (and I'm sure it would've been easier if I did not want to do everything in google colab)


### openBind
This project is more of an integration of multiple end-to-end projects which already exist, but I wanted to create a very public usage of it. However, as of now, much of the code does not run anymore, due to some colab version issues and package control which I truly cannot be bothered to deal with. At the time, the idea was that binder design, either for the sake of teaching or specific drug design, ought to be more accessible. As the slow snowballing of foundational models required more and more compute over time, I thought the idea of a pipeline which could be run all from the convenience of a personal computer, with only the usage of a google account would be wonderful. And, on top of everything, most of the current work in the design pipelines did not use and kind of specific binder-specific binding affinity prediction methodologies yet, so adding a Kd prediction model would be good as well to help streamline the binder selection process. 
- Main Pros
  - This project ignited a desire within me for drug design problems that I couldn't have anticipated. Truly, I have this body of work to thank for the passion I feel now towards de novo design problems, and the idea of instrumentating full pipelines with multiple foundational models.
- Main Cons
  - The same pro is the con -- Other than the passion I felt, the long sleepless nights that I worked on this pipeline made it nearly impossible to test any of the final designs I had (in wet lab). If I could do this project again, I would spend less time merely running scripts and more time reading through the documentation and methodologies of those who come before me. I was naive and approached this project a bit hardheaded -- I would have loved to compare the binding models against rosetta energies or molecular dynamics, but I fear my current obligations prevent me from doing so.


### TBD
(future project retrospective... maybe?)
