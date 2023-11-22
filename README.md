## Evaluating the Impact of Data Preprocessing Techniques on the Performance of Intrusion Detection Systems

This repository contains complementary materials for the article Evaluating the Impact of Data Preprocessing Techniques on the Performance of Intrusion Detection Systems.

The article studies the impact of data processing techniques on the performance of Machine Learning (ML) based Intrusion Detection Systems (IDS).

The preprocessing techniques used were data cleaning, codification, and normalization to observe performance in binary and multiclass models.

The datasets used were UNSW-NB15 and CIC-IDS2017, which are publicly available.

The main objective of the work lies in the research questions aimed at which data processing techniques perform best in Machine Learning based IDS and how various classification algorithms perform under different preprocessing techniques.

Below are descriptions of the files relating to complementary materials on the results of experiments and evaluation tests of data preprocessing techniques and IDS models.

The files show graphs with normality distributions of the data that justify the use of non-parametric statistical tests in the investigation. In addition, tables with differences in critical distances between all data preprocessing techniques were performed in the performance comparison with the Nemenyi test.

# File: 1_fig_non-normal_distribution_techniques.jpg

The figure (1_fig_non-normal_distribution_techniques.jpg) shows the non-normal distribution of the sample data for the data preprocessing techniques. The non-normal distribution justifies the execution of non-parametric statistical tests in the investigation. Non-parametric tests are applied when there is no normal distribution between sample data.

# File: 2_fig_non-normal_distribution_algorithms.jpg

The figure (2_fig_non-normal_distribution_algorithms.jpg) shows the non-normal distribution of the sample data concerning the classification algorithms. The non-normal distribution justifies the execution of non-parametric statistical tests in the investigation. Non-parametric tests are applied when there is no normal distribution between sample data.

# File: 3_appendices_comparisons_techniques_nemenyi_test.pdf

The file (3_appendices_comparisons_techniques_nemenyi_test.pdf) shows in detail the comparisons between the groups of data preprocessing techniques in the binary class models and multiclass models, with specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC-IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017).

# File: 4_appendices_comparisons_algorithms_nemenyi_test.pdf

The file (4_appendices_comparisons_algorithms_nemenyi_test.pdf) shows in detail the comparisons between classification algorithms using data preprocessing techniques in binary class models and multiclass models, with specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC-IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017).

# File: 5_descriptive_statistics_techniques.pdf

The file (5_descriptive_statistics_techniques.pdf) shows the descriptive statistics of the sample results of the data pre-processing techniques in the binary class models and multiclass models for specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC-IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017). The description includes the following data:
- Metric: name of the metric to analyze.
- Technique: acronym for the group of analyzed techniques.
- Count: number of lines per sample.
- Mean: sample mean of the rows.
- S-Dev: sample standard deviation of the rows.
- Var: sampling variation of the lines.
- Min: minimum sample value of the rows.
- Q1: sample value of the first quartile of the rows.
- Median: sample value of the median of the rows.
- Q3: sample value of the third quartile of the rows.
- Max: maximum sample value of the rows.

# File: 6_descriptive_statistics_algorithms.pdf

The file (6_descriptive_statistics_algorithms.pdf) shows descriptive statistics of the sample results of classification algorithms using data preprocessing techniques in the binary class models and multiclass models for specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC-IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017). The description includes the following data:
- Metric: name of the metric to analyze.
- Technique: acronym for the group of analyzed techniques.
- Count: number of lines per sample.
- Mean: sample mean of the rows.
- S-Dev: sample standard deviation of the rows.
- Var: sampling variation of the lines.
- Min: minimum sample value of the rows.
- Q1: sample value of the first quartile of the rows.
- Median: sample value of the median of the rows.
- Q3: sample value of the third quartile of the rows.
- Max: maximum sample value of the rows.

# File: 7_boxplot_sample_results_techniques.jpg

The figure (7_boxplot_sample_results_techniques.jpg) shows the boxplot of sample results of data preprocessing techniques in binary class models and multiclass models for specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC -IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017).

# File: 8_boxplot_sample_results_algorithms.jpg

The figure (8_boxplot_sample_results_algorithms.jpg) shows the boxplot of sample results of classification algorithms using data preprocessing techniques in binary class models and multiclass models for specific attacks from Group 1: Reconnaissance (UNSW-NB15) and PortScan (CIC -IDS2017), and specific attacks from Group 2: DoS (UNSW-NB15) and DoS/DDoS (CIC-IDS2017).
