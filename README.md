# skin_disease_analysis & prediction

# problem Statement
 The goal is to predict the specific skin condition based on the combination of clinical and histopathological features. The classification of patients into one of these six classes is crucial for accurate diagnosis and treatment.

 # Dataset Overview
 This healthcare dataset consists of 34 columns, where 33 columns are treated as features and one column, labeled "class", serves as the target variable. The dataset is focused on diagnosing or analyzing a skin-related medical condition. The features are divided into two categories: 12 clinical features and 22 histopathological features. Each of these features is categorical, taking values in the range of 0, 1, 2, 3. A value of 0 represents the absence or minimal effect of the disease, while 1 and 2 represent mild effects, and 3 indicates a severe presence of the feature.

In addition to the categorical features, there is one continuous feature, Age, which is measured as a linear variable, representing the patient's age in years. This feature is distinct from the rest as it is continuous rather than categorical.
The target column, labeled "class" contains 6 unique values, each representing a distinct skin condition. This makes the dataset a multiclass classification problem.

