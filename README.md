Iris Classification using Logistic Regression
Project Overview
The main purpose of this project is to perform a classification using Logistic Regression with the Iris dataset which is known to be one of the most popular.\r\nThe error is to identify the species of iris flowers using different features like sepal length, sepal width, petal length, and petal width.
Dataset
All of the data in the Iris dataset are intended to be used for the classification of three species of iris flowers which are namely Setosa, Versicolor, and Virginica. The dataset consists of four features for each flower sample, namely:
- Sepal length
- Sepal width
- Petal length
- Petal width
These before-mentioned features will be then calculated with the help of a simple mathematical model and the resulting formula will be used for predicting the species of the iris flower.
Steps Involved
1. **Loading the Dataset**  
   A function for importing the dataset is predefined, which can be used in Python or R language. The data and the target labels are given to the function which is then used to load the data into memory.
2. **Preprocessing the Data**  
- Divide the dataset into a training set and a test set with `train_test_split()` command.
   - Convert the z score of the feature attributes for better model performance with `StandardScaler()`.
3. **Train Logistic Regression Model**  
   We use the training data to train a Logistic Regression classifier.
4. **Model Evaluation**  
   - We can use the Accuracy (Proportion of correctly classified```html
- `seaborn`
Results
After we have been training the model, and the result was quite impressive, with a very high value of the accuracy rate which is a great evidence that Logistic Regression is
