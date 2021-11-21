# Krishna Naidoo - Github Repository

Hi, I'm a postdoc at the Center for Theoretical Physics at the Polish Academy of Sciences (CFT PAN) in Warsaw. I work broadly in the area of cosmology working on the cosmic web and high order statistics method such as the minimum spanning tree (for which I developed the python library mistree) and constrained simulations of the local universe.

I love to write code and find myself continuously developing new libraries and analysis pipelines. This is driven by a desire to know how things work and to exploit this knowledge for performance and to push beyond the boundaries of existing status quo software.

I've written a bunch of software libraries which are in various stages of development, you may find some of these useful in your own work. A brief guide on what's available and their various stages of development and future plans are provided below.

### Peer-reviewed libraries

* [MiSTree](https://github.com/knaidoo29/mistree) - A python package for constructing and analysing minimum spanning trees.

### Research libraries

These are libraries which I have spent a considerable amount of time developing and have appeared in some of my research work (paper's and PhD thesis).

> #### General

* [twofast](https://github.com/knaidoo29/twofast)[^1] - Two point correlation function estimator in c++ with OpenMPI parallelisation and python management class for generating input files and running it.

> #### Cosmology

* [pyGenISW](https://github.com/knaidoo29/pyGenISW) - Computes the Integrated Sachs-Wolfe using spherical Bessel transforms for data provided in healpix redshift slices.
* [TheoryCL](https://github.com/knaidoo29/TheoryCL) - Computing auto- and cross-angular power spectra (cl)s for sources in the late universe.

### Libraries in development


* [fiesta](https://github.com/knaidoo29/fiesta)[^2] - A python library for interpolating fields in 1 to 3 dimensions.
* [knpy](https://github.com/knaidoo29/knpy) - Personal python library.
* [magpie](https://github.com/knaidoo29/magpie)[^2] - A python library for remapping pixels into different projections.
* [MPIutils](https://github.com/knaidoo29/MPIutils) - A python library for interacting with mpi4py and running basic MPI operations.
* [shift](https://github.com/knaidoo29/shift)[^2] - A python library for performing Fourier transforms defined in polar and spherical polar coordinates.

### Footnotes

[^1]: This is a brute force two point estimator with MPI parallelisation. Future releases (probably moving to new software) will work to make this more optimised by limiting the number of pairs of points which are cycled through.
[^2]: Heavy development with a plan to publish with peer-review in the future.
