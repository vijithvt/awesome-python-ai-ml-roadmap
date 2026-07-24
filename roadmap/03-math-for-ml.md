# Stage 3 — Math for Machine Learning

**Time:** 4–8 weeks, concurrent with coding  
**Goal:** understand model behavior and diagnostics—not memorize proofs.

## Learn by implementation

| Area | Minimum useful knowledge | Implement |
| --- | --- | --- |
| Linear algebra | vectors, matrices, dot products, norms, projections, eigen/SVD intuition | linear regression and PCA |
| Calculus | derivatives, partial derivatives, chain rule, gradients | gradient descent |
| Probability | conditional probability, Bayes rule, common distributions, expectation | Naive Bayes |
| Statistics | sampling, estimators, intervals, tests, bias/variance | bootstrap interval |
| Optimization | loss, regularization, convexity intuition, learning rate | logistic regression |

## Selected resources

- [Mathematics for Machine Learning](https://mml-book.github.io/) — free companion
  book; use relevant chapters, not necessarily cover to cover
- [3Blue1Brown: Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra)
- [Seeing Theory](https://seeing-theory.brown.edu/) for probability intuition
- [Khan Academy statistics and probability](https://www.khanacademy.org/math/statistics-probability)

## Exercises

1. Calculate cosine similarity and explain when magnitude is discarded.
2. Visualize how a matrix transforms a grid.
3. Derive and numerically check the gradient of mean squared error.
4. Implement batch gradient descent and plot loss for three learning rates.
5. Simulate the law of large numbers.
6. Use Bayes rule for a screening-test scenario; distinguish sensitivity and precision.
7. Bootstrap a confidence interval and compare it with a parametric interval.
8. Demonstrate overfitting by increasing polynomial degree.
9. Use SVD for low-rank image approximation.
10. Explain L1 versus L2 regularization geometrically and experimentally.

## Checkpoint

Implement linear regression, logistic regression, and PCA using NumPy (no
scikit-learn model implementations). Compare with library results and document
numerical differences.

**Exit criteria:** connect a loss function to an optimization process; select an
evaluation estimate; diagnose under/overfitting; explain uncertainty honestly.
