# Waterman_Projects
Data science work in healthcare and other domains

Diabetes Predictions (6 files):

1. Data_Engineering.ipynb: Script Contains: all code for cleaning, engineering, and otherwise preparing data for machine learning.

2. Feature_selection.ipynb: Script combs through cleaned output of script #1, and reduces the dimensionality of the dataset, retaining only features of relatively high predictive value, thereby improving the predictive power of our eventual model. The curated features are then used for the later machine learning scripts.

3. XGBoost.ipynb: Script Contains: hyperparameter tuning job initiatied in notebook, the training of an optimized model from the optimized hyperparameters, the deployment of this model, and batch predictions being used to assess the model in both a statistical as well as a financial/operational context.
   
4. Linear_Learner.ipynb: (Script Contains: Sagemaker UI initiated hyperparameter tuning job using protobuf data, the training of an optimized model from the optimized hyperparameters, the deployment of this model, the statistical assessment of the model, and the deployed model's ability to interact with the 'Lambda_function_script_facilitating_inference_calls.py' file to facilitate real-time inference calls.

Lambda_function_script_facilitating_inference_calls.py: Script used to facilitate back-end real-time inference calls alongside the deployed model and an API Gateway.

Diabetes_Inputs.csv: (contains raw input data for the above "1. Feature_Engineering.ipynb" file).
