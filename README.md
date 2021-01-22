# Relationship-between-Weather-and-Traffic-Events-using-Machine-Learning-Algorithms
Analyzing and visualizing effect of weather event on traffic events in New York State in USA

## This was a project I chose to do in my course Machine Learning and Data Analytics
## in Civil Engineering Applications(CE784A) under Dr. Pranamesh Chakraborty

-> Here we explored two large datasets contains around 33 milion data. <\br>
-> First we cleaned the traffic and weather data seperately and filtered out
   the required columns from the two datasets. <\br>
-> In the next phase, we visualize the data and discard the outliers from the datasets
   gor more generalizationns. <\br>
-> Then we combined the two datasets in a single dataset and sort it by start time of the events. <\br>
-> In the next step, we discard the weather events spanning less than 15 minutes (Thresold Time)
   [Hyperparameter] as we assumed that there will be no effect of weather on traffic events 
   if it spanned less than the thresold time. <\br>
-> After that, we added a column which reflect if a weather or traffic event influenced
   other evnets. <\br>
-> Created a balanced training,test and validation datasets and fed it to our machine learning
   models to predict if there will be traffic event influced by a weather or traffic event. <\br>
-> Three models are used **Logistic Regression** , **Support Vector Machine(SVM)** , and
   **Multilayer Perceptron(MLP)** . <\br>
-> Atlast we built a tree structure using python to visualize the effects of various event
   on other events. <\br>

### For more information, please check out the documentation file.

* Cleaned and merged weather and traffic datasets in chronological order consists of 33.1 million events. <\br>
* Processed the dataset and extract feature vector and target variable to feed our ML models. <\br>
* Trained the model with Logistic Regression, Support Vector Machine and MLP classifier. <\br>
* Prepared a tree structure to visualize the patterns of effect of one event on another event. <\br>
