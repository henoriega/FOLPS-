# Fast One Loop Power Spectrum in the presence of massive neutrinos (FOLPSν)

**Author**: Hernán E. Noriega

Email: henoriega@estudiantes.fisica.unam.mx

**Other people who contributed to this code**:
- Alejandro Aviles
- Sebastien Fromenteau
- Mariana Vargas Magaña

#
This code ......
### Requirements:
**Requirements:** 

- numpy (update your numpy to versions ≥ 1.20.0)
- scipy


FOLPSν (still in development) is a code for efficiently evaluating the redshift-space power spectrum in the presence of massive neutrinos.
The code is based on the FFTLog formalism (https://arxiv.org/abs/1603.04826, https://arxiv.org/abs/1603.04405) and computes the one-loop power spectrum from [Eulerian Perturbation Theory](https://arxiv.org/abs/astro-ph/0112551), incorporating into the model some standard ingredients such as non-linear bias, Infrared resummations, and Effective Field Theory counterterms.

**Remark:** FFTLog matrices and vectors do not depend on the cosmological parameters, so they only need to be computed once!



Attribution
-----------

Please cite `Foreman-Mackey, Hogg, Lang & Goodman (2012)
<https://arxiv.org/abs/1202.3665>`_ if you find this code useful in your
research. The BibTeX entry for the paper is::

    @article{emcee,
       author = {{Foreman-Mackey}, D. and {Hogg}, D.~W. and {Lang}, D. and {Goodman}, J.},
        title = {emcee: The MCMC Hammer},
      journal = {PASP},
         year = 2013,
       volume = 125,
        pages = {306-312},
       eprint = {1202.3665},
          doi = {10.1086/670067}
    }
