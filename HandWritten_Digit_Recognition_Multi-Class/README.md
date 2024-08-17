<h1 align="center">
Handwritten Digit Recognition with ML Classification Models🔢📝
  
SVM - Random Forest - Decision Tree 📈⚙️
</h1>

<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/HandWritten_Digit_Recognition_Multi-Class/img/digits2x.png?raw=true"
">
</p>

## Introduction

The goal of this project is to accurately classify handwritten digits using a dataset of digit samples. The dataset comprises a sequence of 16 features representing various characteristics of the handwritten digits.

<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/HandWritten_Digit_Recognition_Multi-Class/img/digits3.png?raw=true"
">
</p>


## Problem Statement
The accurate classification of handwritten digits is a critical task in the field of computer vision, with applications ranging from automated postal mail sorting to digit recognition in educational tools. Despite the availability of advanced machine learning techniques, achieving high accuracy in digit classification remains challenging due to variations in handwriting styles, sizes, and shapes. 

This project aims to address this challenge by developing and evaluating three machine learning models—Support Vector Machine (SVM), Random Forest, and Decision Tree—to classify handwritten digits based on their trajectory characteristics. The goal is to determine which model performs best in terms of accuracy, precision, recall, and F1-score, thereby providing a robust solution for digit recognition tasks.

The outcomes of this study will contribute to the understanding of model performance on image-based data and may be applied in various practical scenarios requiring digit recognition.


## Objectives

- **Data Preprocessing:** Clean and prepare the data for model training.
- **Model Development:** Implement Support Vector Machine (SVM), Random Forest, and Decision Tree classifiers.
- **Model Training and Evaluation:** Train the models on the training set and evaluate their performance using metrics such as accuracy, precision, recall, and F1-score.
- **Model Comparison:** Compare the models to identify the best performer in terms of classification accuracy and generalization.
- **Conclusion:** Summarize the findings and provide recommendations for potential improvements.

*The dataset and results are used for educational purposes, demonstrating the application of machine learning techniques on image-based data. The aim is to build effective machine-learning models to classify handwritten digits and to gain a deeper understanding of these techniques.*


## About the Dataset

The dataset consists of samples of handwritten digits, where each sample is represented by a set of 16 features derived from the digit's trajectory. These features capture various aspects of the digit's shape and movement during writing.

- **Dataset:** Handwritten Digits Dataset
- **Content:** Data on various features extracted from handwritten digits.
- **Number of Rows:** 10992
- **Number of Columns:** 17 (16 input features + 1 class label)


| **INPUTS**      | **Description**                                                                                     |
|-----------------|-----------------------------------------------------------------------------------------------------|
| **input1-input16** | Integer values representing different characteristics of the digit's trajectory, such as coordinates and angles. |
| **class**       | Categorical variable representing the digit label (0-9).                                            |


The dataset is commonly used for training and evaluating machine learning models to recognize handwritten digits, making it an ideal candidate for classification tasks in computer vision.


**Relevant Paper:**
- Alimoglu, F., & Alpaydin, E. (1997, August). Combining multiple representations and classifiers for pen-based handwritten digit recognition. In Proceedings of the Fourth International Conference on Document Analysis and Recognition (Vol. 2, pp. 637-640). IEEE. DOI: 10.24432/C5MG6K  
----

## Conclusion:

**Final Model:** SVM Model with GridSearchCV 

*Parameters:*
- Accuracy: 0.993 
- f1: 0.993   
- Incorrect Predictions: 8
---

**Overall:**

In this project, we used SVM, Random Forest, and Decision Tree models to classify handwritten digits based on coordinate-based features. Given the complexity of the dataset, we prioritized accuracy and F1 scores to evaluate model performance, ensuring both precision and recall were balanced.

- **SVM Model**: Demonstrates the highest performance with both accuracy and F1 scores at 0.993.
- **Random Forest (RF) Model**: Follows closely behind SVM with accuracy and F1 scores of 0.978.
- **Decision Tree (DT) Model**: Shows the lowest performance among the three, with accuracy at 0.956 and F1 score at 0.957.

**Final Model Selection:**

Based on the results, the **SVM model** was selected as the final model. It consistently outperforms the other models in both accuracy and F1 score, indicating its strong ability to generalize and accurately classify the data.

**Reason:**

- **High Accuracy and F1 Score**: The SVM model achieves the highest accuracy and F1 score, which suggests it is the best at both correctly predicting the class labels (accuracy) and balancing precision and recall (F1 score).
  
- **Data Characteristics**: Given the nature of the dataset, which involves complex patterns due to high-dimensional coordinate-based features, SVM's ability to find an optimal hyperplane in high-dimensional space makes it particularly effective.

- **Importance of F1 Score**: The F1 score is especially important in cases where the dataset may be imbalanced, ensuring that the model is not only accurate but also effective at managing false positives and false negatives. SVM excels in this regard, as shown by its top F1 score.
---

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Handwritten Digit Recognition-SVM-DT-RF🔢📝](https://www.kaggle.com/code/duygujones/handwritten-digit-recognition-svm-dt-rf)
 - The dataset is available to download on the Kaggle: [Handwritten_Digits_Recognition](https://www.kaggle.com/datasets/duygujones/pen-based-handwritten-digit)
 - Relevant Paper: [Pen-Based Recognition of Handwritten Digits-Article](https://archive.ics.uci.edu/dataset/81/pen+based+recognition+of+handwritten+digits)

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
