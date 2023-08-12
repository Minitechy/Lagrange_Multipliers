## Lagrange_Multipliers_Code
All the Python code used to create the graphs shown in the main paper, along with numerical solutions, were utilized to validate the analytical solutions for the case study of the primary problem.
------------------------------------------------------------------------------------------------------

Code 1 is used to implement the generalized SLSQP Algorithm 1. The algorithm takes into account a budget constraint, requiring that all funds be invested in these _n_ stocks, and ensures that the proportion allocated to each stock is non-negative. Additionally, it considers a portfolio risk constraint. By providing input parameters such as the number of stocks to consider, their respective expected returns, standard deviations, and a predetermined risk tolerance, the algorithm can accurately determine the optimal allocation of funds.

Code 2 is utilized to generate Figure 1 that illustrates the relationship between the portfolio risk and the proportion of Stock _A_. This graph visually represents the impact of varying the allocation of Stock _A_ on the resulting portfolio risk.

Code 3 is employed to generate Figure 2 that visually represents the optimal proportions of Stocks _A_ and _B_ as a function of the portfolio risk tolerance. This graph provides valuable insights into the allocation strategy based on risk tolerance.

Code 4 is employed to generate Figure 3 depicting the maximum expected return of the portfolio  as a function of the correlation coefficient. This graph offers valuable insights into the influence of the correlation coefficient on the portfolio’s performance.

Code 5 is utilized to generate Figure 4 depicting the optimal proportions of Stocks _A_ and _B_ as a function of the correlation coefficient. This graph showcases the dynamic allocation strategies that evolve as the correlation coefficient changes.
