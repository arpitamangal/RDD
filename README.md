# Experimental Design and Analysis
### Projects to establish causality and draw reliable conclusions from experimental data.

Experimental design involves designing the experiment in a way that minimizes the effects of extraneous variables and maximizes the internal validity of the results. This includes identifying the research question, selecting the sample, determining the experimental conditions, and establishing the methods of data collection.

Analysis of the data obtained from the experiment involves applying statistical tests and other analytical techniques to determine the significance of the observed differences between the experimental conditions. This process aims to determine the causal effects of the independent variables on the dependent variables, while controlling for the effects of confounding variables.

# Should the legal age for drinking be reduced from 21?
The code implements a regression discontinuity design (RDD) to answer the above question.
* Determines if alcohol increases the chances of death by 
  - accident
  - suicide
  - others
* Comprehends the trade-offs of choosing different bandwidths for the design. Bandwidth used: 
  - 1 year (i.e., 21 +- 1).
  - 6 months (i.e., 21 +-0.5).
  - maximum (i.e. entire data).
  
Inference: 
There is a correlation between deaths above and below the legal drinking age, but we cannot conclude that the age limit causes these deaths, as there may be other confounding factors unrelated to alcohol. If alcohol is indeed the cause, lowering the drinking age would not solve the problem and could lead to a similar issue with younger age groups. Before making any conclusions, we need to account for confounding factors, identify true treatment effects, and take informed decisions.

Dataset: "drinking.csv"


