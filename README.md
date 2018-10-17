# safetest
Validate the assumptions of tests before running them

# Purpouse

Some methods are more robust to violations of the assumptions.
This might mean that the results of a test are not conclusive.
The idea of this package is to check the assumptions for any given statisticall test.

# Assumptions

Common assumptions are:
- Following some distribution: normal, poisson... (in the residuals of models or in some tests)
- Same mean (ANOVA)
- No ties (ranking algorithms like fgsea)
- Randomness
