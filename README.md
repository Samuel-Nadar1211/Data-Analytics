# Heart-Disease-Diagnostic
- Health is real wealth.
- In the pandemic time we all realized the brute effects of covid-19 on all irrespective of any status.
- Heart disease is a leading cause of death worldwide, impacting millions of people annually.
- Heart disease imposes a significant economic burden due to healthcare costs and loss of productivity.
- Increasing awareness and education about heart disease is crucial for prevention and early detection.
- To analyse the health and medical data for better future preparation.

### Correlation
* resting blood pressure, serum cholestoral in mg/dl, fasting blood sugar > 120 mg/dl, resting electrocardiographic results have weak correlation with heart disease (0 - 0.15)
* age and sex have moderate correlation with heart disease (0.15 - 0.3)
* chest pain, maximum heart rate achieved, exercise induced angina, oldpeak, the slope of the peak exercise ST segment, number of major vessels colored by flourosopy, thal have good correlation with heart disease (0.3 - 0.5)
* <strong>Few Interesting Correlation</strong>
  * exercise induced angina with chest pain
  * maximum heart rate achieved with slope of the peak exercise ST segment, exercise induced angina, age
  * oldpeak with the slope of the peak exercise ST segment [very good], maximum heart rate achieved

### Observation
- Around 48.68% of people have heart disease
- Gender 0 (72.44%) tend to have more heart disease than gender 1 (42.08%)
- At around age of 41 to 50, people tend to have more heart disease (67.21%) and above age of 60 people tend to have less heart disease (40.81%)
- Type 0 chest pain mostly does not imply heart disease. Type 2 chest pain is the mostly observed in case of heart disease
- In case of heart disease, the slope of the peak exercise ST segment is mostly 2. The slope being 1 mostly implies the absence of heart disease
- In case of heart disease, generally none of major vessels are coloured by fluoroscopy
- Reversible defect in thalassemia has higher chance of heart disease
- Presence of Exercise induced angina generally implies the absence of heart disease
- In case of exercise induced angina, chest pain is mostly of type 0
- In case of heart disease maximum heart received achieved is elevated
- In case of slope of the peak exercise ST segment being 2 the maximum heart received achieved is more than slope of the peak exercise ST segment being 1
- In absence of exercise induced angina maximum heart received achieved is elevated
- Maximum heart rate achieved is less in case of chest pain type 0
- As age increases, maximum heart rate achieved decreases
- In case of heart disease oldpeak is depressed with a higher chance of being 0
- Oldpeak reduces with maximum heart rate achieved

### Performance of Machine Learning Classification Model
LightGBM, XGBoost, Gradient Boosting Classifier, Support Vector Machine > Random Forest Classifier > Neural Networks > Logistic Regression > Naive Bayes

### Dashboard
![Screenshot 2024-07-22 161534](https://github.com/user-attachments/assets/2394d548-fcdd-4ad7-86d8-11475405961a)


# Crop-Production-Analysis
* The Agriculture business domain, as a vital part of the overall supply chain, is expected to highly evolve in the upcoming years via the developments, which are taking place on the side of the Future Internet.
* This dataset provides a huge amount of information on crop production in India ranging from several years.

### Formula
- Crop Density = Crop Production / Land Area
- Crop Production α Land Area

### Observation
- A major drought was present at 2002
- Kerala has highest production of crop
- Uttar Pradesh has highest land area for crop production
- Production of crops has an increasing trend whereas land area has decreasing trend
- Rabi and Kharif are the major seasons of whole country
- Rice and Wheat are produced in large area
- Coconut and Sugarcane has the highest production
- Coconut is Kharif or whole season crop majorly produced in southern states, mainly in Kerala
- Whole Year Crops and Winter Crops tend to have higher crop density

### Performance of Machine Learning Regression Model
XGBoost > LightGBM > Random Forest Regressor > Decision Tree Regressor > Neural Networks > Linear Regressor > Linear Support Vector Regressor

### Dashboard
![Screenshot 2024-07-22 163359](https://github.com/user-attachments/assets/9f628033-300a-431e-8d8d-dee1fa2ea21c)


# Analyzing-Amazon-Sales
* Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits.
* Sales management today is the most important function in a commercial and business enterprise.

### Relation
- Unit Price * Units Sold == Total Revenue
- Unit Cost * Units Sold == Total Cost
- Total Revenue - Total Cost == Total Profit

### Evaluation Metric
Profitability Ratio =  Total Profit / Sales

### Linear Regression
Unit Price = 1.2358 * Unit Cost + 40.6587

### Performance of Machine Learning Regression Model
XGBoost Regressor > Random Forest Regressor > LightGBM Regressor > Linear Regression > Support Vector Regressor > Decision Tree Regressor > Neural Network (due to less dataset)

### Maximal Frequent Itemsets
* {'Beverages', 'Clothes', 'Cosmetics’}
* {'Cereal', 'Clothes', 'Cosmetics’}
* {'Office Supplies', 'Clothes', 'Fruits', 'Cosmetics’}
* {'Clothes', 'Personal Care', 'Household', 'Cosmetics'}

### Association Rule
* (Clothes, Personal Care) -> (Cosmetics, Household)
* (Clothes, Household) -> (Personal Care, Cosmetics)
* (Personal Care, Cosmetics) -> (Clothes, Household)
* (Cosmetics, Household) -> (Clothes, Personal Care)

### Dashboard
![Screenshot 2024-07-30 195419](https://github.com/user-attachments/assets/a69401b4-5801-4fef-b488-68dd3f9ea416)