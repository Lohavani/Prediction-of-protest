# Prediction-of-protest

Link to dataset used for analysis and prediction - https://github.com/DISC-Systems-Lab/GDELT

The three files here are - 
1. Data Analysis - Code for exploratory data analysis and visualizations to identify trends in the protest data by aggregating and grouping on the dataframe. This uses File 1 (Balanced_Data_All.zip) which has some additional columns needed for the analysis.
2. Prediction using Target column (Data_Prediction_1) - This is the code for the final prediction which uses 5 classification algorithms (k-NN, Logistic Regression, Decision tree, Random Forest and XGBoost). Benchmarking of results between these algorithms is done using evaluation metrics. This is done using File 2 of the dataset (Balanced_Data_No_Protest_Code_Significant). 
3. Experimental prediction using EventRootCode (Data_Prediction_2)- This is an experimental prediction where the EventRootCode column is given as the target variable and the prediction is done using the same 5 algorithms. The results are accuracies of this prediction which is needed for comparing with Prediction 1. This is also done using File 2 of the dataset (Balanced_Data_No_Protest_Code_Significant).
