---
excerpt: '

<br/> 

__If you are interested in any of the following projects, feel free to contract me for a collaboration.__ 

- - - 

<br/>


__Automatic problem reduction using machine learning__ [[IEEE TPAMI](https://yuansuny.github.io/files/Jpaper_MLPR.pdf), [OR Spectrum](https://arxiv.org/pdf/2005.05847.pdf)] <br/>
In the big data era, the size of many real-world combinatorial optimisation problems has increased significantly over the years, making the problems very hard to solve. This project aims to develop innovative problem reduction methods using machine learning to reduce the size of large-scale combinatorial optimisation problems so that the reduced problems can be solved by existing optimisation algorithms.

![](https://yuansuny.github.io/images/MLPR_training.png)


- - - 

<br/>


* __Boosting Meta-heuristics via Solution Prediction and Machine Learning__ (To apprear) <br/>
As a proof of concept, we integrate machine learning with ant colony optimization (ACO) to solve a combinatorial optimization problem. Our machine learning model trains on a set of optimally-solved problem instances, and predicts for a test instance which decision variables are more likely to be part of an optimal solution. We explore multiple ways of incorporating this solution prediction into the probabilistic model of ACO to bias its sampling towards using predicted high-quality decision variables more often, when constructing feasible solutions. We empirically show that our machine learning prediction significantly speeds up ACO in finding high-quality solutions, and outperforms other quality measure directly computed from problem characteristics.  Our model is robust in the sense that 1) it is fairly insensitive to the learning algorithm used in training; and 2) it generalizes well to large and real-world problem instances.

* __Revisiting Probability Distribution Assumptions for Information Theoretic Feature Selection__ [[outcome](https://yuansuny.github.io/files/Cpaper_PDA.pdf)] <br/>
Feature selection has been shown to be beneficial for many data mining and machine learning tasks, especially for big data analytics. Mutual Information (MI) is a well-known information-theoretic approach used to evaluate the relevance of feature subsets and class labels. However, estimating high-dimensional MI poses significant challenges. Consequently, a great deal of research has focused on using low-order MI approximations or computing a lower bound on MI called Variational Information (VI). These methods often require certain assumptions made on the probability distributions of features such that these distributions are realistic yet tractable to compute. In this project, we revealed two sets of distribution assumptions underlying many MI and VI based methods: Feature Independence Distribution and Geometric Mean Distribution. We systematically analyzed their strengths and weaknesses and proposed a logical extension called Arithmetic Mean Distribution, which leads to an unbiased and normalised estimation of probability densities. We conducted detailed empirical studies across a suite of 29 real-world classification problems and illustrated improved prediction accuracy of our methods based on the identification of more informative features, thus providing support for our theoretical findings.

* __Decomposition Methods for Large-scale black-box continuous optimization problems__ [[outcome](https://yuansuny.github.io/files/Jpaper_RDG.pdf)] <br/>
Cooperative Co-evolution (CC) is an evolutionary computation framework that can be used to solve high dimensional optimization problems via a ‘divide-and-conquer’ mechanism. However, the main challenge when using this framework lies in problem decomposition. That is, deciding how to allocate decision variables to a particular sub-problem, especially interacting decision variables. Existing decomposition methods are typically computationally expensive, taking $O(n^2)$ function evaluations when decomposing an n-dimensional problem. In this project, we propose a new decomposition method, which we call Recursive Differential Grouping (RDG), by considering the interaction between decision variables based on non-linearity detection. RDG recursively examines the interaction between a selected decision variable and the remaining variables, placing all interacting decision variables into the same sub-problem. We use analytical methods to show that RDG can be used to efficiently decompose an n-dimensional problem using $O(n \log n)$ function evaluations, without explicitly examining all pairwise variable interactions. We evaluated the efficacy of the RDG method using large scale benchmark optimization problems. Numerical simulation experiments showed that RDG greatly improved the efficiency of problem decomposition in terms of time complexity. Significantly, when RDG was embedded in a CC framework, the optimization results were better than results from seven other decomposition methods.





'

---
