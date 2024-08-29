<h1 align="center">
🚢Titanic Survival Prediction: <br> ⚓ Advanced Ensemble ML Models for Improved Accuracy📈
</h1>

<h3 align="center"> Decision Tree - Random Forest - AdaBoost - Gradient - XGBoost - LightBoost - CatBoost - Stacking </h3>


<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/Titanic_ML_Boosting_Models/img/titanic_gif2.gif?raw=true"
</p>

<h3 align="center"> The Story Behind This Notebook: My Titanic Data Journey </h3>

Welcome to this advanced notebook, where I take you on a deep dive into the Titanic dataset to explore and predict survival outcomes. This project is meticulously structured, with each step carefully documented and explained in the Table of Contents. Whether you're curious about data preprocessing or machine learning, you'll find valuable insights throughout.

One of the most exciting parts of this project for me was handling missing values. I dedicated a lot of time to this, including extensive research into Titanic’s historical records, watching documentaries, and even revisiting the iconic film. This thorough understanding of the data and its context allowed me to take a detailed approach to imputation and feature engineering, making this notebook a valuable resource for anyone looking to master these skills.

In the data preprocessing phase, innovative encoding techniques were applied, setting the stage for model training. Then explored eight different machine learning models, including Decision Trees, Random Forest, AdaBoost, Gradient Boosting, XGBoost, LightBoost, CatBoost, and Stacking. Each model was fine-tuned, results were compared, and the reasoning behind the final choices was clearly explained.

Finally, after carefully comparing the models, a final model was selected and used for the competition submission. 
    
*This journey is not only a technical exploration but also a reflection of my curiosity and excitement that drove the research, making this project both informative and engaging.*<br>
*If you have any suggestions for improving this notebook, please comment or fork it to try your own ideas, or any questions feel free to ask in the comments.*

<h4 align="center">  Thanks for joining me on this journey—Happy Trails! </h4>

---


## About the Project
<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/Titanic_ML_Boosting_Models/img/titanicX2.png?raw=true"
</p>
  
The goal of this project is to build a predictive model that identifies the characteristics and conditions associated with a higher likelihood of survival.   
 The Titanic disaster revealed that survival was influenced by a range of factors, such as class, age, and gender.    
 Using the available passenger data, the project aims to predict who was more likely to survive based on passenger information.  


## About the Dataset

The sinking of the Titanic is one of the most well-known maritime disasters in history. 

 The RMS Titanic was a British ship that sank on April 15, 1912, after hitting an iceberg during its maiden voyage. Despite being known for its luxury and being deemed “unsinkable,” the ship lacked enough lifeboats for all passengers. This tragic disaster resulted in the deaths of over 1,500 people out of 2,224 on board.
The Titanic dataset includes details about the passengers, such as their age, class, and whether they survived.  
    
 *The Titanic dataset is commonly used to train and evaluate machine learning models for predicting survival outcomes, making it ideal for classification tasks in data science.*
    
    
- **Dataset:** Titanic Dataset  
- **Content:** Data on various attributes of Titanic passengers, including demographic and ticket information.  
- **Number of Rows:** 891  
- **Number of Columns:** 12 (11 features + 1 class label)  

| **INPUTS**         | **Description**                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------|
| **PassengerId**    | Unique identifier for each passenger.                                                                 |
| **Pclass**         | Passenger class (1, 2, or 3).                                                                         |
| **Name**           | Name of the passenger.                                                                               |
| **Sex**            | Gender of the passenger (male or female).                                                             |
| **Age**            | Age of the passenger in years.                                                                        |
| **SibSp**          | Number of siblings or spouses aboard the Titanic.                                                     |
| **Parch**          | Number of parents or children aboard the Titanic.                                                     |
| **Ticket**         | Ticket number of the passenger.                                                                       |
| **Fare**           | Fare paid by the passenger.                                                                          |
| **Cabin**          | Cabin number where the passenger stayed.                                                              |
| **Embarked**       | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).                                 |
| **Survived**       | Categorical variable representing the survival status (0 = No, 1 = Yes).                              |


**Reference:**
 Will Cukierski. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic

 ## 🔍 **Key  Steps:**
- **Data Exploration:** Detailed analysis and handling of missing values with insights drawn from historical records and even the Titanic movie!
- **Feature Engineering:** Creative and effective strategies to enhance model performance.
- **Modeling:** I trained and fine-tuned 8 different models, including Decision Trees, Random Forest, AdaBoost, Gradient Boosting, XGBoost, LightBoost, CatBoost, and Stacking, to find the best fit.
- **Final Model Selection:** After rigorous comparison, I selected the most balanced and accurate model for final submission.



----

## Conclusion:

In this project, we used AdaBoost, Gradient Boosting, XGBoost, Stacking, Random Forest, Decision Tree, CatBoost, and LGBM Boost models to predict survival outcomes on the Titanic dataset, which is inherently imbalanced.

- Although the initial focus was on Recall and Precision-Recall scores due to the nature of imbalanced datasets, the competition prioritizes **Accuracy** as the key metric.
-  The results were derived from both cross-validation on the training data and a separate evaluation using an example submission dataset. Here, we focus on comparing AdaBoost and LGBM Boost to determine the most suitable model.

### Model Selection Based on Results:

- **Strong Overall Performance**: LGBM Boost has a solid accuracy score of 0.821, making it highly reliable. While AdaBoost slightly edges out in accuracy at 0.827, LGBM Boost offers a better balance across key metrics like Precision-Recall and ROC AUC. This means LGBM Boost is not just accurate but also more consistent in identifying survivors correctly while minimizing errors.

- **Balanced Metrics**: LGBM Boost's performance across various metrics shows that it's not only good at making correct predictions but also at maintaining a balance between catching true survivors and avoiding false positives. This balance makes it a more robust and dependable model.

### Metric Importance:

- **In the context of this competition**, accuracy is the critical metric because it measures the percentage of passengers correctly classified, aligning with the competition's objective to maximize correct predictions.

- **In typical scenarios with imbalanced datasets**, Recall and Precision-Recall might be prioritized, especially when the minority class represents high-risk cases (e.g., survivors, high-risk patients). In such cases, focusing on recall reduces the risk of missing critical instances, even at the cost of some accuracy.

### Business Impact:

  - For the competition, prioritizing accuracy leads to higher overall correct predictions, aligning with the evaluation criteria. However, in real-world applications where missing key cases could be costly, models might need to focus more on recall. This ensures critical cases are identified, leading to better decision-making and resource allocation.

  - **Balanced Decision-Making**: By selecting LGBM Boost, the model provides a reliable framework for making well-rounded decisions, particularly in scenarios where both accuracy and the balance between precision and recall are important. This could be crucial in applications such as customer retention, fraud detection, or medical diagnostics, where misclassifications can have significant consequences.

- **Optimizing Outcomes**: The balanced performance of LGBM Boost ensures that the model can effectively capture the right cases (survivors) without over-committing to false positives, leading to more informed and effective resource allocation and decision-making.

### Result:

**LGBM Boost** is the final model of choice due to its strong accuracy and balanced performance across other critical metrics. While AdaBoost offers slightly higher accuracy, LGBM Boost provides a more comprehensive and reliable performance profile, making it the optimal choice for predicting survival outcomes on the Titanic dataset and for broader applications where balanced model performance is crucial.

---

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Titanic Prediction-Advanced Ensemble ML Models🚢⚓](https://www.kaggle.com/code/duygujones/titanic-prediction-advanced-ensemble-ml-models)
 - The dataset is available to download on the Kaggle: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
 - Relevant Paper: Will Cukierski. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic 

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Duygu Jones, a Data Scientist, passionate about data analysis, and machine learning.

♻️ You can find more about me and my work through the following links:

- **Linkedin**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)

🌐Feel free to connect with me!

<br>

🎯 Enhance your machine learning skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---

##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
