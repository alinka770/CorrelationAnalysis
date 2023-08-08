# CorrelationAnalysis
The purpose of my work is to familiarize myself with the basics of correlation analysis and the main correlation coefficients, and to gain the skills to perform correlation analysis on real-world data.

I have been provided with a dataset Abalone(https://archive.ics.uci.edu/dataset/1/abalone). It is necessary to analyze the correlation relationships between quantitative indicators. The analysis will be based on correlation plots and pairwise correlation coefficients. To achieve this:

1. I will construct and analyze correlation plots for all pairs of quantitative indicators. During the analysis, I will pay attention to the following:
   - Identify noticeable linear or nonlinear dependencies between specific indicators and note the absence of any dependency between others.
   - Identify data heterogeneities.
   - Detect any anomalous values present in the data.

2. I will create and analyze a matrix of estimates for pairwise correlation coefficients. If the indicators are continuous and normally distributed, I will use the Pearson coefficient. If the distribution of indicators deviates from normal or if the indicators are discrete, I will use the Spearman or Kendall coefficient accordingly. In the constructed matrix, I will replace insignificant correlation coefficients with zeros or mark them with a special symbol. During the analysis, I will focus on the following:
   - Identify pairs of indicators with correlation coefficients close to 1 in magnitude.
   - Determine which independent indicator correlates most strongly with the dependent indicator (as defined in the given dataset, where the task involves regression; the indicator to be predicted is referred to as the dependent or target indicator).
   - Identify any indicators that do not correlate with any other indicators.
  
In the second part of this work I am tasked with creating a custom function that takes a dataset with two-dimensional data (comprising two indicators - x and y) as input and produces the following outcomes on the screen:

A correlation plot,
A table presenting the results of correlation coefficient estimation,
A table displaying the outcomes of hypothesis testing concerning the equivalence of the Pearson coefficient and the correlation ratio (applicable only when the correlation ratio holds significance).
