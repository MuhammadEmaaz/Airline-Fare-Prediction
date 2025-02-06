# **Airline Fare Prediction using Machine Learning** ✈️

## **About the Project**

Predicting airline ticket prices is a complex task that involves understanding various factors such as the airline, route, departure time, duration, and the number of stops. This project uses machine learning algorithms to predict flight fares, providing airlines with insights into pricing strategies, and helping customers make informed decisions when booking flights.

In this project, I built a predictive model using a dataset that contains features like **Airline**, **Route**, **Duration**, **Source/Destination**, **Stops**, and **Price**. By applying machine learning techniques, I aim to predict the price of a ticket based on these features.

---

## **Problem Statement**

Airline ticket prices are influenced by several factors, and predicting the price for a given flight can save costs for both airlines and passengers. However, it remains a complex task due to the variety of variables involved. 

Here are some of the key issues faced:
- **Dynamic Pricing**: Flight prices can vary based on the time of booking, availability, and demand.
- **Multiple Influencing Factors**: Features such as flight duration, airline, and number of stops significantly influence the price.
- **Competition**: Predicting flight prices can give airlines a competitive edge in setting dynamic and profitable fares.

The goal of this project is to build a predictive model that accurately estimates the price of a flight based on these influencing factors.

---

## **Approach - Project Planning & Aims Grid**

### **Project Goals**
- Develop a machine learning model to predict airline ticket prices.
- Analyze key features influencing the price of airline tickets.
- Provide actionable insights for improving fare prediction models.

### **Aims Grid**

| **Objective**                 | **Approach**                                                     |
|-------------------------------|------------------------------------------------------------------|
| **Data Collection**            | Gather and clean the dataset containing airline ticket features.|
| **Data Preprocessing**         | Handle missing values, extract useful features, and encode categorical variables. |
| **Model Development**          | Train and evaluate different machine learning models, including Random Forest. |
| **Results & Recommendations**  | Provide model evaluation metrics and pricing insights for airlines. |

---

## **Technologies Used**

This project utilizes the following Python libraries:

- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical computations.
- **seaborn** & **matplotlib**: For data visualization (graphs and plots).
- **scikit-learn**: For building and evaluating machine learning models (RandomForest, DecisionTree).
- **pickle**: For saving and loading the trained model.
- **Cufflinks**: For interactive plots.

---

## **Trends and Insights**

- **Flight Departure Trends**: 
   - The majority of flights take off in the **Early Morning** and **Evening**, with a lower number in the **Late Night**.
  
- **Price Insights**: 
   - **Longer flights** generally have higher prices, and **premium airlines** charge more than low-cost carriers.
   - The price increase is noticeable when **multiple stops** are involved in the flight.
  
- **Route Analysis**:
   - Certain routes like `CCU → BOM → BLR` and `DEL → BOM → COK` were most frequently used by **Jet Airways**, which may influence pricing due to demand and route popularity.

---

## **Results & Findings**

### **Key Takeaways**:
- **Random Forest Regressor** achieved an **R² score of 81.7%**, indicating that it explains a substantial portion of the variance in flight prices.
- The **MAPE (Mean Absolute Percentage Error)** was around **13.12%**, meaning the model predictions are reasonably accurate.

### **Feature Importance**:
The most influential features on price prediction were:
1. **Airline**: 1.32
2. **Arrival Hour**: 1.14
3. **Duration (hours)**: 1.12
4. **Destination**: 1.06
5. **Departure Hour**: 0.93

---

## **Legal & Ethical Considerations**

- **Data Privacy**: 
   - Ensure compliance with data privacy regulations like **GDPR** if the dataset contains sensitive personal information, though in this case, the dataset seems to be anonymized.
  
- **Bias & Fairness**:
   - Machine learning models, especially those used for pricing predictions, should be carefully evaluated for potential biases, such as over-representation of certain routes or airlines in the dataset.

---

## **Conclusion**

This project successfully implemented a machine learning model to predict airline fares based on various features. The key findings demonstrate the importance of certain features like **Airline**, **Duration**, and **Departure Time** in determining the ticket price. The Random Forest Regressor model, with an **R² score of 81.7%**, performs well and is ready for future deployment.

The complete workflow, including **data cleaning**, **feature extraction**, **outlier detection**, and **model optimization**, ensures a robust predictive model.

---

## **Next Steps:**

1. **Real-time Prediction**: Integrating the model into an online system for real-time pricing predictions based on user inputs.
2. **Hyperparameter Tuning**: Further optimizing the model using grid search or randomized search for better performance.
3. **Incorporating Additional Features**: Include additional features like **weather**, **seasonality**, and **special promotions** to improve accuracy.
4. **API Deployment**: Deploy the model as an API for integrating with other airline systems or websites.

---

## 📜 Legal & Ethical Considerations
- This project ensures compliance with data privacy regulations.
- The dataset was sourced from publicly available repositories.
- No personally identifiable information (PII) is included in the dataset.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request.

## 📧 Contact
For any inquiries, reach out via email: Emaazsiddiq@gmail.com
