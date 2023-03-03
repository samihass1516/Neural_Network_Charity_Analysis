# Neural_Network_Charity_Analysis

## Overview:

This challenge aims to explore and implement neural networks using the TensorFlow platform in Python.

     •	Compare the differences between the traditional machine learning classification and regression models and the neural network models.
  
     •	Describe the perceptron model and its components.
  
     •	Implement neural network models using TensorFlow.
  
     •	Explain how different neural network structures change algorithm performance.
  
     •	Preprocess and construct datasets for neural network models.
  
     •	Compare the differences between neural network models and deep neural networks.
  
     •	Implement deep neural network models using TensorFlow.
  
     •	Save trained TensorFlow models for later use.
  
## Analysis:

Data Analysts Beks, who has come a long way since her first day at that boot camp five years ago, came to help the Alphabet Soup foundation predict where to make investments.  With our knowledge of machine learning and neural networks, we will use the features in the provided dataset to help Beks create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

    •	Deliverable 1: Preprocessing Data for a Neural Network Model
    •	Deliverable 2: Compile, Train, and Evaluate the Model
    •	Deliverable 3: Optimize the Model
    •	Deliverable 4: A Written Report on the Neural Network Model (README.md)
    
## Results:

Data Processing

1.	The column IS_SUCCESSFUL is considered the target variable of our model because IS_SUCCESSFUL contains binary data on whether or not the charity donation was used effectively.

2.	The variables considered our model’s features are: The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and ASK_AMT         columns.

3.	The variable(s) that were neither targets nor features and had to be removed from the input data was the: EIN, NAME, STATUS, and SPECIAL_CONSIDERATION       columns.

![Screenshot 2023-03-02 232246](https://user-images.githubusercontent.com/114379268/222630868-6fb03d7b-bdc8-4ffa-bb25-6efa87fa9cb2.png)

Compiling, Training, and Evaluating the Model

For the AlphabetSoupCharity_Optimization, I conducted three models.  For the first one, I did three hidden nodes layers.  And for the first layer, I changed the activation to Sigmoid, hoping to increase the model’s performance, but I got an accuracy of 72%

![Screenshot 2023-03-02 223440](https://user-images.githubusercontent.com/114379268/222631010-083f3f44-cf6f-4b3a-9b8a-a5292b1ca132.png)
![Screenshot 2023-03-02 223523](https://user-images.githubusercontent.com/114379268/222631030-b49e3aae-993f-4c01-8a99-21def60b4252.png)

And for the second model, I conducted four hidden nodes layers, but for the first layer, I changed the activation to Relu and the Epoch of 5, and the accuracy came out to 72%

![Screenshot 2023-03-02 223553](https://user-images.githubusercontent.com/114379268/222631084-27c50524-4ef2-4779-8a26-6c2a33f33199.png)
![Screenshot 2023-03-02 223620](https://user-images.githubusercontent.com/114379268/222631098-d6b6b4d1-5174-4028-a688-e55ec362257d.png)

And my third model, I conducted four hidden node layers, and for the first layer, I changed the activation to Sigmoid again, hoping it would increase my accuracy.  And I changed the Epoch to 50, but I still got an accuracy of 72%. If I round it up, it’s 73%

![Screenshot 2023-03-02 225205](https://user-images.githubusercontent.com/114379268/222631211-d8014d62-c76a-4c3b-93cc-9245ad3a1f4d.png)
![Screenshot 2023-03-02 225231](https://user-images.githubusercontent.com/114379268/222631227-36ed0e77-fd5f-4acb-909a-a74db58bd439.png)

## Summary:

After running different models, changing the numbers for the hidden nodes layers, and adding neurons, I hoped to get an accuracy higher than 75%, but unfortunately, that did not happen.  One recommendation is to use a different learning machine, the supervised learning machine model Random Forest Classifier.  It can perform both regression and classification tasks.  And it can produce good predictions that can be easily understood and handle extensive data efficiently.



