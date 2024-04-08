# Economic Freedom Index

### Introduction ###
The dataset measures 12 aspects of economic freedom, grouped into four broad pillars:
- Rule of law (property rights, judicial effectiveness, and government integrity);
- Government size (tax burden, government spending, and fiscal health);
- Regulatory efficiency (business freedom, labor freedom, and monetary freedom); and
- Market openness (trade freedom, investment freedom, and financial freedom).

1. Rule of Law:
   - Property Rights: the ability to accumulate private property and wealth. A key aspect of the protection of property rights is the enforcement of contracts.
   - Judicial Effectiveness: effective legal frameworks able to protect the rights of all citizens against infringement of the law by others, including infringement by governments and powerful parties.
   - Government Integrity: the lack of systemic corruption of government institutions by such practices as bribery, nepotism, cronyism, patronage, embezzlement, and graft.

2. Government Size:
   - Tax Burden: individual and corporate income tax rates are an important and direct constraint on an individual’s economic freedom and are reflected as such in the Index, but they are not by themselves a comprehensive measure of the tax burden. Governments impose many other indirect taxes, including payroll, sales, and excise taxes, as well as tariffs and value-added taxes (VATs). The Index of Economic Freedom captures the burden of these taxes by measuring the overall burden from all forms of taxation as a percentage of total gross domestic product (GDP).
   - Government Spending: the cost, size, and intrusiveness of government.
   - Fiscal Health: one of the clearest indicators of the extent to which a government respects the principle of limited government is its budget. Debt is an accumulation of budget deficits over time. In theory, debt financing of public spending could contribute to productive investment and economic growth. Debt could also be a mechanism for positive macroeconomic countercyclical interventions or even long-term growth policies. On the other hand, high levels of public debt can lead to higher interest rates, crowd out private investment, and limit government’s flexibility in responding to economic crises.
  
3. Regulatory Efficiency:
- Business Freedom: an individual’s ability to establish and run an enterprise without undue interference from the state.
- Labor Freedom: the ability of individuals to find employment opportunities and work.
- Monetary Freedom: a stable currency and market-determined prices.

4. Market Openness:
- Trade Freedom: lack of impediments to trade, which include tariffs, export taxes, trade quotas, outright trade bans, and nontariff barriers related to various licensing, standard-setting, and other regulatory actions.
- Investment Freedom: freedom on the movement of capital, whether domestic or international.
- Financial Freedom: availability of diversified savings, credit, payment, and investment services to individuals and businesses. 

---

### Project ###

The following project focuses on the analysis of the indicators previously examined. In particular, it is comprised of:
- A data visualization part, in which different regions are compared based on different indicators, and the relationship between the variables are explored in the form of plots.
- An outlier detection part, where some instances, corresponding to peculiar countries, are uncovered as outliers, examined and, in some cases, removed. In this step, the predictors are also trasnformed to a more normal distribution.
- A Principal Component Analysis, which suggests through a biplot that the indicators Tax Burden, Government Spending and Fiscal Health can be set apart from the other indicators.
- A cluster analysis, where variables are clustered through hierarchical methods
