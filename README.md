
# 📈 E-Commerce Customer Spending Analysis

# 🧾 Overview

* This project aims to help an eCommerce company determine whether to invest more in its mobile app or website to improve customer spending. The dataset contains customer data including usage metrics and their yearly amount spent. We perform EDA and linear regression modeling to identify key features influencing spending.


---

# 📂 Dataset

**The dataset includes the following features:**

* Avg. Session Length: Average session time in minutes.

* Time on App: Time spent on the company’s mobile app.

* Time on Website: Time spent on the website.

* Length of Membership: Total years as a customer.

* Yearly Amount Spent: Target variable (customer’s yearly spending).

* Plus: Email, Address, Avatar (non-numeric, not used in modeling).



---

# 🛠️ Technologies Used

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn



---

# 📊 Exploratory Data Analysis (EDA)

* Pairplots revealed positive correlations between Time on App, Length of Membership, and Yearly Amount Spent.

* Time on Website showed weaker correlation.

* A strong linear trend was observed between Length of Membership and spending.



---

# 🧮 Model Summary
**A Linear Regression model was built using the following predictors:**

* Avg. Session Length

* Time on App

* Time on Website

* Length of Membership

**Model Performance:**

* MAE: 8.43

* MSE: 103.92

* RMSE: 10.19


* Residuals showed a near-normal distribution, indicating a good model fit.


---

# ✅ Business Recommendations

**Based on model insights:**

1. Invest in Mobile App Development

* The coefficient for Time on App (38.60) is significantly higher than for Time on Website (0.46).

* This suggests that increasing app engagement has a stronger impact on revenue.



2. Customer Loyalty Matters

* Length of Membership has the highest coefficient (61.67), indicating that retaining customers leads to more spending.

* Suggests focusing on loyalty programs, personalized offers, or membership perks.



3. Website Experience is Less Influential

* The website has the weakest relationship with spending. Improvements may not yield as much return unless targeting specific user segments.



4. Session Optimization

* Avg. Session Length also contributes positively to spending.

* Ensure both app and web interfaces encourage longer, meaningful sessions (e.g., better UX, product discovery features).



