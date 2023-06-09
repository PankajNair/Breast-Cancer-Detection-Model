# Breast Cancer Detection Model
## Problem Statement
Breast cancer is one of the leading causes of cancer-related deaths among women worldwide. Early detection of breast cancer is crucial for successful treatment and improved survival rates. However, accurate and timely detection of breast cancer remains a challenging problem due to the complexity of mammograms and the subtle differences between cancerous and non-cancerous tissues. The problem of breast cancer detection requires the development of advanced machine learning models that can effectively analyze mammogram data, accurately identify signs of breast cancer, and generalize well to new data. Addressing these challenges is crucial for the successful detection and treatment of breast cancer, which can significantly improve patient outcomes and reduce cancer-related mortality rates.
## Data Information
The dataset can be download using this [link](https://drive.google.com/file/d/1HQqUCF23fihnE3aCbx2MNPmER9o_If_m/view)

The dataset contains various information that would be required for the accurate detection of the tumor. It includes mean and worst area, texture, smoothness and compactness. 1 is used to identify a Benign tumor and 0 is used to identify a Malignant tumor.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. For the current dataset, we standardize the input data values using the StandardScalar() function available in sklearn library.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use keras and Tensorflow to build the model. The model has 3 layers, the input and hidden layers having relu activation and the output layer having sigmoid activation. We also need to evaluate the models using appropriate evaluation metrics.
