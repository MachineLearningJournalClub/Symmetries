# Symmetries
Introduction to Geometric Deep Learning

### References 
* [Geometric Deep Learning Protobook](https://arxiv.org/abs/2104.13478)
* [A Wavelet Tour of Signal Processing](https://wavelet-tour.github.io/)


-----
## 1st Tutorial: Multiscale Representations and Wavelets

Taking inspiration from [Gabriel Peyre's Numerical Tours](https://github.com/gpeyre/numerical-tours)

In particular: 

* [Fourier & Wavelets](https://github.com/gpeyre/numerical-tours/blob/master/python/introduction_4_fourier_wavelets.ipynb) 
* [Image Denoising with Wavelets](https://github.com/gpeyre/numerical-tours/blob/master/python/denoisingwav_2_wavelet_2d.ipynb)
* [Comparison Fourier & Wavelets](https://www.samulski.nl/files/wavelets/wavelets.pdf)

__[BONUS]__

We can eventually try to re-implement some matlab code on specific wavelet families: 
* https://wavelet-tour.github.io/softwares/ 
* [Here](http://www.laurent-duval.eu/siva-wits-where-is-the-starlet.html#bandlet) a collection of a large variety of geometric multiscale transforms 

The notion of wavelets and multiscale separation is also used to build neural networks (i.e. Scattering Networks) 
* See [Kymatio](https://www.kymat.io/) for some implementations 
* In general the work of Stephane Mallat's Lab both on [Scholar](https://scholar.google.fr/citations?hl=fr&user=g_YTmSgAAAAJ&view_op=list_works&sortby=pubdate) and Github (scattered among lab members, for example see [this](https://github.com/j-zarka/separation_concentration_deepnets))


-----
## 2nd Tutorial: Graphs 

* Introduction to Graphs and applications w/ [NetworkX](https://networkx.org/)

This content is largely based on

* ["Complessita' nei sistemi sociali"](https://github.com/lordgrilo/complexity-book) course at UniTo
* [NetworkX Gallery Examples](https://networkx.org/documentation/stable/auto_examples/index.html)

More in detail: 

* Create an empty graph, adding nodes and edges and drawing
* Graph properties: Eccentricity, Radius, Diameter, Center, Periphery, Density, Average Shortest Path
* Centrality Measures: Degree, Betweenness, Closeness, PageRank
* Random Walks & PageRank
* Clustering & Community Detection
* Beam Search 
* Disparity Filtering 


----
## 3rd Tutorial: Manifolds

* Introduction to Manifolds and applications w/ [Geomstats](https://geomstats.github.io/)

* To get an idea of the motivations behind learning about and on manifolds, please take a look at [this](https://github.com/geomstats/geomstats/blob/master/notebooks/00_foundations__introduction_to_geomstats.ipynb) awesome notebook from Adele Myers and collaborators :)
* Also, for some more definitions, there is [this](https://github.com/geomstats/geomstats/blob/master/notebooks/01_foundations__manifolds.ipynb) notebook

More in detail:

* Three different & intuitive definitions of a Manifold 
* An Example: the hypersphere
* Manifolds as a Class? w/ Geomstats
* The Parent Class: Manifold
* OpenSet and LevelSet
* VectorSpace
* ProductManifold
* What is a connection 
* 1st Example: EMG data and SemiPositiveDefinite Matrices 
* 2nd Example: Zachary's Karate Club and Hyperbolic Embeddings


-----

# Projects & Ideas



### [ARC Challenge](https://lab42.global/arc/) - Abstraction Reasoning Corpus
* [Core knowledge](https://lab42.global/arc/core-knowledge/) a short story
* Previous Edition on [Kaggle](https://www.kaggle.com/c/abstraction-and-reasoning-challenge)
* [Some notebooks](https://www.kaggle.com/competitions/abstraction-and-reasoning-challenge/code?competitionId=18329&sortBy=scoreAscending) with solutions
