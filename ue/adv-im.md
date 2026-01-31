---
layout: single
title: "Advanced Method in Image Processing"
sidebar:
  - title: "Teacher"
    text: |
      - Florence Tupin
      - Yann Gousseau
---

{% include sig.button %} {% include im.button %}

**Image acquisition / radiometry / color imaging / high dynamic range imaging (6h + 3h lab):**

This course introduces the fundamentals of image acquisition. A complete mathematical modeling of the acquisition process is presented, with particular emphasis on 2D sampling and precise noise modeling. Representations of color and the radiometric content of images are detailed, along with a brief introduction to optimal transport. This section continues with several applications in computational photography, notably high dynamic range (HDR) imaging, and concludes with a practical lab session.

**Markov models and Bayesian analysis (3h):**

This course first provides an introduction to Markov models (definition, Gibbs sampling, and simulated annealing). We then show how these models can be used to perform basic image processing tasks such as classification or denoising on simple examples. An independent Jupyter Notebook lab assignment will be proposed and discussed at the beginning of the next session.

**Graph-cut-based optimization (3h):**

This course introduces the concept of minimum cut (min-cut) in graphs. We will then see how min-cut can be used to perform exact optimization in the case of binary image labeling (such as object/background classification). In a second part, we will cover the extension of this algorithm to multi-label situations with denoising applications. Approximate optimization and exact combinatorial optimization will be discussed, as well as the case of total variation minimization. Again, an independent Jupyter Notebook lab assignment will be proposed and discussed at the beginning of the next session.

**Patch-based and dictionary methods for image restoration (3h):**

This course introduces patch-based methods and describes the non-local means algorithm. Extensions to non-Gaussian noise and patch dictionaries will then be presented. The integration of patch-based approaches into deep learning methods will also be discussed.

**Deep learning strategies for image denoising (3h):**

In this course, we review several deep learning–based strategies for image denoising. We will mainly cover three families of approaches: plug-and-play methods, supervised methods, and self-supervised methods.

**Image editing: from patches to generative models (3h):**

In this course on image editing, we revisit the two families of methods previously introduced for image denoising: patch-based methods and deep learning methods. Particular emphasis will be placed on inpainting techniques, for both images and video. This specific application will also serve as an opportunity to introduce the most classical generative models: autoencoders, GANs, and diffusion models.
