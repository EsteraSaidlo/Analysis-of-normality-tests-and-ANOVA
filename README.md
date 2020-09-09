# Analysis-of-normality-tests-and-ANOVA

The project consists of two parts:
1. Normality tests - power comparison
2. ANOVA

# Normality tests - power comparison
The assumption about normal distribution of variables is the basis of many classical modelling techniques, including variance analysis. 
In the first part, the following normality tests were analysed:
- Shapiro-Wilk test,
- Jarque-Ber test,
- Pearson test,
- Anderson-Darling test,
- Lilliefors test,
- SJ test.

They have been tested on the basis of such distributions as:
- t-Student distribution,
- uniform distribution,
- exponential distribution.

Hypotheses concerning selected normality tests were created based on available knowledge and density function charts.

# ANOVA
The analysis of variance allows to examine the impact of qualitative data on a quantitative or interval variable. Thanks to multi-factor ANOVA we can check the effect of interaction - simultaneous influence of several factors on the explained variable. With the help of post-hoc tests it is possible to check between which variables there are interactions. And by examining the strength of experimental effects it is possible to find out to what extent the analysis of variance explains the occurring relationships. 

In this part, an analysis of variance was carried out based on data concerning apartment prices. The following variables were taken into account:
- number of rooms,
- the district where the apartment is located,
- type of building.


# Technology
- R
