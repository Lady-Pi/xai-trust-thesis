## Deep Neural Network-Based Loan Approval System with Deep SHAP Explanations

**Author: Lisa van der Linden**

**Bachelor of Science**  - Applied Artificial Intelligence

**Bachelor Thesis** The Effect of Explainable Artificial Intelligence (XAI) on User Trust in Deep Neural Network-Based Loan Approval Systems

**International University of Applied Sciences**

The purpose of this notebook is generate explanations in various levels of transparancy for automated loan approval evaluations.

A DNN model is trained using the German Credit Dataset. Loan applications will be evaluated using binary outcomes (approved/rejected).

Deep SHAP will be implemented to generate explanations for the predictions. Outputs of these explanations will be generated in three levels of incremental transparancy:

- The Amber System: No explanation
- The Opal System: a simplified explanation in plain english using the top two features based on SHAP values
- The Quartz System: The full SHAP waterfall

The code contains an algorithm to select scenarios with a variety of top features and good explainability.

The loan approval model is intended for demonstration and resarch purposes only.
