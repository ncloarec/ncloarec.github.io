---
layout: page
title: Projects
permalink: /projects/
---

Below are some select projects or homework I found interesting to share.

## On the Gaussian Wigner matrix
*Course :* [Random Matrix Theory](http://math.ens-paris-saclay.fr/version-francaise/formations/master-mva/contenus-/theorie-des-matrices-aleatoires-et-apprentissage-214242.kjsp?RH=1242430202531),
 prof. [Jamal Najim](http://www-syscom.univ-mlv.fr/~najim/).

 The purpose of this homework is to study asymptotic spectral properties of the *gaussian Wigner matrix*,
 where entries correspond to *iid* centered complex valued gaussian variables such
 that the final matrix is hermitian.


 While the spectrum of a large random matrix is itself random and at first
  supposed to be complicated, its behavior stabilizes when the
 dimension of the underlying matrices tends to infinity, eventually tending
 towards a completely deterministic spectrum.

 * [Subject](../PDF/projects/RMT/HW1.pdf)
 * [Solution](../PDF/projects/RMT/HW1_CLOAREC_ROUSSEAU.pdf)
 * [GitHub](https://github.com/ncloarec/RMT_HW1)

## Online Learning and sleeping regret
*Course :* [Prediction for individual sequences](http://pierre.gaillard.me/teaching/mva.html),
 prof. [Rémi Bardenet](http://pierre.gaillard.me/).

 The purpose of this homework is to study some properties of online learning
 algorithms such as **prod algorithm** in a context of a finite decision set where only a subset of active decisions is available at each time *t* while the other decisions are sleeping and cannot be chosen.

* [Subject](../PDF/projects/MVA/Online_Learning/Subject.pdf)
* [Solution](../PDF/projects/MVA/Online_Learning/Homework.pdf)

## Frank-Wolfe Bayesian Quadrature
*Course :* [Bayesian statistics](https://www.ensae.fr/courses/statistique-bayesienne/),
 prof. [Rémi Bardenet](https://rbardenet.github.io/).

The purpose of this project is to study and implement the paper from [Francois-Xavier Briol et al.](https://arxiv.org/abs/1506.02681).

It focuses on the problem of **probabilistic integration** interpreting the numerical
 integration problem as a *statistical inference problem*. The impressive result
 exposed in this paper is clearly the super fast exponential convergence to the true value of the integral compared to the other methods such as *Monte Carlo*, *Quasi Monte
 Carlo* or *Kernel Herding*.

* [Report](../PDF/projects/FWBQ_report.pdf)
* [GitHub](https://github.com/ncloarec/FWBQ_project)


## Visualizing and understanding convolutional networks
*Course :* [Object recognition and computer vision](https://www.di.ens.fr/willow/teaching/recvis18/), prof. [Ivan Laptev](https://www.di.ens.fr/~laptev/).

![architecture](/assets/images/architecture.svg)

The purpose of this project was to study and implement the paper from [Zeiler et al.](https://arxiv.org/abs/1311.2901).

It focuses on understanding intermediate feature layers that have been learned by convolutional neural networks during the training part using **deconvolution to project the feature activations back to the input pixel space** in order to *identify the input stimuli that excite individual feature maps at any layer in the model*.

* [Report](../PDF/projects/Deconv_net_report.pdf)


## Matrix completion by singular value thresholding

*Course :* [High-dimensional statistics](http://www.ensae.fr/courses/statistique-en-grande-dimension/), prof. [Alexandre Tsybakov](http://www.crest.fr/pagesperso.php?user=2891)

The purpose of this homework is to study some properties about *soft-thresholding*,
 *hard-thresholding* estimators for low-rank matrix estimation.

We also show a [trace inequality](https://en.wikipedia.org/wiki/Trace_inequality) due to Von Neumann in the first problem.

* [Subject](../PDF/projects/tsybakov/HW4.pdf)
* [Solution](../PDF/projects/tsybakov/HW4_Nicolas_CLOAREC.pdf)
* [GitHub](https://github.com/ncloarec/HW4_Tsybakov)

## Singular values and sparcity

*Course :* [High-dimensional statistics](http://www.ensae.fr/courses/statistique-en-grande-dimension/), prof. [Alexandre Tsybakov](http://www.crest.fr/pagesperso.php?user=2891)

The purpose of this homework is to give an inequality for singular
 values in the context of sparcity, e.g with a constraint on the number of non-null
 coefficients.

We also show that set of least squares solutions for a regularized optimization
problem involving a convex function in the regularization term define an
[affine space](https://en.wikipedia.org/wiki/Affine_space) with the kernel of the
feature matrix as direction.

* [Subject](../PDF/projects/tsybakov/HW3.pdf)
* [Solution](../PDF/projects/tsybakov/HW3_Nicolas_CLOAREC.pdf)
* [GitHub](https://github.com/ncloarec/HW3_Tsybakov)

## On soft and hard thresholding estimators

*Course :* [High-dimensional statistics](http://www.ensae.fr/courses/statistique-en-grande-dimension/), prof. [Alexandre Tsybakov](http://www.crest.fr/pagesperso.php?user=2891)

The purpose of this homework is to study some properties about *soft-thresholding*,
 *hard-thresholding* and *Dantzig* estimators.

We also give an oracle inequality in probability in the context of sparcity for
the *soft-thresholding* estimator.

* [Subject](../PDF/projects/tsybakov/HW2.pdf)
* [Solution](../PDF/projects/tsybakov/HW2_Nicolas_CLOAREC.pdf)
* [GitHub](https://github.com/ncloarec/HW2_Tsybakov)

## Linear model and high dimension

*Course :* [High-dimensional statistics](http://www.ensae.fr/courses/statistique-en-grande-dimension/), prof. [Alexandre Tsybakov](http://www.crest.fr/pagesperso.php?user=2891)

The purpose of this homework is to study some properties about *least squares
estimators* for **misspecified models**.

We also give a proof of the *Hoeffding's lemma* for a bounded random
variable and show properties of [sub-gaussian variables](https://en.wikipedia.org/wiki/Sub-Gaussian_distribution).

* [Subject](../PDF/projects/tsybakov/HW1.pdf)
* [Solution](../PDF/projects/tsybakov/HW1_Nicolas_CLOAREC.pdf)
* [GitHub](https://github.com/ncloarec/HW1_Tsybakov)


## On the divisor graph

The purpose of this project was to work on the asymptotic properties of the
divisor graph introduced by [Paul Erdös and Eric Saias](http://matwbn.icm.edu.pl/ksiazki/aa/aa73/aa7324.pdf).

![](/assets/images/graph1.svg) ![](/assets/images/graph2.svg)

*Two different representation of the divisor graph for n=9.*


* [Slides introduction](../PDF/projects/tipe/tipe.pdf)
* [Slides implementation](../PDF/projects/tipe/info.pdf)
* [Code](https://github.com/ncloarec/TIPE)

## 4th International Tournament of Young Mathematicians

After a national selection during the [French National Tournament of Young Mathematicians](https://tfjm.org) which took place at [Ecole Polytechnique](https://www.polytechnique.edu/en) (*April 2012*), member of the french team to represent France at the [4th International Tournament of Young Mathematicians](http://www.itym.org/) (*July 2012*).

Supervisors for the french team :
* [Gabriel Dospinescu](http://perso.ens-lyon.fr/gabriel.dospinescu/)
* [Emmanuel Lecouturier](https://webusers.imj-prg.fr/emmanuel.lecouturier)

Here are the problems for this 4th edition :
* [Problems](../PDF/projects/ITYM/Problems-ITYM2012.pdf)

Problems are generally published in mid-march and students have several weeks to work on it. I personally have chosen to focus on the three following :
* [Problem1](../PDF/projects/ITYM/ITYM2012-Probleme1.pdf)
* [Problem2](../PDF/projects/ITYM/ITYM2012-Probleme2.pdf)
* [Problem5](../PDF/projects/ITYM/ITYM2012-Probleme5.pdf)
