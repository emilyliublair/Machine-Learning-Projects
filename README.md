# Machine Learning Projects

### Description
These are 4 machine learning-centered projects I built using Tensorflow and Python. Made from Google Colaboratory. 

#### Cat Dog Image Classifier
This machine learning model takes in images and classifies them into classes of dogs or cats. Retrieved data from https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip. I created a convolutional neural network with 2 stacks of Conv2D and MaxPooling2D layers and 2 dense layers activated by a ReLU activation function and a sigmoid function. Achieves 66% accuracy. 

#### Book Recommendation Using KNN
This is a book recommendation algorithm using K-Nearest Neighbors that takes in a book title and returns a list of 5 similar books along with their respective distance. Retrieved data from https://cdn.freecodecamp.org/project-data/books/book-crossings.zip. To ensure statistical significance, I removed users with less than 200 ratings and books with less than 100 ratings. Then, I created the model using the algorithm, 'brute', and the metric as 'cosine'. 

#### Predicting Health Costs Using Regression
This machine learning model predicts healthcare costs based on sex, if the patient smokes, region, age, bmi, and number of children using a regression algorithm. Retrieved data from https://cdn.freecodecamp.org/project-data/health-costs/insurance.csv. The model contains 3 dense layers activated by the ReLU activation function. Achieves a Mean Absolute Error of 1824.48 expenses. 

#### Text Classification Using LSTM
This machine leanring model will classify SMS messages as either 'ham' (sent by a friend) or 'spam'(sent by a company or is a advertisement message). Retrieved data from https://cdn.freecodecamp.org/project-data/sms/train-data.tsv, https://cdn.freecodecamp.org/project-data/sms/valid-data.tsv. The model is made up of an LSTM layer and a dense layer with the activation function 'sigmoid'. Near 98% accuracy. 
