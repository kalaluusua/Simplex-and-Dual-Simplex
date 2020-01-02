# Simplex and Dual Simplex
Simplex and Dual Simplex are linear optimization algorithms, of which one operates in primal and other in dual space. In the case of primal Simplex, the algorithm is given a feasible solution and it halts when the solution is optimal or the optimal solution is infeasible. The dual Simplex on the other hand is given a primal infeasible solution, and the algorithm halts once the current solution is both primal and dual feasible (i.e. optimal), or if the optimal solution is infeasible. 

This repository contains both implementations with an option to apply Bland's rule to prevent cycling.
