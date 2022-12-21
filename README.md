# Symmetries
A couple of exercises on Geometric Deep Learning

### References 
* [Geometric Deep Learning Protobook](https://arxiv.org/abs/2104.13478)
* [A Wavelet Tour of Signal Processing](https://wavelet-tour.github.io/)


-----
## 1st Tutorial: Multiscale Representations and Wavelets

Taking inspiration from [Gabriel Peyre's Numerical Tours](https://github.com/gpeyre/numerical-tours)

In particular: 

* [Fourier & Wavelets](https://github.com/gpeyre/numerical-tours/blob/master/python/introduction_4_fourier_wavelets.ipynb) 
* [Image Denoising with Wavelets](https://github.com/gpeyre/numerical-tours/blob/master/python/denoisingwav_2_wavelet_2d.ipynb)

__[BONUS]__

We can eventually try to re-implement some matlab code on specific wavelet families: 
* https://wavelet-tour.github.io/softwares/ 
* [Here](http://www.laurent-duval.eu/siva-wits-where-is-the-starlet.html#bandlet) a collection of a large variety of geometric multiscale transforms 

The notion of wavelets and multiscale separation is also used to build neural networks (i.e. Scattering Networks) 
* See [Kymatio](https://www.kymat.io/) for some implementations 
* In general the work of Stephane Mallat's Lab both on [Scholar](https://scholar.google.fr/citations?hl=fr&user=g_YTmSgAAAAJ&view_op=list_works&sortby=pubdate) and Github (scattered among lab members, for example see [this](https://github.com/j-zarka/separation_concentration_deepnets))
