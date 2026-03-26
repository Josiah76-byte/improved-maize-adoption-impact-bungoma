# improved-maize-adoption-impact-bungoma
Impact evaluation of improved maize variety adoption on farm productivity in Bungoma using endogenous switching regression and spatial analysis.

# Overview
This project estimates the causal effect of adopting improved maize varieties on farm productivity. It addresses selection bias using an endogenous switching regression framework and tests for spatial dependence in adoption decisions.

# Data
Cross-sectional farm household data from Bungoma County, including production outcomes, adoption status, household characteristics, and geolocation variables.

# Sampling design
Multi-stage sampling approach
First stage, Bungoma was selected based on maize production relevance
Second stage, sub-counties and wards selected purposively
Third stage, villages selected randomly
Final stage, households selected using systematic random sampling from village lists

Sample size
Total sample: 720 farm households
Adopters: 235
Non-adopters: 485

# Data collected
Maize productivity (output per ha)
Adoption status of improved maize varieties
Household demographics
Farm and input use characteristics
Market access variables
GPS coordinates for spatial analysis

# Methods
Endogenous Switching Regression to correct for selection bias
Estimation of ATT and ATU
Decomposition of heterogeneity effects
Moran’s I statistic for spatial autocorrelation

# Key Results
Adoption is driven by economic capacity and market access. Education and income increase adoption probability. Distance to markets reduces participation, suggesting transaction costs. Household size shows a negative effect, which may reflect resource constraints. Demand-side preference, captured by willingness to pay, plays a strong role.
ATT: 0.053, about a 5.44 percent increase in productivity
ATU: 0.014, about 1.40 percent potential gain
Heterogeneity effect: 0.039, statistically significant
Moran’s I: 0.001, p = 0.389, no spatial clustering in adoption

# Interpretation
Adoption leads to statistically significant productivity gains. Higher returns among adopters indicate positive selection. Non-adopters face constraints that limit both adoption and realized gains. Adoption decisions are not spatially correlated within the defined distance band.

# Policy relevance
Reduce market access barriers
Expand credit and input financing
Invest in farmer education and demonstrations
Use demand-side incentives to increase uptake
Target women and resource-constrained households
Design interventions that account for farmer heterogeneity

# Tools

Stata for econometric analysis
movestay for ESR estimation
Spatial analysis tools for Moran’s I
