# PRS_boosting_ukb
Analysis of snpboostlss results on UK Biobank 

<p style="text-align: justify;">
  
**Abstract:** Polygenic scores are commonly used to estimate the cumulative genetic contribution to complex traits by aggregating the effects of multiple genetic variants. In the case of continuous phenotypes, traditional methods have primarily focused on predicting the effect of variants on the phenotypic mean in the population, thereby overlooking potential genetic influences that modulate phenotypic variance. Recent studies suggest that variance quantitative trait loci (vQTLs) provide important insights into the genetic control of trait variability and may serve as candidates for gene–environment interactions that are not captured by mean-based models.

In this work, we applied ***snpboostlss***—a new cyclical gradient boosting framework for Gaussian location–scale models to body mass index (BMI) data from the UK Biobank. This method efficiently processes high-dimensional genotype data by selecting, in each boosting iteration, a batch of variants that exhibit strong correlations with the current residuals. By estimating genetic effects on both the mean and the variance of BMI, snpboostlss enables the construction of dual-component polygenic models that offer a more detailed view of the genetic architecture
underlying the trait.

Our analysis revealed genetic loci that influence average BMI alongside markers that predominantly affect BMI variance. Notably, some variants contributed to both components, while others were specific to variance, suggesting distinct mechanisms and potential evidence for gene–environment interplay. These findings demonstrate that integrating variance effects into polygenic modeling can improve model interpretability and yield refined predictive insights for complex traits within precision medicine.
</p>
