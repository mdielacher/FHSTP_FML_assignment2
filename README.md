# FHSTP_FML_assignment2 - Group 4
**Members:** Marwin Prenner, Leo Weissensteiner, Merna Zaher, Matthias Kopeinig, Marcel Dielacher

## Introduction:
### Summary
This project deals with a synthesised Adult Census Income dataset and aims to develop a Proof of Concept (PoC) that identifies the financial health of individuals aged 17 to 90 years. The project includes phases such as data understanding, model comparison and the implementation of a proof of concept with federated learning.

### Understanding the data
The Adult Census Income dataset contains a variety of characteristics that provide information about individuals, their occupational characteristics, education level, marital status and more. The goal is to use this data to predict the financial health of individuals.

The data was thoroughly analysed and processed to identify potential factors influencing the financial situation. This step was crucial for the development of accurate models.

### Data preperation & Feature Enfineering
The cleansing of data includes the handling of missing or incorrect values, the removal of duplicates and the adjustment of data formats. The aim is to bring the data into a consistent and reliable state. This phase is crucial to ensure that the models are trained on high-quality data.

### Model comparison
Various machine learning models were tested for their suitability for financial health forecasting. This process involved training and evaluating models such as decision trees, random forests, support vector machines and neural networks. The best models were selected based on their accuracy, precision and recall.

### Federated Learning Proof of Concept
To address data protection concerns, a proof of concept for federated learning was implemented. This approach makes it possible to train models on the distributed data of individuals without centralising the data itself. This preserves the privacy of the individuals.

The implementation includes the configuration of federated learning platforms, the training of models on decentralised nodes and the merging of the aggregated models into a final prediction unit.

## Run Code:
1. Execute the **00_preprocessing.ipynb** to preprocess the data + feature engineering --> please create the folder data
2. Execute the **01_data_findings.ipynb** to understand the data
3. Execute the **02_model-comparison.ipynb** to try different models --> please create the folder models if you run it (it is better not to let it run it will take a very long time)
4. Execute the **02a_comparsans_fresh.ipynb** - to find the best SMOTE.
5. Execute the **02b_xgboost_eli5.ipynb** - to make a XGBoost Classifier with ELI5.
6. Execute the **03_nn-fml-poc.ipynb** to simulate the FML 



