This folder contains the data files related to two papers published by Bannach-Brown et al. (2019). The first one is [Understanding in vivo Models of Depression: A Systematic Review](https://onlinelibrary.wiley.com/doi/full/10.1002/ebm2.24), a systematic review project that resulted in the data set we can use. The second paper is [Machine learning algorithms for systematic review: reducing workload in a preclinical review of animal studies and reducing human screening error](https://systematicreviewsjournal.biomedcentral.com/articles/10.1186/s13643-019-0942-7#Comments), where the authors classified a part of the papers found in the first study into inclusion or exclusion. In this second paper, the authors used a training set of 5749 papers and claimed that we can download the records on this [website](https://zenodo.org/record/151190#.XQPGhYj7TD7). However, on the data archive website, we only have access to a data set (with inclusion and exclusion labels) that is less than half of the size of the actual data set used in the study. The sample size of the data set we have access to is 1993, with 14% inclusion rate.

The "Depression-Dataset-SLIM-DevelopmentTrainingSet.txt" file is the raw data set downloaded from the research archive link above. The "Data Processing.R" contains the code to process the raw data set and output the csv file we can use. The "Bannach-Brown Data" is the final csv data file we can use for our own purpose. 