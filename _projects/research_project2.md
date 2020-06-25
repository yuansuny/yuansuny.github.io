---
excerpt: '

* __Using Statistical Measures and Machine Learning for Problem Reduction__ ([paper1](https://yuansuny.github.io/files/Jpaper_MLPR.pdf), [paper2](https://arxiv.org/pdf/2005.05847.pdf)) <br/>
Combinatorial optimization plays an important role in real-world problem solving. In the big data era, the dimensionality of a combinatorial optimization problem is usually very large, which poses a significant challenge to existing solution algorithms. In this project, we investigate problem reduction techniques using stochastic sampling and machine learning to tackle large-scale optimization problems. These techniques heuristically remove decision variables from a problem instance, that are not expected to be part of an optimal solution. First, we investigate the use of statistical measures computed from stochastic sampling of feasible solutions compared with features computed directly from the instance data. Two measures are particularly useful for this: 1) a ranking-based measure, favoring decision variables that frequently appear in high-quality solutions; and 2) a correlation-based measure, favoring decision variables that are highly correlated with the objective values. To take this further, we develop a machine learning approach, called Machine Learning for Problem Reduction (MLPR), that trains a supervised learning model on easy problem instances for which the optimal solution is known. This gives us a combination of features enabling us to better predict the decision variables that belong to the optimal solution for a given hard problem. We have demonstrated the efficacy of our approaches on the maximum weight clique problem ([MWCP](https://yuansuny.github.io/files/Jpaper_MLPR.pdf)) and travelling salesman problem ([TSP](https://arxiv.org/pdf/2005.05847.pdf)). Our experimental results have shown that our problem reduction techniques are very effective and can be used to boost the performance of existing solution methods.



<!---
The aim of this project is to aggregate powerful techniques from different domains, e.g., machine learning, operations research and meta-heuristics, to tackle large-scale combinatorial optimization problems. So far, we have developed two pieces of work along this line: <br/>
1. We have used data mining and machine learning techniques to reduce the size of a given large problem. An existing solution method can then be used to solve the reduced problem. <br/>
1. We have used Lagrangian Relaxation to decompose a large mixed integer program into a series of easy problem instances that can be solved quickly. The Lagrangian dual problem is solved by meta-heuristics. <br/>
---!>



'

---
