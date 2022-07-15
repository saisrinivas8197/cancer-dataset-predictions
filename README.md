# cancer-dataset-predictions
- Dataset used for cancer prediction is available in kaggle and contains information regrding ID, Diagnosis(M = malignant, B = benign), ten real valued fetures for each cell nuclei. The analysis focuses on which features are important in cancer prediction and aid us in model selection and hyper parameter selection.
- Initially data is imported into panadas dataframe via Jupyter notebook, checked for any missing or null values and observed the data distribution of the independant features using matplot lib package.
- Next, categorical variable (diagnosis) is converted into numeric with the help of Label Encoder.Label Encoder is the part of SciKit Learn library in Python and used to convert categorical data, or text data, into numbers, which our predictive models can better understand.
- 
