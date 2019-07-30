# Computing-L1-type-estimators-in-linear-regression-using-modern-linear-programming-solvers-with-impl
Graduation project in python

In linear regression, L1-norm-based regression estimators are usually preferred to the commonly used least-squares estimator 
when the error terms in the model contain outliers or the variance of the error distribution is unbounded. 
Typical L1-norm-based regression estimators include the least absolute deviation estimator, quantile regression estimator and 
rank regression estimator. All these estimators are obtained by minimizing the sum of L1 norms of some linear functions of the regression 
parameter. The associated L1-type minimization problem is a popular convex optimization problem, nowadays and particularly so, 
since we are exposed to much more complex data sets. In this project, we aim to identify a relatively efficient way to solve such L1-type 
minimization problems on personal computer, and discuss potential improvements after a series of comparisons under three different methods 
of regression analysis. We apply two popular linear programming solvers, GUROBI and Glop, to solve the minimization problems using two 
different methods, each under two linear programming formulations. The efficiencies of these solvers under different settings are compared 
based on computation time and consumption of random-access memory (RAM). Through the comparisons, 
we draw a couple of interesting conclusions and discuss potential improvements by analysing the reasons underpinning these results.

