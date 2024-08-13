<h1 align="center">
🌍 CO2 Emissions Analysis and Prediction 🚗
  
📈Linear Regression and Regularization Project🚀
</h1>

<p align="center">
  <img src="https://github.com/Duygu-Jones/Machine-Learning-Projects/blob/main/CO2_Emissions_ML_Models/CO2emission.png?raw=true">
</p>

## Executive Summary:

- This project aims to analyse and predict CO2 emissions from vehicles in Canada.
- By examining the dataset, performing Exploratory Data Analysis (EDA), and developing predictive models, we aim to understand the relationships between various factors and CO2 emissions.
- The objective of creating and using a model with the CO2 emission dataset is to build machine learning algorithms capable of accurately predicting vehicle CO2 emissions based on their characteristics.
- By examining variables such as engine size, number of cylinders, and fuel consumption, the aim is to develop models that can evaluate the environmental impact of different vehicles and guide policy decisions aimed at reducing carbon emissions.
- Additionally, these models can support automotive manufacturers in designing more fuel-efficient vehicles and help consumers make informed choices when selecting vehicles with lower carbon footprints.
- Ultimately, the goal is to harness data-driven insights to mitigate the environmental impact of transportation and promote sustainable development.
- _Evaluating model accuracy on both training and test sets is essential to determine whether the model is overfitting or underfitting the data, addressing the bias-variance tradeoff effectively_.

## About the Dataset

- **Dataset**: CO2 Emissions by Vehicle in Canada
- **Content**: Data on CO2 emissions from vehicles with various attributes.
- **Number of Rows**: 1067
- **Number of Columns**: 12

**Inputs:**

- **Make**: Vehicle make
- **Model**: Vehicle model
- **Vehicle Class**: Vehicle class
- **Engine Size**: Engine size (L)
- **Cylinders**: Number of cylinders
- **Transmission**: Transmission type
- **Fuel Type**: Fuel type
- **Fuel Consumption City**: Fuel consumption in city (L/100 km)
- **Fuel Consumption Hwy**: Fuel consumption on highway (L/100 km)
- **Fuel Consumption Comb (L/100 km)**: Combined fuel consumption (L/100 km)
- **Fuel Consumption Comb (mpg)**: Combined fuel consumption (mpg)
- **CO2 Emissions**: CO2 emissions (g/km)

## The project consists of two main phases:

1. **Exploratory Data Analysis (EDA)**:

- Analyze CO2 Emission Patterns
- Assess the Impact of External Factors
- Feature Engineering

2. **Machine Learning Model**:
   - Simple Linear Regression Model
   - Multiple Linear Regression Model
   - Polynomial Regression Model
   - Scaling the Data
   - Regularization
     - Ridge regression was evaluated with cross-validation and GridSearchCV was used to choose the best alpha value.
     - Lasso regression was also evaluated similarly, with GridSearchCV used for parameter tuning.
   - Final Model and Prediction
   - Feature Importances: The importance of features was analyzed using Ridge and Lasso regression techniques.

*As this dataset was compiled for analytical and educational purposes, each phase of the project was broken down into beginner-friendly steps and explained in detail to ensure a thorough understanding.*

## Key Insights and Conclusions:

1. **Fuel Consumption and Emissions**: Higher fuel consumption (L/100 km) directly results in higher CO2 emissions.
2. **Engine Size Impact**: Vehicles with larger engine sizes and more cylinders produce more CO2 emissions.
3. **Fuel Type Differences**: CO2 emissions vary significantly depending on the fuel type used.
4. **Fuel Efficiency (mpg)**: Vehicles with higher miles per gallon (mpg) are more fuel-efficient and emit less CO2.

## Recommendations:

#### Machine Learning Perspective:

To further improve the analysis and model performance:

- Integrate real-time data and additional external factors to enhance prediction accuracy.
- Experiment with different machine learning algorithms and hyperparameter tuning to find the best-performing model.
- Consider deploying the model for dynamic CO2 emission adjustments based on predictions.

#### Business Perspective:

1. **Regulatory Advocacy**: Advocate for policies that tax high-emission vehicles and provide incentives for low-emission vehicles.
2. **Product Design**: Focus on designing vehicles with optimized engine sizes and higher fuel efficiency (mpg) to reduce emissions.
3. **Consumer Education**: Inform consumers about the benefits of fuel-efficient vehicles and their positive impact on the environment.

---

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*
**Kaggle Notebook:** [CO2 Emissions (EDA and ML) Linear Regression](https://www.kaggle.com/code/duygujones/co2-emissions-analysis-and-prediction)

 - This dataset is available to download on the Kaggle website: [CO2 Emissions_Canada.csv](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)
 - Acknowledgements: Official open data website of Canada Government [Link](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6)

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
