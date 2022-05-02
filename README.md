# Neural_Network_Charity_Analysis

# Overview of the Loan Prediction Risk Anaylsis:

	 The purpose of this analysis is to develop a neural network to assist in finding out which organizations should be considered for funding from Alphabet Soup Charity. Using data obtained from organizations that have been given or denied funding, the neural network is to be trained on multiple inputs to classify future organization requests for funding.

# Results:

- Data Preprocessing

	What variable(s) are considered the target(s) for your model?

		The target of IS_SUCCESSFUL is the current target for the model.

	What variable(s) are considered to be the features for your model?

		APPLICATION_TYPE
		AFFILIATION
		CLASSIFICATION
		USE_CASE
		ORGANIZATION
		STATUS
		INCOME_AMT
		SPECIAL_CONSIDERATIONS
		ASK_AMT

	What variable(s) are neither targets nor features, and should be removed from the input data?

		EIN
		NAME

- Compiling, Training, and Evaluating the Model

	How many neurons, layers, and activation functions did you select for your neural network model, and why? 

		For the 1st attempt at model, two layers, with 80 and 30 neurons respectively, were used. Next, we activated "sigmoid." This was presented as the starting point for the creation of the model allowing 		the analyst to adjust in order to increase optimization.

	Were you able to achieve the target model performance? 

		The performance was set at 75%. Unfortunately, the current model only achieved an accuracy rating of 63.76%. 

	What steps did you take to try and increase model performance? 

		In order to improve efficiency, three attempts were performed. 

# Summary

	As stated above, the first setup for the model did not perform at the required level, coming in at 63.76%. The model was adjusted and the percentage dropped on the last two attempts. All other models had lower final accuracies than the initial model. For this, it can be seen that changing the number of hidden layers and neurons had a worse effect on increasing model accuracy. Further adjustment may lead to a model that eliminates the validity the dataset.

Based the results, I would recommend a Random Forest Classifier for an alternate model design through machine learning. This is due to Random Forest ability of performing binary classification and the ability to handle large datasets which would hopefully provide a more accurate result.