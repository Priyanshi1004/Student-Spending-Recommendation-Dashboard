# Student-Spending-Recommendation-Dashboard
This dashboard presents an analysis of college students' spending habits, financial stress levels, savings behavior, and preferences in managing money.

🧾 Student Spending Dashboard
A comprehensive interactive dashboard built using R Shiny to analyze and visualize student spending behavior. This project aims to uncover insights about financial habits, savings patterns, stress indicators, and payment preferences among students across various demographics.

🚀 Features
📊 Overview Tab: Demographic summary of students.
💸 Spending Analysis: Category-wise expenditure trends.
💰 Savings & Stress: Analysis of savings rate and financial stress indicators.
💳 Payment Preferences: Breakdown of preferred payment methods.
📈 Trends & Clusters: Time-based trends and clustering of students using K-means.
📉 Regression Analysis: Explore correlations between spending habits and stress/savings.
📂 Data Table: Filterable table view of raw dataset.
🧠 Recommendations: Smart financial tips based on spending patterns.

📂 Project Structure
bash
Copy
Edit
├── app.R                    # Main Shiny app file
├── www/                    # Custom CSS or image assets (optional)
├── data/
│   └── student_spending.csv  # Input dataset
├── README.md                # Project documentation
└── ...

🛠️ Technologies Used
R
Shiny
Plotly (for interactive plots)
dplyr, ggplot2, tidyverse
K-means Clustering
Regression Models

🧪 How to Run
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/student-spending-dashboard.git
Open the app.R file in RStudio.

Run the app:
R
Copy
Edit
shiny::runApp()

📈 Dataset Info
This dataset contains fictional data representing the spending habits of 1000 students across various demographic groups and academic backgrounds.
The dataset includes information such as age, gender, year in school, major, monthly income, financial aid received, and expenses in different spending categories.
Spending categories include tuition, housing, food, transportation, books & supplies, entertainment, personal care, technology, health & wellness, and miscellaneous expenses.
Additionally, the dataset includes the preferred payment method for each student.
Columns:

Age: Age of the student (in years)
Gender: Gender of the student (Male, Female, Non-binary)
Year in School: Year of study (Freshman, Sophomore, Junior, Senior)
Major: Field of study or major
Monthly Income: Monthly income of the student (in dollars)
Financial Aid: Financial aid received by the student (in dollars)
Tuition: Expenses for tuition (in dollars)
Housing: Expenses for housing (in dollars)
Food: Expenses for food (in dollars)
Transportation: Expenses for transportation (in dollars)
Books & Supplies: Expenses for books and supplies (in dollars)
Entertainment: Expenses for entertainment (in dollars)
Personal Care: Expenses for personal care items (in dollars)
Technology: Expenses for technology (in dollars)
Health & Wellness: Expenses for health and wellness (in dollars)
Miscellaneous: Miscellaneous expenses (in dollars)
Preferred Payment Method: Preferred payment method (Cash, Credit/Debit Card, Mobile Payment App)

📌 Goals
Identify high-spending student segments
Recommend budgeting strategies
Assist educational institutions in understanding student financial well-being

🙋‍♀️ Author
Priyanshi Bhootda

📄 License
This project is licensed under the MIT License.


