# Neural_Network
Built a deep learning neural network to evaluate and categorize the effectiveness of donations to charities.

## Overview of the Analysis
We used Bek's dataset to build an unsupervised binary classifier that can forecast whether applicants will be sponsored by Alphabet Soup using machine learning and neural networks. Through its corporate fundraising activities over the last few years, Alphabet Soup has provided funding to more than 34,000 organizations. The entire list is contained in a CSV file that Bek has been given. Each organization's information is contained in columns of the dataset. Put your understanding of Pandas and StandardScaler() of Scikit-Learn to use by compiling, training, and assessing a neural network model using the dataset.

## Results 

### Data Processing
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT was regarded as the model's features.
- The columns EIN and NAME were eliminated from the input data because they were neither targets nor features.
- Variable IS_SUCCESSFUL was regarded as the model's aim.

### Compiling, Training, and Evaluating the Model
- The model was unable to achieve 75% of the target. My model indicated a 72% accuracy rate.
- The STATUS and SPECIAL_CONSIDERATIONS columns were removed, and Tanh was substituted for relu as the activation function for the three layers.
- The first layer of the neural hidden layer contains 80 neurons, while the second layer contains 30 neurons. The output layer's activation function is "sigmoid," whereas the first and second hidden layers' activation functions are "relu."

## Summary
The accuracy goal of 75% was not met despite deep learning neural networks. Due to the target level's regularity, the model is not doing better than it. Given that our supervised model deals with binary classification, another supervised machine learning model might be employed, such as the Random Forest Classifier.
