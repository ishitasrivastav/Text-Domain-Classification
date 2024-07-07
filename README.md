# Text-Domain-Classification
This mini project focuses on the task of text domain classification utilizing Support Vector Machines (SVM) and Random Forest. The dataset comprises two columns: 'text' containing textual content and 'label' encompassing five distinct types: business, tech, entertainment, politics, and sports. The objective is to develop a model capable of accurately classifying text into one of these predefined categories.

The results demonstrate that the SVM classifier excels in text domain classification, achieving high levels of precision, recall, and F1-score across multiple domains. 

Category       | Precision | Recall | F1   | Support |
-------------- | --------- | --- -- | ---  |-------- |
Business       | 0.94      | 0.94   | 0.94 | 557 
-------------- | --------- | --- -- | ---  |-------- |
Entertainment  | 0.96      | 0.92   | 0.94 | 420 
-------------- | --------- | --- -- | ---  |-------- |
Politics       | 0.92      | 0.95   | 0.94 | 502 
-------------- | --------- | --- -- | ---  |-------- |
Sports         | 0.94      | 0.98   | 0.96 | 585 
-------------- | --------- | --- -- | ---  |-------- |
Tech           | 0.98      | 0.94   | 0.96 | 508

Accuracy       |           |        | 0.95 | 2572
-------------- | --------- | --- -- | ---  |-------- |
Macro Avg      | 0.95      | 0.94   | 0.95 | 2572 
-------------- | --------- | --- -- | ---  |-------- |
Weighted Avg   | 0.95      | 0.95   | 0.95 |  2572 

For Random Forest, 

Category       | Precision | Recall | F1   | Support |
-------------- | --------- | --- -- | ---  |-------- |
Business       | 0.92      | 0.86   | 0.89 | 557 
-------------- | --------- | --- -- | ---  |-------- |
Entertainment  | 0.93       | 0.82  | 0.87 | 420 
-------------- | --------- | --- -- | ---  |-------- |
Politics       | 0.88      | 0.90   | 0.89 | 502 
-------------- | --------- | --- -- | ---  |-------- |
Sports         | 0.84      | 0.97   | 0.90 | 585 
-------------- | --------- | --- -- | ---  |-------- |
Tech           | 0.92      | 0.89   | 0.91 | 508

Accuracy       |           |        | 0.89 | 2572
-------------- | --------- | --- -- | ---  |-------- |
Macro Avg      | 0.90      | 0.89   | 0.89 | 2572 
-------------- | --------- | --- -- | ---  |-------- |
Weighted Avg   | 0.90      | 0.89   | 0.89 |  2572 

