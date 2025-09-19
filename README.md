# Master Thesis Thilo Bergner
### The relationship between affect dynamics during psychotherapy and depression: A pilot study using a large language model
---
This repository contains all code and analyses for my master’s thesis. The knitted HTML reports are accessible via the links below:

1) [MA_1_Sentiment_Analysis](https://thilobergner.github.io/master-thesis/MA_1_Sentiment_Analysis.html) contains the pre-processing of the session transcripts, setting up of the large language model XLM-T and the sentiment prediction.
2) [MA_2_Data_Preparation](https://thilobergner.github.io/master-thesis/MA_2_Data_Preparation.html) contains data preparation, including the smoothing of sentiment scores and calculation of the final affect and depression measures.
3) [MA_3_Descriptive_Statistics](https://thilobergner.github.io/master-thesis/MA_3_Descriptive_Statistics.html) contains descriptive results for the affect and depression measures, as well as demographic data. Additionally, exemplary time series plots are created.
4) [MA_4_Imputation](https://thilobergner.github.io/master-thesis/MA_4_Imputation.html) contains the missing data analysis and the preparation of the MAR and two MNAR imputation models.
5) [MA_5_Results](https://thilobergner.github.io/master-thesis/MA_5_Results.html) contains the results for all hypotheses using both the MAR and the MNAR imputed datasets for the sensitivity analysis.

Additionally, the following reports contain the imputation models and results for all hypotheses using different smoothing parameters to assess the robustness of initial results:
1) [MA_6_Results_45](https://thilobergner.github.io/master-thesis/MA_6_Results_Robustness45) for a bandwith of 45.
2) [MA_6_Results_15](https://thilobergner.github.io/master-thesis/MA_6_Results_Robustness15) for a bandwith of 15.
3) [MA_6_Results_raw](https://thilobergner.github.io/master-thesis/MA_6_Results_Robustness_raw) for the raw sentiment scores.
