<<<  Project Overview  >>>



This project investigates the progression of joint destruction in patients with rheumatoid arthritis using longitudinal clinical data collected over a seven-year follow-up period. The main objective is to study how disease progression changes over time and how it is associated with patient characteristics such as sex, age, genetic background, and treatment-era differences.



Joint damage is measured using the Sharp–van der Heijde Score (SHS), an X-ray-based measure ranging from 0 to 448, with higher values indicating greater structural joint damage. Disease status is also assessed through a binary severity outcome, classified as low or high based on a combination of clinical indicators.



The dataset contains records from 500 patients enrolled between 1990 and 2006. Measurements were obtained at baseline and approximately annually for up to seven years. Available variables include patient age and sex, inclusion period, visit number, repeated SHS measurements, disease-severity assessments, and a selected single nucleotide polymorphism (SNP) representing genetic variation.



The analysis considers two longitudinal outcomes:



* Continuous outcome: progression of the Sharp–van der Heijde Score over time.
* Binary outcome: probability of experiencing high disease severity over time.



The statistical analysis focuses on determining how these outcomes evolve longitudinally while accounting for differences in sex, age, SNP status, and inclusion period. The inclusion period is particularly relevant because treatment strategies for rheumatoid arthritis changed during the study period. Patients are therefore distinguished according to whether they entered the study before or after January 1996.



Because repeated observations from the same patient are correlated, the analysis uses mixed-effects models. A linear mixed-effects model is used for the continuous SHS outcome, while a mixed-effects logistic regression model is used for the binary severity outcome. Model development includes exploration of the mean, variance, and within-patient correlation structures, assessment of interaction effects, model comparison, and residual diagnostics.



An additional challenge is the presence of incomplete longitudinal measurements due to factors such as loss to follow-up, relocation, remission, or other causes. The analysis therefore also considers the structure of the available repeated measurements when interpreting disease progression over time.



The project combines descriptive longitudinal analysis, statistical modeling, model diagnostics, and interpretation of effect estimates to characterize rheumatoid arthritis progression and investigate potential demographic and genetic factors associated with disease development.

