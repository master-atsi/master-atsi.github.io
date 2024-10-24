---
layout: single
title: "Inverse problems"
sidebar:
  - title: "Teacher"
    text: |
      - Thomas Rodet
      - Charles Soussen
  - title: "Hours"
    text: "18h CM + 9h TD-TP"
---

{% include sig.button %} {% include im.button %} {% include stat.button %}

A large part of signal processing can be seen from the point of view of inversion,
in the sense that the observations are partly informative on the quantity to be
estimated and the estimation is also based on physical models. In various
applications such as astrophysics, biomedical engineering, industrial monitoring
or remote sensing, the direct use of measurements is not always satisfactory.
Inversion methods make possible to take into account distortions introduced by
the measuring devices in order to reconstruct the quantity of interest. This
course addresses ill posed inverse problems, for which the observed data are
insufficient to reliably reconstruct the object of interest. Regularization
techniques are then necessary to solve these difficult problems. We introduce
two major families of methods. On the one hand variational approach, based on
the construction and optimization of a regularized cost function and on the
other Bayesian approach, based on the probabilistic modeling of the object to
be reconstructed and the errors of model. This latter approach leads to
unsupervised methods for quantifying uncertainties. The different underlying
approaches and algorithms will be illustrated on different case studies (TP) such
as the restoration or reconstruction of signals and images with linear direct
models or not. Application areas related to these case studies will be biomedical
engineering, nondestructive testing or image processing in astrophysics.

## References

1. J. Idier. « Approche bayésienne pour les problèmes inverses , Traité IC2, Série traitement du signal et de l'image, Hermès, Paris, nov. 2001.
2. J. F. Giovannelli et J. Idier, « Méthodes d'inversion appliquées au traitement du signal et de l'image », Hermès, Paris, nov. 2013.
3. J. Nocedal et S. J. Wright, « Numerical optimization », Springer texts in Operations Research and Financial Engineering, 2ème édition, Springer Verlag, New York, juil. 2006.
4. C. P. Robert, « Le choix bayésien », Coll. Statistique et probabilités appliquées, Springer, Paris, 2006.
5. V. Smidl et A. Quinn, « The variational Bayes method in signal processing », Springer, Berlin, 2006.
