# Data Analysis & Machine Learning Projects

Here are all my Data-related projects. A description of each of them is provided, as well as images to show the results.

All the code can be found in this repository.

## Amazon search result analysis and classification (python)

In this project I did data analysis and **trained a machine learning model to classify an amazon product wheter it was owned** (or possibly owned) **by Amazon or not**. All in python 3. 

This proyect was finished **December 2022**. The database used for this proyect is named "Amazon Brands and Exclusives" and can be found in [here](https://www.kaggle.com/datasets/thedevastator/amazon-s-dominance-in-e-commerce-why-you-should). 

The project files are 2: "Data_Analysis_Amazon.ipynb" and "Machine_Learning_Amazon.ipynb", and can be found in this repository. **This documents include not only code, but details and explanations**; for a detailed analysis, please see the documents. 

### Data Analysis
Here are some graphics regarding the data analysis:



Statistical test were done. Particularly, the **Mann Whitney U Test** for each pair of data to test for statistical difference. Since most of the pairs of data had a statistically significant difference, I continued with the machine learning model. _More details are found on the .ipynb file_

### Machine learning
2 models were trained using the scikit-learn library in python:
- A **logistic regression** model with 6 features. This one reached **71% accuracy**.
- A **neural network** model with 6 initial features and 3 hidden layers of 6 neurons each. This one reached up 75% in accuracy. 

Both of these only classified between "wholly non-Amazon" products, and others, to increase the accuracy of the model. 

Important notes:
- This was an **individual project**. All the work was done by me, using the free-to-use [database](https://www.kaggle.com/datasets/thedevastator/amazon-s-dominance-in-e-commerce-why-you-should). 
- The **objetive of this project** was to verify if it was possible to develop a classifier that could allow for more "honest" (ad-free) search resutls, as it seemed that products owned by Amazon got better placements in the results. However, only the data analysis and machine learning models were done by me. 
- I overall think that **the results of the project were decently sucessfull**, achieven over 75% acurracy. It is clear that improvements could be made though. 
