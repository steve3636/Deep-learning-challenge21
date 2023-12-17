# Deep-learning-challenge
Certainly! Here's an extended version of the report considering additional attempts made to enhance the model's performance:

---
Deep Learning Model Performance for Alphabet Soup

The Analysis:
The analysis aims to develop a deep learning model for Alphabet Soup, a non-profit organization, to predict the success of funding applicants. The goal is to create a model that accurately predicts whether applicants will use the funding effectively based on various features provided in the dataset.

Data Preprocessing

Target Variable
  - The target variable for the model is focus on 'IS_SUCCESSFUL,' indicating whether funding applicants were successful (binary classification: 1 for successful, 0 for unsuccessful).

Features:
  - Features used for the model include 'APPLICATION_TYPE,' 'AFFILIATION,' 'CLASSIFICATION,' 'USE_CASE,' 'ORGANIZATION,' 'STATUS,' 'INCOME_AMT,' .

Variables Removed
  - At first 'EIN' and 'NAME' columns were removed as they don’t contribute as features or targets. 'SPECIAL_CONSIDERATIONS' been removed been removed to improve the performance.

Compiling, Training, and Evaluating the Model

- Neurons, Layers, Activation Functions:
  - Model architecture:
    - First hidden layer: 80 neurons with ReLU activation. At optional file: 180 neuron avtivated
    - Second hidden layer: 30 neurons with ReLU activation. At optional file 20 neuron avtivated
    - Output layer: 1 neuron with Sigmoid activation for binary classification.
   
  At Otional file: 3 3 hiden layer was added.
    - First hidden layer: 180 neurons with ReLU activation. 
    - Second hidden layer: 20 neurons with ReLU activation.
    - Third hidden layer: 10 neurons with ReLU activation.
    - Output layer: 1 neuron with Sigmoid activation for binary classification.

  Achievement of Target Model Performance
    - The model underwent several iterations:
    - Removed 'SPECIAL_CONSIDERATIONS,' adjusted cutoff values.
    - Adjusted epochs and added more layers.
    - Increased epochs had some influence on improvement but fell short of the target.
    - The final accuracy achieved was approximately 72.86%.

 Observations:
  - Despite various adjustments, including altering the dataset and model architecture, the model's performance improved marginally (less than 1%).
  - Increasing epochs showed a slight influence in improvement but still did not reach the desired accuracy level.

Summary

The deep learning model achieved an accuracy of approximately 72.86% in predicting funding success after multiple iterations and adjustments. Despite efforts to fine-tune the model, improvements were limited, showcasing the complexities in achieving higher accuracy for this classification problem.

To enhance the model further:
- Exploring more sophisticated architectures or alternative models like ensemble methods could potentially improve predictions.
- Extensive feature engineering or exploring other external datasets might provide additional valuable information for better predictions.

Considering the constraints faced in improving accuracy, it might be prudent to explore alternative modeling approaches or seek additional relevant data sources to address the challenges of this specific classification problem effectively.

