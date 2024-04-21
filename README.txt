Ecommerce Company Analysis
Overview
This project aims to help an Ecommerce company based in New York City determine whether they should focus their efforts on improving their mobile app experience or their website. The company offers both in-store style and clothing advice sessions as well as online shopping options through their mobile app and website. By analyzing customer data, including time spent on the app or website, annual income, and other relevant metrics, this project seeks to provide insights into the factors that influence customer spending behavior.

Dataset
-The dataset used for this analysis contains fake customer data, including the following variables:

-Time_on_website: The amount of time (in minutes) spent by the customer on the company's website.
-Time_on_app: The amount of time (in minutes) spent by the customer on the company's mobile app.
-Avg_session_length: The average session length (in minutes) of the customer's style and clothing advice sessions.
-Annual_income: The annual income (in dollars) of the customer.
-Spending_score: A score assigned to each customer based on their spending behavior.
Analysis
-To determine the relationship between customer behavior and spending, a linear regression model was built using Python and the scikit-learn library. The model predicts the spending score of a customer based on the features mentioned above.

Results
-The analysis revealed the following insights:

-The time spent on the mobile app has a stronger positive correlation with spending score compared to the time spent on the website.
-Annual income also has a positive correlation with spending score, indicating that customers with higher incomes tend to spend more.
-Average session length did not show a significant impact on spending score in this analysis.

Recommendations
-Based on these findings, the company may consider prioritizing improvements to the mobile app experience to enhance customer engagement and increase spending. Additionally, targeted marketing strategies could be implemented to attract high-income customers to the mobile app.

Files
-ecommerce_analysis.ipynb: Jupyter Notebook containing the code for data analysis and model building.
-ecommerce_data.csv: Fake customer data used for analysis.
Dependencies
-Python 3.x
-pandas
-NumPy
-scikit-learn
-Matplotlib
-seaborn
Usage
-Clone this repository to your local machine.
-Install the necessary dependencies listed above.
-Open ecommerce_analysis.ipynb in a Jupyter Notebook environment.
-Follow the instructions in the notebook to execute the code cells and reproduce the analysis.