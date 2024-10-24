# Customer Retention Analysis

## Problem Statement
### The telecom industry faces a significant challenge in retaining customers, as acquiring them is costly and highly competitive. The Retention Manager’s goal is to prevent customer churn by identifying at-risk customers before they terminate their contracts. Currently, the company approaches retention reactively, contacting customers only after they have left, which has proven ineffective. With the wealth of customer data available, the telecom aims to adopt a proactive strategy that leverages predictive analytics to forecast churn and enables timely intervention. However, past customer analysis using traditional methods like Excel has not yielded actionable insights, leading to dead ends in the analysis process.
### 
### To address these issues, the telecom company seeks to develop a comprehensive dashboard that clearly visualizes key performance indicators (KPIs) around customer churn. The goal is to create an easily understandable and interactive dashboard for management, highlighting at-risk customers based on factors such as usage patterns, contract duration, billing information, and customer interactions. This approach will not only improve customer retention efforts but also streamline the decision-making process by offering clear insights into customer behavior and churn risk.
###

## About dataset
### 1.customerID: Unique identifier for each customer.
### 2.gender: Customer's gender, either "Male" or "Female."
### 3.SeniorCitizen: Indicates whether the customer is a senior citizen (1 if yes, 0 if no).
### 4.Partner: Whether the customer has a partner (Yes/No).
### 5.Dependents: Whether the customer has dependents (Yes/No).
### 6.tenure: The number of months the customer has stayed with the company.
### 7.PhoneService: Indicates if the customer has a phone service (Yes/No).
### 8.MultipleLines: Indicates if the customer has multiple lines (No, Yes, or "No phone service").
### 9.InternetService: Type of internet service the customer has (DSL, Fiber optic, or No).
### 10.OnlineSecurity: Whether the customer has online security add-on (Yes/No/No internet service).
### 11.OnlineBackup: Whether the customer has online backup service (Yes/No/No internet service).
### 12.DeviceProtection: Whether the customer has device protection service (Yes/No/No internet service).
### 13.TechSupport: Whether the customer has technical support service (Yes/No/No internet service).
### 14.StreamingTV: Whether the customer streams TV through the service (Yes/No/No internet service).
### 15.StreamingMovies: Whether the customer streams movies through the service (Yes/No/No internet service).
### 16.Contract: Type of contract the customer is under (Month-to-month, One year, Two year).
### 17.PaperlessBilling: Whether the customer is enrolled in paperless billing (Yes/No).
### 18.PaymentMethod: Customer's payment method (Electronic check, Mailed check, Bank transfer, Credit card).
### 19.MonthlyCharges: The amount the customer is charged monthly.
### 20.TotalCharges: The total amount charged to the customer.
### 21.numAdminTickets: Number of administrative tickets the customer has logged.
### 22.numTechTickets: Number of technical tickets the customer has logged.
### 23.Churn: Whether the customer has churned (Yes/No).
###

## KPI's to Focus:
###
### 1.Demographics
### 2.Customer account information
### 3.Service customer Signed for
### 4.Churn by type of Internet services
### 5.Customer by internet service 
### 6.Sum of monthly charges
### 7.Type of contract
### 8.Churn by payment method

## Analysis Insights
### 

## Customer Churn Dashboard
###
![Screenshot 2024-10-24 110943](https://github.com/user-attachments/assets/c7e78121-590d-4f57-aa32-6133d8774019)


###
![Screenshot 2024-10-24 111441](https://github.com/user-attachments/assets/f4190f4c-f808-4d47-9c97-f6d57d9a53f8)

###
### 1.Customer Base Overview:
#### Total customers at risk: 7,043
#### Overall churn rate: 26.54% (which is quite high for the telecom industry)
#### Yearly charges: $16.06M
#### Monthly charges: $456.12K
### Critical Risk Factors:
### Contract Type Impact:
#### Month-to-month contracts show the highest churn rate (42.71%)
#### Two-year contracts have the lowest churn rate (~11%)
#### 55% of customers are on month-to-month contracts, representing a significant risk area

### Internet Service Analysis:
#### Fiber optic customers show the highest churn rate (41.89%)
#### DSL has a moderate churn rate (18.96%)
#### Despite higher churn, Fiber optic service has the largest customer base (3.1K customers)

### 2.Customer Demographics:
#### Gender distribution is fairly balanced (50.5% female, 49.5% male)
#### Customer segments:
#### 36% Partners
#### 25% Senior Citizens
#### 17% Dependents

### Service Adoption:
#### Phone Service: 91% adoption rate
#### Streaming TV and Movies: 44% each
#### Lower adoption rates for:
#### Device protection (29%)
#### Online Backup (28%)
#### Tech Support (17%)
#### Online Security (16%)

### Payment Behavior:
#### Electronic check users show the highest churn risk
#### Payment method distribution:
#### Electronic check: 34%
#### Mailed check: 23%
#### Bank transfer and Credit card: 22% each
#### Paperless billing adopted by 25.09% of customers

## Recommendations for Customer Retentation:
### 1.Contract Strategy:
#### Develop incentives to move month-to-month customers to longer-term contracts
#### Create special offers for customers completing their first year
#### Design retention programs specifically for Fiber optic service customers

### 2.Service Enhancement:
#### Investigate why Fiber optic services have high churn despite being popular
#### Focus on increasing adoption of security and support services, which could increase customer stickiness

### 3.Payment Method Optimization:
#### Analyze why electronic check users have higher churn rates
#### Consider incentives for customers to switch to more stable payment methods

### 4.Customer Engagement:
#### Develop targeted retention programs for each customer segment (Partners, Senior Citizens, Dependents)
#### Create service bundles that appeal to specific demographic groups.

### 5.Proactive Risk Management:
#### Implement early warning system for customers showing risk patterns
#### Focus on the first year of service, where churn risk appears highest
#### Consider a loyalty program to reward long-term customers
