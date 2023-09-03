Overview of the analysis: The purpose of this project is to create a model using machine learning and neural networks to predict if applicants will be successful if the nonprofit foundation Alphabet Soup provides funding. 

Data Preprocessing
What variable(s) are the target(s) for your model? The target variable is the 'IS_SUCCESSFUL' column from application_df
What variable(s) are the features for your model? The features were 'APPLICATION_TYPE', 'AFFILIATION', CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONCIDERATIONS', and 'ASK_AMT'
What variable(s) should be removed from the input data because they are neither targets nor features? 'EIN' and 'NAME' variables were removed because they were neither targets or features. 

Compiling, Training, and Evaluating the Model
Attepmt #1
    * layer 1 = 8 neurons and activation function = relu
    * layer 2 = 5 neurons and activation function = relu
    * epochs = 100
    * result = 72.4%

Attempt #2 
    * layer 1 = 8 neurons and activation function = relu
    * layer 2 = 18 neurons and activation function = relu
    * epochs = 100
    * result = 72.71%

Attempt #3
    * layer 1 = 9 neurons and activation function = relu
    * layer 2 = 18 neurons and activation function = relu
    * layer 3 = 18 neurons and activation function = relu
    * epochs = 100
    * result = 72.67%

Summary: The highest accuracy my models achieved was 72.71%, not quite the requested 75%. I was able to change the parameters in a way that would provide varying results. All three attempts were within 0.31% of each other. 