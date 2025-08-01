# blockhouse_assignment
Problem 1: Need to model g<sub>t</sub>(x) using the data given in DATA folder </br>
Problem 2: Come up with an algorithm to find x<sub>i</sub>'s to minimize the $\sum_{i=1}^{N} g_i(x_i)$ such that $\sum_{i=1}^{N} x_i = S$

# Problem 1
In `modeling.ipynb`, I plotted the graph for $g_t(x)$ at t=13:30 and t=17:30 by combining the data from all 3 tickers. </br>
The plot is saved in `gt_graph_at_1330_1730.png`. It can be seen that $g_t(x)$ increases in a linear fashion. </br>
In `q1.ipynb`, I modeled $g_t(x)$ as $\beta_{t} * x$ and using linear regression, found the values of $\beta_{t}$ which are saved in `linearized_impact_coefficients.csv` </br>

# Problem 2
We can thus formulate the problem of finding $x_i$'s as LP problem and can use any LP solver to compute them </br>
find more in `q2.pdf`
