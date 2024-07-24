# deep-learning-challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

1. EIN and NAME—Identification columns
2.APPLICATION_TYPE—Alphabet Soup application type
3. AFFILIATION—Affiliated sector of industry
4.CLASSIFICATION—Government organization classification
5. USE_CASE—Use case for funding
6. ORGANIZATION—Organization type
7. STATUS—Active status
8. INCOME_AMT—Income classification
9. SPECIAL_CONSIDERATIONS—Special considerations for application
10. ASK_AMT—Funding amount requested
11. IS_SUCCESSFUL—Was the money used effectively

## Requirements
1. Preprocess the Data 
2. Create a dataframe containing the charity_data.csv data , and identify the 
3. target and feature variables in the dataset 
4. Drop the EIN and NAME columns 
5. Determine the number of unique values in each column 
6. For columns with more than 10 unique values, determine the number of data 
points for each unique value 
8. Create a new value called Other that contains rare categorical variables 
9. Create a feature array, X, and a target array, y by using the preprocessed data 
10. Split the preprocessed data into training and testing datasets
11. Scale the data by using a StandardScaler that has been fitted to the training data 
12. Compile, Train and Evaluate the Model 
13. Create a neural network model with a defined number of input features and nodes for each layer 
14. Create hidden layers and an output layer with appropriate activation functions 
15. Check the structure of the model
16. Compile and train the model 
17. Evaluate the model using the test data to determine the loss and accuracy 
18. Export your results to an HDF5 file named AlphabetSoupCharity.h5 
19. Optimize the Model 
20. Repeat the preprocessing steps in a new Jupyter notebook 
21. Create a new neural network model, implementing at least 3 model optimization methods 
22. Save and export your results to an HDF5 file named 
AlphabetSoupCharity_Optimization.h5 
23. Write a Report on the Neural Network Model 
- Write an analysis that includes a title and multiple sections, labeled with headers and subheaders 
- Format images in the report so that they display correction 
- Explain the purpose of the analysis 
- Answer all 6 questions in the results section 
- Summarize the overall results of your model
- Describe how you could use a different model to solve the same problem, and explain why you would use that model

