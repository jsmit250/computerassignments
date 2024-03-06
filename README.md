# Machine Learning Computer Assignments:

# CA01: Exploratory Data Analysis – House Price Analysis

Exploratory Data Analysis is an approach analyzing data sets to summarize their main
characteristics such as mean, standard deviation, and count, so on, often with visual
methods. It’s where the researcher takes a bird’s eye view of the data and tries to make
some sense of it. It’s often the first step in data analysis, implemented before any formal
statistical techniques are applied.

# CA02: Building a Spam Detector using Naive Bayes Algorithm
	
Assignment Description: In this exercise we shall train the model with set of emails labelled as either from Spam
or Not Spam. There are 702 emails equally divided into spam and non spam category.
Next, we shall test the model on 260 emails. We shall ask model to predict the category
of this emails and compare the accuracy with correct classification that we already know.

Instructions: The data folders are in a Zip file at BrightSpace CA02 assignment folder. The assignment
instruction document and the provided .ipynb file is also at BrightSpace.
What you are supposed to do:

1. Read the code and understand the logic of every line of the code

2. Complete the code (there are missing areas of the code and it is mentioned in the
		commented cells), such that the code runs properly and produces the exact same
		result as displayed at the end of the notebook.

3. Comment the code thoroughly using “markdown” texts and comment lines so that
		the logic of the code is easily understandable. It’s your job to explain clearly your
		understanding of the process at every step

# CA03 – Decision Tree Algorithm

1. Data Source and Contents

2. Data Quality Analysis (DQA)

3. Build Decision Tree Classifier Models
Definition: Given a data of attributes together with its classes, a decision tree produces a
sequence of rules that can be used to classify the data.
Advantages: Decision Tree is simple to understand and visualise, requires little data
preparation, and can handle both numerical and categorical data.
Disadvantages: Decision tree can create complex trees that do not generalize well, and
decision trees can be unstable because small variations in the data might result in a
completely different tree being generated.

4. Evaluate Decision Tree Performance
Calculate and display the following. Do all of these inside your Notebook.
• Confusion Matrix (TP, TN, FP, FN ... etc.)
• Accuracy, Precision, Recall, F1 Score

5. Tune Decision Tree Performance
Try varying FOUR of the hyperparameters manually, as per the following table, and train /
score your model for each set of these hyperparameters. Record your Tree’s performance
with respect to each of these sets of hyperparameters in the Model Performance section of
the following table.

6. Visualize Your Best Decision Tree using GraphViz

7. Conclusion
Explain your observations from the above performance tuning effort.
Q.4 How long was your total run time to train the best model?
Q.5 Did you find the BEST TREE?
Q.6 Write your observations from the visualization of the best tree
Q.7 Will this Tree “overfit”? (Hint: Is this tree “fully grown”

8. Prediction using your “trained” Decision Tree Model

9. Deliverables
Your assignment outputs will have the following components:
(1) Fully functional Notebook, Data, Readme file in a single folder at GitHub (this is for
sharing with your peer for peer review)
(2) Upload your fully executed notebook at BrightSpace
(3) All questions should be answered with the corresponding Question Numbers in
Marked-down Cells in the Notebook.

# CA04 – Ensemble Models

1. Data Source and Contents

   The dataset is obtained from the Census Bureau and represents salaries of people along
with seven demographic variables. The following is a description of our dataset:
• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
• Number of attributes (Columns): 7
• Number of instances (Rows): 48,842
Use the following exact “path” in your code as the data source:
"https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true"
Training and Test Data: There is a column indicating the rows to be used as “Training
Data” and “Testing Data”. You can programmatically create your Training and Testing
datasets as separate dataframes in your code based on this column value.
You do not need to do DQA, as you had already done so in CA03 for the same data.
However, you need to do the same data cleaning and transformations here again to be able
to run the ML Model. You can re-use the code from CA03.

2. Finding Optimal Value of a key Ensemble Method Hyper-parameter

   For Ensemble Models, one of the key hyper-parameter is number of “estimators”. You are
required to find its best value by creating the following line graphs:
- Accuracy Vs. n_estimators
- AUC Vs. n_estimators
Following is an example code of finding the optimal value of “Accuracy” Vs. “Maximum
Depth” for DecisionTreeClassifier algorithm. Review the following code snippet to
understand how the optimal value of this hyper-parameter (Max Depth = 10) is found by
plotting a graph.

3. Building a Random Forest Model

 	Using Notebook, and the same data source from CA03, train a Random Forest Model. Using
similar approach of Section 2 above, plot a graph of Accuracy vs. n_estimator and AUC Vs.
n_estimator. Use n_estimator values as [50,100,150,200,250,300,350,400,450,500]. Keep
all other hyperparameter values at default.
Answer the following questions for Random Forest model and each algorithm in 4:
	1. Write your observations about the Classifier’s behavior with respect to the number
of estimators
	2. Is there an optimal value of the estimator within the given range?

4. Building AdaBoost, Gradient Boost, and XGB

	Repeat the process of Section 3 above for AdaBoost, Gradient Boost, and XGB Classifiers.
   
5. Compare Performance

	For the best values of Accuracy and AUC for four models (Random Forest, AdaBoost,
Gradient Boost, XGB) in the previous steps
   
6. Deliverables

   	Your assignment outputs will have the following components:
	(1) Fully functional Notebook, Data, Readme file in a single folder at GitHub
	(2) Fully functional and fully executed Notebook at BrightSpace



