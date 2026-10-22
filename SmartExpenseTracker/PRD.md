
# Project Requirement Document (PRD)

## Project Title
Development of a Smart Expense Tracker with Machine Learning-Based Monthly Spending Prediction for University Students

## 1. Project Overview
The Smart Expense Tracker is a web-based application designed to help university students manage their personal expenses. The system allows users to record expenses, monitor monthly budgets, view spending reports, and predict their total spending for the following month using machine learning.

## 2. Background
University students need to manage expenses such as food, transportation, education, accommodation, and entertainment. Some students may struggle to track their spending and plan their monthly budgets. A smart expense tracker can help students understand their spending habits and make better financial decisions.

## 3. Problem Statement
- Students may find it difficult to track daily expenses when relying on memory or manual records.
- Poor expense management may cause students to overspend or exceed their monthly budgets.
- Basic expense-tracking systems may focus on past spending without predicting future expenses.
- Students may need a simple system that combines expense tracking, budget monitoring, and spending prediction.

## 4. Project Objectives
- To identify the requirements for a student expense-tracking system.
- To develop and compare machine learning models for monthly spending prediction.
- To develop a web application for expense recording, budget monitoring, and spending reports.
- To evaluate the prediction performance and functionality of the system.

## 5. Target Users
The primary target users are university students who want to manage their daily expenses and monthly budgets. The system is designed for students who prefer a simple way to record spending and monitor their financial situation.

## 6. Functional Requirements
The system must provide the following functions:

- **FR01:** Allow users to register and log in.
- **FR02:** Allow users to add, edit, and delete expense records.
- **FR03:** Allow users to categorise expenses, such as food, transport, education, and entertainment.
- **FR04:** Allow users to set a monthly budget.
- **FR05:** Display monthly spending summaries using charts and reports.
- **FR06:** Provide warnings when spending approaches or exceeds the monthly budget.
- **FR07:** Predict the user's total spending for the following month using machine learning.
- **FR08:** Allow users to view their previous expense records.
- **FR09:** Allow users to filter expenses by date and category.
- **FR10:** Allow users to manage their expense categories if this feature is included in the final design.

## 7. Non-Functional Requirements
- **Usability:** The interface should be simple and easy to understand.
- **Security:** The system should protect user login details and personal expense records.
- **Performance:** The system should display summaries and predictions within an acceptable response time.
- **Reliability:** The system should save expense records correctly.
- **Maintainability:** The source code should be organised and easy to update.
- **Compatibility:** The web application should work on commonly used modern web browsers.

## 8. Proposed Technologies
| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Python Flask |
| Database | MySQL |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas and NumPy |
| Charts | Chart.js |
| Development Tool | Visual Studio Code |
| Version Control | Git and GitHub |

## 9. Project Scope
The project will focus on developing a web-based expense tracker for university students. The system will support manual expense recording, expense categorisation, monthly budget setting, spending reports, budget warnings, and monthly spending prediction.

## 10. Project Limitations
- Users must enter their expenses manually.
- The system will not connect directly to bank accounts.
- Prediction accuracy may be limited when historical expense data is insufficient.
- The system will not provide professional financial advice.
- The accuracy of predictions will depend on the quality and quantity of available data.

## 11. Machine Learning Requirements
The system will explore machine learning models to predict the user's total spending for the following month.

The proposed models are:
- Moving Average as a baseline prediction method.
- Linear Regression.
- Random Forest Regressor.

The models will use suitable historical expense data. Their performance will be compared using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Data will be separated chronologically for training and testing to reduce the risk of using future information during training.

## 12. Database Requirements
The database will store the information needed for the system.

The proposed database entities are:
- **Users:** Stores user account information.
- **Expenses:** Stores expense amounts, dates, categories, and descriptions.
- **Categories:** Stores expense category information.
- **Budgets:** Stores users' monthly budget limits.
- **Predictions:** Stores monthly spending predictions and related information, if required by the final design.

The database structure may be updated during system development.

## 13. User Interface Requirements
The system should provide a simple and user-friendly interface.

The proposed pages are:
- Login and registration page.
- Dashboard page showing monthly spending summaries.
- Expense management page.
- Budget management page.
- Spending reports and charts page.
- Monthly spending prediction page.
- User account or profile page.

## 14. Acceptance Criteria
The project will be considered successful when:

- Users can register, log in, and manage their expense records.
- Expense records are saved and retrieved correctly.
- The system calculates monthly spending and displays reports correctly.
- Budget warnings appear when the defined conditions are met.
- The prediction feature produces a spending estimate when sufficient data is available.
- Machine learning models are evaluated using appropriate performance metrics.
- The main system functions pass their planned tests.

## 15. Testing Requirements
The system will be tested to check whether its features work correctly.

The planned testing activities include:
- **Functional Testing:** Check that each feature works according to its requirements.
- **Input Validation Testing:** Check how the system handles empty, invalid, or incorrect inputs.
- **Database Testing:** Check whether expense records are saved, updated, retrieved, and deleted correctly.
- **Prediction Evaluation:** Compare machine learning predictions with actual spending using MAE and RMSE.
- **Usability Testing:** Check whether users can understand and use the system easily.

## 16. Project Benefits
The system is expected to provide the following benefits:

- Help students understand their spending habits.
- Support better monthly budget planning.
- Help users identify unnecessary spending.
- Provide an estimate of future monthly expenses.
- Demonstrate the practical application of machine learning in personal financial management.

## 17. Ethical and Privacy Considerations
The system will handle personal financial records, so user information must be protected. Passwords should be stored securely using an appropriate password-hashing method. Access to expense records should be restricted to the relevant user. Any external dataset used for machine learning should be checked for its source, suitability, and usage licence.

## 18. Expected Outcome
The expected outcome is a functional web-based expense tracker that combines expense recording, budget monitoring, spending reports, and machine learning-based monthly spending prediction. The project will also compare selected prediction methods to identify which provides better results on the available data.

## 19. Future Enhancements
Possible future improvements include:
- Exporting spending reports to PDF or CSV.
- Adding recurring expense records.
- Providing more detailed spending insights.
- Developing a mobile application.
- Integrating bank transactions, subject to suitable security and access requirements.

## 20. Conclusion
The Smart Expense Tracker aims to help university students manage their personal finances through expense tracking, budget monitoring, and monthly spending prediction. The PRD provides the initial requirements and direction for system design, implementation, and evaluation. The requirements may be refined after discussions with the project supervisor.