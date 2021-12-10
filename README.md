# <center> AI Project </center>
<center>  <b> Team members: </b> </br>
      Namitha Nagaraju </br>
      Syeda Fatiha Buttul <center> </br>

<center> <b> Under the Guidance of: </b> </br>
          Vahid Behzadan </center> </br>

 <center> <b> Date: </b> </br>
6th December 2021 </center>
</br>
</br>
</br>
</br>

<b> DATA ACQUISITION </b>
</br> Click here to download the data: https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning </br>
<b> Details about the data </b> </br> 
Train data: 1.4 MB
</br> Test data: 14 KB </br>
Total number of rows in training data is 4920 </br>
Total number of rows after sampling in testing data is 2050 </br>
Number of symptoms (Independent variables are 132. Ex: chills, joint_pain, stomach_pain, acidity, ulcers_on_tongue, etc. </br>
Number of diseases to predict (different classes of dependent variable) is 42. Ex: Fungal infection, Allergy, Chronic cholestasis, Drug Reaction, AIDS, Diabetes, etc.
</br></br> <b> DATA CLEANING </b>
</br> For both test and train data 
</br> 1. Checked for outliars
</br> 2. Checked for null values
</br> 3. Checked for erroneous columns
</br> 4. Checked of data is imbalanced
</br> 5. Validated datatypes
</br> 6. Label Encoding
</br> 7. Sampling for test dataset
</br> 8. No scaling was needed

</br></br> <b>  DATA EXPLORATION </b>

<br> <b> Exploring independent variables </br>
![Analysis](https://user-images.githubusercontent.com/64222141/145634540-46415653-3f4a-4a64-ada2-eb31e47100d6.png)

<br> <b> Correlational Analysis:</b> </br>
![Correl](https://user-images.githubusercontent.com/64222141/145634075-eedc666a-f863-4068-be48-9f6679a61c39.png)
<br> <b> Unsupervised Learning: K-means clustering </b>
![Screenshot 2021-12-10 at 2 59 45 PM](https://user-images.githubusercontent.com/64222141/145634394-35ccd1e3-54f3-47ba-95f7-4bacdd47731e.png)

</br>
</br></br> <b>  MODELING </b>
</br>The below are the different models evaluated
</br> 1.Logistic Regression https://en.wikipedia.org/wiki/Logistic_regression
</br> 2.Random Forest Classifier https://en.wikipedia.org/wiki/Random_forest
</br> 3.Support Vector Classifier https://en.wikipedia.org/wiki/Support-vector_machine
</br> 4.K Neighbors Classifier https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm
</br> 5.Decision Tree Classifier https://en.wikipedia.org/wiki/Decision_tree_learning
</br> 6.AdaBoost Classifier https://en.wikipedia.org/wiki/AdaBoost
</br> 7.Bagging Classifier https://www.geeksforgeeks.org/ml-bagging-classifier/
</br> 8.Gradient Boosting Classifier https://en.wikipedia.org/wiki/Gradient_boosting

</br></br> <b> Results </b>
100 % Accuracy for all the models except AdaBoost Classifier

