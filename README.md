# Customer_Churn_Prediction

**Project Description**
**Objective:**
The primary objective of this project is to analyze customer data from a telecommunications company to understand the factors influencing customer churn and develop predictive models to identify customers who are likely to churn. Churn, in this context, refers to customers who discontinue their service with the company. By predicting churn, the company can take proactive measures to retain customers and improve overall customer satisfaction.

**Dataset Description**
The dataset consists of customer data with 21 columns, each representing different attributes of the customers and their service usage. Below is a detailed description of each column:

**customerID:** Unique identifier for each customer.
    
**gender:** Gender of the customer (Male, Female).
    
**SeniorCitizen:** Indicates if the customer is a senior citizen (1 for Yes, 0 for No).
    
**Partner:** Indicates if the customer has a partner (Yes, No).
    
**Dependents:** Indicates if the customer has dependents (Yes, No).
    
**tenure:** Number of months the customer has been with the company.
    
**PhoneService:** Indicates if the customer has phone service (Yes, No).
    
**MultipleLines:** Indicates if the customer has multiple lines (Yes, No, No phone service).
    
**InternetService:** Type of internet service (DSL, Fiber optic, No).
    
**OnlineSecurity:** Indicates if the customer has online security service (Yes, No, No internet service).
    
**OnlineBackup:** Indicates if the customer has online backup service (Yes, No, No internet service).
    
**DeviceProtection:** Indicates if the customer has device protection plan (Yes, No, No internet service).
    
**TechSupport:** Indicates if the customer has tech support service (Yes, No, No internet service).
    
**StreamingTV:** Indicates if the customer has streaming TV service (Yes, No, No internet service).
    
**StreamingMovies:** Indicates if the customer has streaming movies service (Yes, No, No internet service).
    
**Contract:** Type of contract (Month-to-month, One year, Two year).
    
**PaperlessBilling:** Indicates if the customer uses paperless billing (Yes, No).
    
**PaymentMethod:** Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
    
**MonthlyCharges:** The amount charged to the customer monthly.
    
**TotalCharges:** The total amount charged to the customer.
    
**Churn:** Indicates if the customer churned (Yes, No).
    
## Installation
To run the project in your Jupyter Notebook or Google Colab, follow these steps:

1. **Clone the repository**:
   - If using Jupyter Notebook:
     ```bash
     !git clone https://github.com/DivyaSriThatikonda/Customer_Churn_Prediction.git
     ```
   - If using Google Colab:
     - Open a new Colab notebook.
     - Execute the following code cell:
       ```python
       !git clone https://github.com/DivyaSriThatikonda/Customer_Churn_Prediction.git
       ```
2. **Install dependencies**:
   - Run the following code cell in the notebook to install the required libraries:
     ```python
     !pip install numpy pandas matplotlib seaborn scikit-learn
     ```

3. **Access the dataset**:
   - The `insurance.csv` dataset is already included in the repository. 

4.**Tools used**:
- **Numpy**: Used for numerical computations and array manipulation.
- **Pandas**: Used for data manipulation, analysis, and cleaning.
- **Seaborn**: Used for data visualization and statistical plotting.
- **Scikit-learn**: Used for building and evaluating the linear regression model.
-**Descriptive Statistics**: Used to summarize and analyze the dataset, including measures such as mean, median, standard deviation, and correlation coefficients.

**Results**
The RandomForest Classifier model achieved an accuracy of 80% in predicting customer churn. This indicates that the model can correctly identify 80% of the customers who are likely to churn and not to churn, enabling the company to take proactive measures to retain these customers.
