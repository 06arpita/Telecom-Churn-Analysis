# **Dataset Overview**

This dataset captures detailed information about customer demographics, service subscriptions, billing details, and churn behavior from a telecom/service-based company. It provides a comprehensive view of how customers interact with the company’s services, the types of plans they subscribe to, the revenue they generate, and whether they continue or discontinue the service.

The dataset includes variables related to personal profile, tenure, service usage, value-added features, payment methods, and financial contributions. It is well-suited for analyzing customer retention, identifying churn drivers, performing revenue analysis, and building predictive models for churn forecasting.

Each record represents an individual customer, making the dataset useful for customer segmentation, behavioral analysis, and lifetime value estimation.

## **Key Variables and Descriptions**

### **Customer_ID:**
A unique identifier assigned to each customer. This attribute is essential for tracking individual customer records and distinguishing one customer from another in the dataset.

### **Gender:**
Specifies the gender of the customer. This variable can be used to analyze behavioral or churn differences across gender groups.

### **Age:**
Represents the age of the customer. It helps in demographic segmentation and understanding age-wise service adoption or churn trends.

### **Married:**
Indicates the marital status of the customer (Married/Unmarried). This can influence purchasing power, plan selection, and retention likelihood.

### **State:**
Shows the state or region where the customer resides. Useful for geographic analysis and regional churn patterns.

### **Number_of_Referrals:**
The number of new customers referred by the existing customer. It reflects customer satisfaction and loyalty.

### **Tenure_in_Months:**
Indicates how long the customer has stayed with the company. Higher tenure generally suggests stronger customer loyalty.

### **Value_Deal:**
Represents whether the customer is enrolled in any promotional or bundled value deal plan.

### **Phone_Service:**
Specifies whether the customer has subscribed to phone services.

### **Multiple_Lines:**
Indicates if the customer uses multiple phone lines under the same account.

### **Internet_Service:**
Shows whether the customer subscribes to internet services.

### **Internet_Type:**
Specifies the type of internet connection (e.g., Fiber, DSL). This can impact service satisfaction and churn.

### **Online_Security:**
Indicates whether the customer has an online security add-on service.

### **Online_Backup:**
Specifies if the customer uses online/cloud backup services.

### **Device_Protection_Plan:**
Shows whether the customer has subscribed to device protection or insurance.

### **Premium_Support:**
Indicates access to priority or premium technical support services.

### **Streaming_TV / Streaming_Movies / Streaming_Music:**
These variables indicate whether the customer subscribes to entertainment streaming services provided by the company.

### **Contract:**
Represents the contract duration (Monthly, Yearly, Multi-year). Contract length strongly affects churn probability.

### **Total_Extra_Data_Charges:**
Charges incurred due to additional data usage beyond plan limits.

### **Total_Long_Distance_Charges:**
Costs associated with long-distance calling services.

### **Total_Revenue:**
Net revenue generated from the customer after adjustments.

### **Customer_Status:**
Indicates whether the customer is Active, Churned, or Newly Joined. This is a key target variable for churn analysis.

### **Churn_Category:**
Broad classification of the reason for churn (e.g., Price, Service Issues, Competitor).

### **Churn_Reason:**
Provides detailed explanations for why the customer discontinued the service.

## **Data Summary**

- **Age**
  - **Range:** 18.00 – 85.00
  - **Mean:** 47.07
  - **Standard Deviation:** 16.70

- **Number_of_Referrals**
  - **Range:** 0.00 – 15.00
  - **Mean:** 7.43
  - **Standard Deviation:** 4.62

- **Tenure_in_Months**
  - **Range:** 1.00 – 36.00
  - **Mean:** 17.34
  - **Standard Deviation:** 10.58

- **Monthly_Charge**
  - **Range:** -10.00 – 118.75
  - **Mean:** 63.65
  - **Standard Deviation:** 31.19

- **Total_Charges**
  - **Range:** 18.80 – 8684.80
  - **Mean:** 2280.37
  - **Standard Deviation:** 2268.05

- **Total_Refunds**
  - **Range:** 0.00 – 49.79
  - **Mean:** 1.92
  - **Standard Deviation:** 7.85

- **Total_Revenue**
  - **Range:** 21.36 – 11979.34
  - **Mean:** 3033.87
  - **Standard Deviation:** 2866.51
