# Breast Cancer Wisconsin DatasetApplication and Results of 6 Different Machine Learning Classification Algorithms
According to BreastCancer.org, breast cancer is the most common cancer across the globe, accounting for roughly 12.5\% of all new cancer cases worldwide. This is reflected within the United States, where an estimated 30\% of newly diagnosed cancers in women will be breast cancer \cite{BCorg}. It is no secret how lethal this cancer can be, and how critical it is to be able to detect it early in order to begin treatment and save patients' lives. Of course, genetics plays a role, which is why when one woman in a family is diagnosed with breast cancer, doctors will urge others that are closely related to her to get tested as well. However, the majority of breast cancer cases occur in women with no prior family history of breast cancer - about 85\% specifically \cite{BCorg}. With such a high incidence of mutations resulting from aging and other life processes, it becomes evident that relying solely on the diagnoses of other women in the family is not a perfect strategy. We must become better at detecting harmful breast cancer cells before they spread into the rest of the body.

For this study, we intend to apply six different classification algorithms to a dataset created by the University of Wisconsin, whose researchers took grayscale images of 569 different breast cancer cell's nuclei. This dataset consists of several features of each nucleus, and whether the cell is diagnosed malignant (M) or benign (B). Of these 569 samples, 357 were diagnosed benign, and 212 malignant. For each of these 10 features, the mean, standard error, and "worst" (mean of the three largest values) is calculated, totaling to 32 columns including the sample's unique ID and diagnosis. 

The six algorithms that will be applied to this dataset include: Decision Tree, Random Forest, k-Neural Network (kNN), Logistic Regression, Support Vector Machine (SVM), and Naive Bayes Classifier. These algorithms have been applied in previous studies, including those that used medical data, and the results have been promising. In particular, it appears the SVM and Random Forest perform the best, with kNN performing the worst, but none have testing accuracies below 90\%. Thus, there is high confidence that these algorithms will all perform very well with this dataset, further proving the viability of using machine learning to diagnose breast cancer.
