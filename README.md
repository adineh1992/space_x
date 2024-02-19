Classification ML Model Project- space x
Overview
Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a rocket launch. Here we will create a machine learning pipeline to predict if the first stage will land or not. we have used 5 machine learning models: LogisticRegression - KNeighborsClassifier - SVC – DecisionTreeClassifier and RandomForest. The data for this project was sourced from Space X website.
Handling Missing Values
First, we addressed the missing values, ensuring the integrity and reliability of our dataset for model training.
Handling Imbalanced Dataset
The challenge of an imbalanced dataset was mitigated through oversampling methods, to ensure our model's performance is not biased towards the majority class.
Algorithms Used
In this project, we utilized a range of algorithms to develop the classification model, including Random Forest, SVM, Logistic Regression, Decision Tree, KNN. These were chosen based on their ability to handle the specifics of our dataset and the prediction task.
Model Evaluation and Selection
GridSearch Usage
We leveraged GridSearch to fine-tune our models, which significantly improved the model's accuracy. The accuracy of the model before and after using GridSearchCV is documented in our results section, showcasing the effectiveness of hyperparameter optimization.
Best Performing Model
The best-performing model was identified as SVM, which achieved the highest accuracy (100%) and performance metrics, including a detailed ROC curve analysis. The ROC curve further illustrates the model's ability to discriminate between classes effectively.

