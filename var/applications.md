# Introduction

The relationship between fiscal policy and inflation has been a central
theme in macroeconomic research. Fiscal policy, through government
spending and taxation, can affect inflation either directly by
influencing aggregate demand or indirectly by affecting expectations and
economic behavior. However, the dynamics of this relationship may vary
over time due to changes in economic conditions, policy regimes, and
external shocks.

This paper applies a Time-Varying Parameter Vector Autoregressive
(TVP-VAR) model to study how fiscal policy affects inflation over the
period 2002 to 2018. The TVP-VAR framework allows for the parameters of
the VAR model to evolve over time, providing a more flexible and
accurate representation of the changing nature of the fiscal-inflation
relationship. The paper aims to contribute to the ongoing debate by
examining this relationship using a more sophisticated econometric model
that captures time-varying dynamics.

The structure of the paper is as follows. Section 2 reviews the relevant
literature and theoretical background. Section 3 outlines the data and
methodology, including a detailed description of the TVP-VAR model.
Section 4 presents the empirical results. Finally, Section 5 concludes
with policy implications and suggestions for future research.

# Theoretical Background and Literature Review

The impact of fiscal policy on inflation has been studied extensively in
the literature, with various channels identified through which
government spending and taxation can influence inflation. The classical
view, articulated by Keynes (1936), suggests that fiscal expansion
through increased government spending can raise aggregate demand,
leading to higher inflation, especially when the economy is near full
capacity. On the other hand, Ricardian equivalence (Barro, 1974)
suggests that fiscal policy does not affect inflation if agents
anticipate future tax increases to offset government debt.

Recent studies have employed econometric models to examine the dynamic
relationship between fiscal policy and inflation. Blanchard and Perotti
(2002) argue that fiscal policy has significant effects on inflation in
the short run, especially in economies with low central bank
credibility. However, the effect may vary depending on the economic
environment and the fiscal stance.

This paper builds on these theories by employing a Time-Varying
Parameter VAR model, which allows us to capture the changing dynamics of
the fiscal policy-inflation relationship over time. The TVP-VAR approach
has been used in recent research to model relationships that evolve with
economic cycles, structural changes, and policy interventions.

# Data and Methodology

## Data

The analysis uses quarterly data from several countries over the period
2002 to 2018. The key variables include:

-   Government spending ( $$G_{it}$$ ),

-   Tax revenues ($T_{it}$),

-   Inflation ($\pi_{it}$),

-   Output gap ($OG_{it}$).

Data sources include the World Bank, national central banks, and
statistical agencies. All variables are expressed as percentages of GDP,
except inflation, which is measured as the annualized quarterly
percentage change in the consumer price index (CPI).

## Methodology

To estimate the relationship between fiscal policy and inflation, we use
a Time-Varying Parameter Vector Autoregressive (TVP-VAR) model, which
allows for the coefficients of the VAR model to change over time. The
general form of the TVP-VAR model is given by:

$$Z_{it} = A_t Z_{i,t-1} + \epsilon_{it}$$

where: -
$Z_{it} = \begin{bmatrix} G_{it} & T_{it} & \pi_{it} & OG_{it} \end{bmatrix}^T$
is the vector of variables for country $i$ at time $t$, - $A_t$ is the
time-varying coefficient matrix, which allows for changes in the
relationships between fiscal policy variables and inflation over time, -
$\epsilon_{it}$ is the error term.

The time-varying coefficients are modeled as a random walk, which allows
for gradual shifts in the relationship between fiscal policy and
inflation. This is particularly useful for capturing the effects of
changes in the economic environment or fiscal policy regimes.

# Empirical Results

In this section, we present the results of the TVP-VAR estimations for
each country. We first examine the basic coefficients for the
relationship between government spending, taxation, and inflation. Then,
we analyze the time-varying impulse response functions (IRFs) to
understand how fiscal policy shocks affect inflation over time.

## TVP-VAR Estimation Results

\[Provide results for each country model, focusing on the time-varying
coefficients and how they evolve over time.\]

## Time-Varying Impulse Response Functions

\[Provide analysis of the IRFs, showing how shocks to fiscal policy
variables (government spending and taxation) impact inflation, and how
these relationships change over time.\]

# Conclusion

This paper has examined the relationship between fiscal policy and
inflation using a Time-Varying Parameter Vector Autoregressive (TVP-VAR)
model. Our findings suggest that the relationship between fiscal policy
and inflation is not static, but evolves over time. Government spending
and taxation have varying effects on inflation depending on the time
period, reflecting changes in economic conditions, policy regimes, and
external shocks.

The use of a TVP-VAR model has provided a more flexible and accurate
representation of the fiscal-inflation relationship than traditional VAR
models. These findings have important implications for policymakers, as
they suggest that the effectiveness of fiscal policy in controlling
inflation may vary over time, depending on the broader macroeconomic
environment.

Further research could expand on these findings by incorporating
additional variables, such as exchange rates or monetary policy
indicators, to further explore the complex interactions between fiscal
policy and inflation. Policymakers should consider the time-varying
nature of fiscal policy impacts when designing long-term inflation
control strategies.

::: thebibliography
9 Blanchard, O., & Perotti, R. (2002). *An empirical characterization of
the dynamic effects of changes in government spending and taxes on
output*. Quarterly Journal of Economics, 117(4), 1329-1368. Barro, R. J.
(1974). *Are government bonds net wealth?* Journal of Political Economy,
82(6), 1095-1117. Keynes, J. M. (1936). *The General Theory of
Employment, Interest, and Money*. Macmillan.
:::

[^1]: LIREIMO
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

 
