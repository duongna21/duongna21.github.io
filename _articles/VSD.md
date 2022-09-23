---
title: "Structured Dropout Variational Inference for Bayesian Neural Networks"
category: articles
permalink: "/articles/VSD/"
venue: "Advances in Neural Information Processing Systems (NeurIPS)"
date: 10-12-2021
link: https://papers.nips.cc/paper/2021/hash/80a160ff31266be2f93012a2a3eca713-Abstract.html
---
[comment]: 
Son Nguyen\*, <b>Duong Nguyen</b>\*, Khai Nguyen, Khoat Than, Hung Bui\*, Nhat Ho\*

Abstract: Approximate inference in Bayesian deep networks exhibits a dilemma of how to yield high fidelity posterior approximations while maintaining computational efficiency and scalability. We tackle this challenge by introducing a novel variational structured approximation inspired by the Bayesian interpretation of Dropout regularization. Concretely, we focus on the inflexibility of the factorized structure in Dropout posterior and then propose an improved method called Variational Structured Dropout (VSD). VSD employs an orthogonal transformation to learn a structured representation on the variational Gaussian noise with plausible complexity, and consequently induces statistical dependencies in the approximate posterior. Theoretically, VSD successfully addresses the pathologies of previous Variational Dropout methods and thus offers a standard Bayesian justification. We further show that VSD induces an adaptive regularization term with several desirable properties which contribute to better generalization. Finally, we conduct extensive experiments on standard benchmarks to demonstrate the effectiveness of VSD over state-of-the-art variational methods on predictive accuracy, uncertainty estimation, and out-of-distribution detection. 