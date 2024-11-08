java c
Problem Set 3 
Applied Econ 440.602: Macroeconomic Theory 
Fall, 2024 
1. Firm Taxes in the Neoclassical Growth Model. In class, when we analyzed taxes in the neo-classical growth model, we assumed that all taxes were levied on households. In this problem, we’ll consider a mix of taxes levied on households and taxes levied on firms. Unless otherwise stated, the notation is the same as what we used in class.
There is a representative household that owns capital, supplies labor, and consumes goods. The household’s lifetime utility function is:

where 0 < β < 1 is the discount factor, u (·) is increasing and concave, and v (·) is increasing and convex. The household pays two forms of taxes: consumption taxes and lump-sum taxes. That is, the household owes τh+τcCt in taxes each period, where τh is the lump-sum tax, and τc is the consumption tax rate. (For simplicity, the tax parameters are assumed to be constant across time.) The household’s date-t budget constraint is:
wtNt + rtKt = (1 + τc) Ct + It + τh.                                                   (2)
The household’s capital stock evolves according to the law of motion Kt+1 = It + (1 − δ) Kt.
There is a representative firm that produces output using the production function Yt = F (Kt, Nt). The firm must pay taxes on capital that it rents and the labor that it hires. In particular, if the firms spends rtKt renting capital, then it must pay τkrtKt to the government, and if the firm spends wtNt on hiring labor, then it must pay τnwtNt to the government. (Again, assume the tax rates are constant.) After taxes, the firm’s date-t profits are therefore:
F (Kt, Nt) − (1 + τk) rtKt − (1 + τn) wtNt.                                                     (3)
Assume that F (·, ·) is increasing and concave in each argument, and homogeneous of degree one. The capital-labor ratio is denoted kt ≡ Kt/Nt. We can write output as F (Kt, Nt) = f (kt) Nt, where f (k) ≡ F (k, 1) is increasing and concave.
The government purchases a constant amount of goods G each period. Assume that the govern-ment runs a balanced budget each period, so G = τh + τcC + τkrtKt + τnwtNt.
Given initial capital K0 and a fiscal policy (τh, τc, τn, τk, G), an equilibrium is an allocation {Ct, Nt, Kt+1}∞t=0 and a price system {rt, wt}∞t=0 such that: (i) the allocation solves the household’s problem, given prices and fiscal policy, (ii) the allocation solves the firm’s problem, given prices and fiscal policy, (iii) the government’s budget constraint is satisfied, and (iv) markets clear, meaning that Yt = Ct + It + G.
(a) Write down the household’s Lagrangian. What are the first-order conditions with respect to Ct, Nt, and Kt+1?
(b) Combine the household’s first-order conditions to eliminate any Lagrange multipliers.
(c) Assume that, each period, the representative firm chooses capital and labor to maximize profits. What are the first-order conditions with respect to Kt and Nt?
(d) Show that, in an equilibrium, the representative firm earns zero after-tax profits.
(e) Show that the market-clearing condition Yt = Ct + It + G is implied by the other equilibrium conditions.
(f) For the remainder of the problem, assume that a steady-state equilibrium exists, and the economy is in a steady-state. That is, all prices and quantities are constant. Denote steady-state allocations and prices by dropping time subscripts and adding bars to each variable. For example, steady-state consumption is denoted C¯. Each of the following questions a代 写Econ 440.602: Macroeconomic Theory Fall, 2024 Problem Set 3C/C++
代做程序编程语言llows you to work through some comparative statics, to see how steady-state outcomes change when the parameters of fiscal policy change. For the remainder of the problem, you can assume the functional forms:

Solve for the steady-state capital-labor ratio k¯ in terms of the model’s parameters. How does k¯ depend on each of the tax parameters τh, τc, τn, and τk? That is, when each of the τ parameters increases, does k¯ go up or down? Explain how you know mathematically.
(g) How does C¯ depend on each of the tax parameters τh, τc, τn, and τk? That is, when each of the τ parameters increases, does C¯ go up or down? Explain how you know mathematically. (Hint 1: Combine equilibrium conditions, evaluated in a steady state, to write N¯ as a function of C¯ and k¯. Hint 2: Combine equilibrium conditions, evaluated in a steady-state, to arrive at a single equation that implicitly characterizes C¯, given k¯.)
(h) How does N¯ depend on each of the tax parameters τh, τc, τn, and τk? That is, when each of the τ parameters increases, does N¯ go up or down? Explain how you know mathematically.
(i) Suppose that G goes up. Do C¯, N¯, k¯, and Y¯ go up, down, or remain the same? Explain how you know mathematically.
2. Measuring Convergence. One implication of the Solow model that we derived is convergence: If kt starts out below its steady-state level, then it will converge upward until it reaches the steady state, and if kt starts out above its steady-state level, then it will converge downward until it reaches the steady state. (The neoclassical growth model has the same implication, although we didn’t show it explicitly.) Consequently, one would expect relatively less-developed economies to grow faster than more developed economies. Blanchard presents some evidence of convergence in relatively wealthy countries. This exercise will have you look at the evidence of convergence across regions within a country. On Canvas, there is a dataset containing real per capital income for each of the 50 states in the union, between 2000 and 2023 that you should use to answer these questions. Throughout, let yi,t denote the natural log of real per capital income in state i in year t. (The data on Canvas are in 2017 dollars, so you’ll have to take logs yourself.) We’ll look at two ways of quantifying convergence, one called β-convergence and one called σ-convergence.
(a) Let gi denote the growth rate of real per capita income over the sample period for country i:

i. Consider the following regression, of the long-run growth rate on the initial level of income:
gi = α + β × yi,2000 + ϵi,                                              (8)
where ϵiis a residual that is uncorrelated with yi,2000. States are said to exhibit β-convergence if β > 0. Explain why β > 0 means that income differences between states are declining.
ii. Produce a scatter plot with yi,2000 on the horizontal axis and gi on the vertical axis.
iii. Using the state-level data, estimate the regression in equation (8). What is the estimated value of β, and what is the associated standard error?
iv. Do your results support the conclusion that per capita income levels are converging across states?
(b) Let σt denote the standard deviation of yi,t across states at date t:

States are said to exhibit σ-convergence if σt is declining over time. Plot σt across years. Do your results support the conclusion that per capita incomes are converging across states?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
