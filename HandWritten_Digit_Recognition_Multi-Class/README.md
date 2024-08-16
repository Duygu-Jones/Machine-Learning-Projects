<h1 align="center">
Predicting Income Levels with ML Classification Models💰💹
  
Logistic Regression - SVM - KNN📈💵
</h1>

<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/Income_Classification_ML_Models/income2x.png?raw=true"
">
</p>

## Introduction

This project aims to predict whether an individual's annual income exceeds $50,000 using the "Adult" dataset from the 1994 Census Bureau.
- The performance of four machine learning models—Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) — developed and compared. 
-  Data preprocessing, model training, evaluation, and comparison were conducted to identify the best-performing model for this classification task.

### Objectives

1. **Data Preprocessing**: Clean and encode data and handle missing values.
2. **Model Development**: Implement Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM).
3. **Model Training and Evaluation**: Train models on the training set and evaluate performance using accuracy, precision, recall, and F1-score metrics.
4. **Model Comparison**: Compare models to identify the best performer.
5. **Conclusion**: Summarized findings and provided recommendations for improvement.

*The dataset and results are used for educational purposes, demonstrating the application of advanced machine learning techniques on real-world data. We aim to build effective machine-learning models to predict adults' income and gain a deeper understanding of machine-learning techniques.*

## About the Dataset

The dataset is a commonly used dataset known as the "Adult" dataset or "Census Income" dataset. It is primarily used for machine learning tasks, particularly classification. The goal is often to predict whether an individual earns more than $50,000 a year based on various demographic and employment-related attributes

The dataset is available on [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/adult-census-income)

**Dataset:** Census Adult Income

- **Content**: Data on various demographic and employment-related attributes of individuals.
- **Number of Rows**: 32,561
- **Number of Columns**: 15

**INPUTS**

| No | Feature            | Description                                                                              |
|----|--------------------|------------------------------------------------------------------------------------------|
| 1  | **age**            | Integer value representing the age of the individual.                                    |
| 2  | **workclass**      | Categorical variable indicating the type of employer (e.g., Private, Self-emp-not-inc, etc.). |
| 3  | **fnlwgt**         | Continuous variable representing the final weight, which is a proxy for the number of people represented by the individual. |
| 4  | **education**      | Categorical variable indicating the highest level of education achieved (e.g., Bachelors, HS-grad, etc.). |
| 5  | **education.num**  | Integer value representing the numerical encoding of education levels.                   |
| 6  | **marital.status** | Categorical variable indicating the marital status of the individual (e.g., Married-civ-spouse, Divorced, etc.). |
| 7  | **occupation**     | Categorical variable representing the individual's occupation (e.g., Tech-support, Craft-repair, etc.). |
| 8  | **relationship**   | Categorical variable representing the individual's relationship status within a family (e.g., Wife, Own-child, etc.). |
| 9  | **race**           | Categorical variable indicating the race of the individual (e.g., White, Black, etc.).   |
| 10 | **sex**            | Categorical variable indicating the gender of the individual (Male or Female).           |
| 11 | **capital.gain**   | Continuous variable representing the capital gains received by the individual.           |
| 12 | **capital.loss**   | Continuous variable representing the capital losses incurred by the individual.          |
| 13 | **hours.per.week** | Continuous variable indicating the number of hours the individual works per week.        |
| 14 | **native.country** | Categorical variable representing the country of origin for the individual (e.g., United-States, Mexico, etc.). |
| 15 | **income**         | Categorical variable indicating the income category of the individual (<=50K or >50K).   |

*The dataset is often used for predictive modelling to understand how different demographic and employment factors relate to income levels. It contains both categorical and continuous variables, making it a versatile dataset for various types of machine-learning algorithms.*

## Details About the Dataset

This dataset was extracted from the 1994 [Census Income Bureau database](https://www.census.gov/en.html) by Ronny Kohavi and Barry Becker. It contains clean records meeting specific criteria, such as age greater than 16 and hours worked per week greater than zero. The main goal is to predict whether an individual earns more than $50K per year.

**Description of `fnlwgt` (Final Weight):** To understand the dataset's origin, extraction conditions, and the methodology behind the `fnlwgt` feature.
The `fnlwgt` feature represents weights controlled to independent estimates of the civilian noninstitutional population of the US, prepared monthly by the Census Bureau's Population Division. The weighting program uses three sets of controls:

1. Population aged 16+ for each state.
2. Hispanic origin by age and sex.
3. Race by age and sex.

These controls are applied multiple times to ensure accuracy. The weights ensure that people with similar demographic characteristics have similar weights, but this is only applicable within each state due to the sampling method.

### Relevant Papers

- Ron Kohavi, [Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid](https://www.researchgate.net/publication/2669468_Scaling_Up_the_Accuracy_of_Naive-Bayes_Classifiers_a_Decision-Tree_Hybrid), Proceedings of the Second International Conference on Knowledge Discovery and Data Mining, 1996.

----

## Conclusion:

**Final Model:** SVM Model

*Parameters:*
- recall: 85,  
- F1: 0.87   
- PRC: 0.76  
---

In this project, we used logistic regression, SVM, and KNN models to predict income levels on an unbalanced dataset. We focused on F1 and recall scores to evaluate performance, as they are critical in **unbalanced datasets** where the minority class (higher income) is key.

### Why SVM was Chosen:
- **Balanced Performance**: The SVM model achieved a strong balance between precision and recall, with an F1 score of 0.87 and a recall of 0.85 on the test set. This makes it effective at identifying high-income individuals while keeping false positives low.
- **Consistency**: SVM showed stable performance across training and test sets, indicating good generalization without overfitting.

### Importance of F1 and Recall:
- **F1 Score**: This metric combines precision and recall, ensuring the model performs well with both false positives and false negatives in mind.
- **Recall**: Prioritizing recall ensures we capture most high-income individuals, which is vital in unbalanced datasets.

📌 In short, the SVM model’s balanced precision and recall, along with its consistent performance, make it the best choice as the final model for predicting income levels.

💹 It’s possible that with further parameter tuning, even better performance could be achieved, which could be worth exploring.


### Key Insights:
- **Education and Occupation**: Higher education and certain occupations (e.g., executive roles) are strong predictors of higher income.
- **Marital Status and Work Hours**: Being married and working more hours are linked to higher income, though the effect of work hours plateaus.

### Recommendations:
- **Policy Interventions**: Focus on improving access to higher education and closing the gender wage gap.
- **Model Refinement**: Enhance models by incorporating additional features and exploring advanced techniques for better accuracy.

---

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook:** [💵Income Classification (Logistic-KNN-SVM)💰](https://www.kaggle.com/code/duygujones/income-classification-logistic-svm-knn)
 - The dataset is available to download on the Kaggle website / UCI Machine Learning Repository: [Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income)

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
