---
layout: page
title: Research
permalink: /research/
---

My research and teaching interests include computational and applied mathematics. In particular, my current research focuses on constructing highly accurate fast algorithms leveraging approximation theory and numerical linear algebra.

<img src="SAFRAN_Logo.png" alt="SAFRAN" width="200">

The SAFRAN (Stable Accurate Fast Robust Algorithms & Numerics) group was born in April 2016 at IISc and moved to IITM in September 2017. Students interested to be part of the group [can apply for the research program at IITM Madras](https://research.iitm.ac.in/). Interested candidates are strongly encouraged to apply to either the Mathematics Department or the Interdisciplinary program. [More details on the research at Mathematics Department and the Interdisciplinary program can be found here.](https://research.iitm.ac.in/department_list)

### Members:

#### Current

1. Sivaram Ambikasaran (Convenor)
2. Nachiketa Mishra - (Post Doctoral Fellow, ICTS)
3. Kandappan - (Ph.D. Student, IISc)
4. Manisha - (Ph.D. Student, ICTS)
5. Vaishnavi - (Ph.D. Student, IISc)
6. Abhay Gupta - (M.Tech. Research Student, IISc)

#### Alumni

1. Richa Naik (Intern, IITM)
2. Deeksha Koul (Final Year Project student, DAICT)
3. Karan Raj Singh (Project Assistant, BITS)
4. Chaitanya Tappu (S.N.Bhat Intern, IISc)
5. Ankit Kumar (S.N.Bhat Intern, NIT Rourkela)

### Publications

[Link to Google Scholar](https://scholar.google.co.in/citations?user=h2hgRJoAAAAJ&hl=en)

1. Daniel Foreman-Mackey, Eric Agol, Ruth Angus, <span style="color:magenta">**Sivaram Ambikasaran**</span>, "[Fast and scalable Gaussian process modeling with applications to astronomical time series](https://arxiv.org/abs/1703.09710)", Submitted to AAS journals.
2. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Krithika Narayanaswamy, "[An accurate, fast, mathematically robust, universal, non-iterative algorithm for computing multi-component diffusion velocities](http://www.sciencedirect.com/science/article/pii/S1540748916300554)", Proceedings of Combustion Institute.
3. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Carlos Borges, Lise-Marie Imbert-Gerard, Leslie Greengard, "[Fast, adaptive, high order discretization of the Lippmann-Schwinger equation in two dimension](http://epubs.siam.org/doi/abs/10.1137/15M102455X)", SIAM Journal of Scientific Computing
4. <span style="color:magenta">**Sivaram Ambikasaran**</span>, "[Generalized Rybicki Press algorithm](http://onlinelibrary.wiley.com/doi/10.1002/nla.2003/full)", Numerical Linear Algebra with Applications.
5. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Michael O'Neil, Karan Raj Singh, "[Fast symmetric factorization of hierarchical matrices with applications](https://arxiv.org/abs/1405.0223)"
6. Amirhossein Aminfar, <span style="color:magenta">**Sivaram Ambikasaran**</span>, Eric Darve, ``[A fast block low-rank dense solver with applications to finite-element matrices](http://www.sciencedirect.com/science/article/pii/S0021999115006750)", Journal of Computational Physics
7. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Daniel Foreman-Mackey, Leslie Greengard, David W Hogg, Michael O'Neil, ``[Fast Direct Methods for Gaussian Processes](http://ieeexplore.ieee.org/document/7130620/?reload=true)", Transactions on Pattern Analysis and Machine Intelligence
8. Jun Lai, <span style="color:magenta">**Sivaram Ambikasaran**</span>, Leslie F Greengard, ``[A fast direct solver for high frequency scattering from a large cavity in two dimensions](http://epubs.siam.org/doi/abs/10.1137/140964904)", SIAM Journal of Scientific Computing
9. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Eric Darve, "[The Inverse Fast Multipole Method](http://arxiv.org/abs/1407.1572)"
10. Judith Y Li, <span style="color:magenta">**Sivaram Ambikasaran**</span>, Eric Darve, Peter K Kitanidis, "[A Kalman filter powered by ℋ<sup>2</sup>-matrices for quasi-continuous data assimilation problems](http://onlinelibrary.wiley.com/wol1/doi/10.1002/2013WR014607/abstract)", Water Resources Research.
11. <span style="color:magenta">**Sivaram Ambikasaran**</span>, "[Fast Algorithms for Dense Numerical Linear Algebra and Applications, Stanford Thesis](https://purl.stanford.edu/tj786mf7514)", Stanford Thesis
12. <span style="color:magenta">**Sivaram Ambikasaran**</span>, Arvind Krishna Saibaba, Eric Darve, Peter K Kitanidis, "[Fast Algorithms for Bayesian Inversion](https://link.springer.com/chapter/10.1007/978-1-4614-7434-0_5)", The IMA Volumes in Mathematics and its Applications
13. Arvind Krishna Saibaba, <span style="color:magenta">**Sivaram Ambikasaran**</span>, Judith Y Li, Peter K Kitanidis, Eric Darve, "[Application of hierarchical matrices in geostatistics](https://ogst.ifpenergiesnouvelles.fr/articles/ogst/abs/2012/05/ogst120061/ogst120061.html)", Oil & Gas Science and Technology - Revue d'IFP Energies Nouvelles.
14. Sivaram Ambikasaran, Judith Y Li, Peter K Kitanidis, Eric Darve, "[Large-scale stochastic linear inversion using hierarchical matrices](https://link.springer.com/article/10.1007/s10596-013-9364-0)", Computational Geosciences.
15. <span style="color:magenta">**Sivaram Ambikasaran**</span>, and Eric Darve, "[An 𝒪(*N*log*N*) fast direct solver for partially hierarchical semi-separable matrices](https://link.springer.com/article/10.1007/s10915-013-9714-z)", Journal of Scientific Computing.
16. K. Bhaskar, <span style="color:magenta">**Sivaram Ambikasaran**</span>, ``[Untruncated infinite series superposition method for accurate flexural analysis of isotropic/orthotropic rectangular plates with arbitrary edge conditions](http://www.sciencedirect.com/science/article/pii/S0263822307001067)", Composite Structures.
{: reversed="reversed"}

## Sample Research

1. ### Fast Linear Algebra Algorithms
	The major focus of the group is to reduce the computational complexity of linear algebra algorithms at the same time maintaining high accuracy.
	
	* #### Dense linear algebra
	Typically, linear algebra algorithms for dense matrix vector products scale as 𝒪(*N*<sup>2</sup>) and for solving dense linear systems scale as 𝒪(*N*<sup>3</sup>), where the underlying matrix is of size *N* × *N*. This is excruciatingly slow for large-scale practical problems, making it unattractive for large-scale simulation needed for optimization and design. However, note that since most of the computation is done in finite precision (say machine precision of 16 digits), we can devise approximate but arbitrarily accurate numerical algorithms, that scales favorably and guaranteeing high precision.	
	<center>
	<img src="H2D_level_2.jpg" alt="H2D_level_2" width="250">
	<img src="H2D_level_3.jpg" alt="H2D_level_3" width="250">
	<img src="H2D_level_4.jpg" alt="H2D_level_4" width="250">
	</center>

	* #### Sparse linear algebra
	To solve partial differential equations, discretizing the PDE using finite difference or finite element method is preferred in practice. Such discretizations result in a sparse linear system, which needs to be solved. Solving the corresponding linear system of size *N* × *N* using nested dissection or multifrontal strategies requires a computational cost of 𝒪(*N*<sup>(*d*+1)/2</sup>), where *d* is the underlying dimension. Our focus is on reducing these computational costs to 𝒪(*N*) guaranteeing high precision.

	<center>
	<img src="engine.png" alt="engine" width="400">
	<img src="nested_Dissection.png" alt="nested_dissection" width="400">
	</center>
	
2. ### Design Centric PDE Solvers
	One major application focus of our group is on designing accurate, fast ODE solvers for a wide range of applications, for instance, electromagnetic scattering from penetrable and impenetrable objects, advance stealth applications, material homogenization, imaging, etc. Traditional solvers have been mainly based on iterative techniques, which has its own set of disadvantages. For instance, the number of iterations to converge may be extremely large making it impractical. Another disadvantage, especially for design, is that any modifciation to the geometry or incoming field typically results in restarting the entire iterative solver, which is definitely not desirable. To circumvent these disadvantages, our focus is to design high accurate and fast *direct* solvers for such systems.

	<center>
	<img src="Scattering.png" alt="scattering" width="200">
	<img src="Scattering_1.png" alt="scattering" width="200">
	<img src="homogenization.png" alt="homogenization" width="400">
	</center>

3. ### Computational Statistics
	One of the core issues in computational statistics and large scale data analysis is efficient manipulation of dense covariance matrices, which describe the interdependence between several random variables or random processes. This is especially the case in spatial statistics and time series. In the previously mentioned contexts, the correlation matrices have a highly exploitable structure.	

	<center>
	<img src="corner.png" alt="Corner" width="300">
	<img src="kepler-prediction.png" alt="Light_curve" width="400">
	</center>

4. ### Black-box tools, reproducible and open source computational science
	There are several implementations of the fast multipole method and fast direct solvers, but very few provide standalone implementations or the basic ``building blocks" that can be easily re-used. One of our focus is to develop such standalone implementations, which will be of use in many other applications. Another endeavor is to have the tools for computational science available to the public as open source standalone numerical libraries. To this end, we maintain a GitHub repository(https://github.com/sivaramambikasaran) and a GitLab repository (https://gitlab.com/groups/SAFRAN), where all the numerical packages, which include fast multipole method, fast direct solvers, quadratures, etc., developed by us are posted and made available to the public.

	<center>
	<img src="code.png" alt="code" width="400">
	<img src="2DQuadTree.png" alt="Quad Tree" width="400">
	</center>
	
## List of possible research topics

Below are some of the possible research projects, one can pursue as a member of our group. The list is only indicative and by no means exhaustive. [Look here for more details on the research program at IIT Madras](https://research.iitm.ac.in/). Students are also welcome to discuss other projects that interest them to pursue research under my guidance.  [Choose Mathematics Department and Interdisciplinary program, if you wish to be considered for the group](https://research.iitm.ac.in/department_list).

* [HODLR: In-house fast linear algebra package for hierarchical matrices](http://tinyurl.com/gre8f4f)
* [Direct solvers for high frequency scattering](http://tinyurl.com/jqd9epp)
* [Linear complexity solvers for finite element matrices](http://tinyurl.com/jlpakjh)
* [Fast algorithms for integral equations based inverse obstacle scattering](http://tinyurl.com/za6nxuc)
* [Fast algorithms for integral equations based inverse medium scattering](http://tinyurl.com/j6u8kgw)
* [Linear complexity algorithms for computational statistics](http://tinyurl.com/zreaarp)
* [Algorithms for solving elliptic PDE's with rapidly oscillating coefficient with applications to material homogenisation](http://tinyurl.com/h3ycmgs)
* [Matrix Analysis: Pivoting algorithms and analysis of growth factor](http://tinyurl.com/jum7ffn)
* [Accurate multi-component diffusion in counterflow diffusion flame](https://www.dropbox.com/s/28dynq4ghio6ylr/Multicomponent_Diffusion.pdf?dl=0)
* [Compact chemical mechanism](https://www.dropbox.com/s/4u4lwm9qfqslxgk/Reduction_Methods.pdf?dl=0)
* [Accurate simulation of cool flames](https://www.dropbox.com/s/7iv8zrh9h6xhs00/Droplet_combustion.pdf?dl=0)


## Mathematical Packages

A significant part of the group's effort is to develop inhouse mathematical packages and make them available to the scientific community. These are made available in the hope that they will be useful, but without any warranty. All the codes can be redistributed and/or modified under the terms of the appropriate license.

* [BBFMM2D: Black Box Fast Multipole Method in two dimensions](https://github.com/sivaramambikasaran/BBFMM2D)
* [FLIPACK: Fast Linear Inversion PACKage](https://github.com/sivaramambikasaran/FLIPACK)
* [HODLR: Fast Direct Solver for hierarchical off-diagonal low-rank matrices](https://github.com/sivaramambikasaran/HODLR)
* [ESS: Extended Semi-Separable and the Generalized Rybicki Press algorithms](https://github.com/sivaramambikasaran/ESS)
* [George: Fast and flexible Python library for Gaussian Process Regression](http://dan.iel.fm/george/current/)
* [Celerite: A scalable method for Gaussian Process regression.](http://celerite.readthedocs.io/en/latest/)


## Funding

### Present
* INSPIRE faculty award by Department of Science & Technology
* Young Scientist Research Award by Department of Atomic Energy

### Past
* Start-up grant by Indian Institute of Science
* Simons Foundation Fellowship by ICTS
* Infosys Foundation Funding by ICTS
* AIG