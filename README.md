# Customer-Defection
A project for AISaturdays Lagos(Cohort 5)
Customer defection is the loss of clients or customers. Telephone service companies, ISPs, insurance firms, etc, often use customer defection analysis and rates as one of their key business metrics because the cost of retaining an existing customer is far less than acquiring a new one.
Companies usually make a distinction between voluntary defection (churn) and involuntary defection (churn). Voluntary defection occurs due to a decision by the customer to switch to another company or service provider, involuntary defection occurs due to circumstances such as a customer's relocation to a long-term care facility, death, or the relocation to a distant location.

In this analysis, involuntary reasons for churn will be excluded from the analytical models. We will instead tend to concentrate on voluntary defection, because it typically occurs due to factors of the company-customer relationship which companies control, such as how billing interactions are handled or how after-sales help is provided.

Our team was presented with data from a telco company and tasked to analyse the data and gain insight into customer defection as-well-as develop a model that will predict the possibility of defection by any customer.

The DataSet did not come with a data dictionary, but we used general knowledge to interpret the columns and came up with this dictionary for the purpose of this project;

customerID- Unique identifiers for the customers.

gender- Female and Male.

SeniorCitizen- 0 if the customer is not a senior citizen else 1 (int64).

Partner- Yes if the customer has a partner else No.

Dependents - Yes if the customer has people that depend on them else No.

tenure - How long the customers have been with the company in months(int64).

PhoneService - Yes for customers that have phone service else No.

MultipleLines - Yes for customers with Multiple lines.

            - No for customers with single phone lines.
            - No phone services for customers without phone service.
InternetService - Fiber optic

              - DSL- Digital Subscriber Line
              - No
OnlineSecurity - Yes for customers with online security

             - No for customers without online security
             - No phone services for customers without phone service.
OnlineBackup - Yes for customers with online backup

           - No for customers without online backup
           - No phone services for customers without phone service.
DeviceProtection - Yes for customers with device protection

               - No for customers without device protection
               - No phone services for customers without phone service.
TechSupport - Yes for customers with access to tech support

          - No for customers without access to tech support
          - No phone services for customers without phone service.
StreamingTV - Yes for customers that have Streaming TV

          - No for customers without Streaming TV
          - No phone services for customers without phone service.
StreamingMovies - Yes for customers that stream movies

              - No for customers that don’t stream movies
              - No phone services for customers without phone service.
Contract - Month-to-month: Customers that renew their contract monthly

       - Two year: Customers that renew their contract every two years
       - One year: Customers that renew their contract every year
PaperlessBilling - Yes for customers that handle their billings online

               - No for customers that do not handle their billings online
PaymentMethod - Electronic check: Customers that handle payment via electronic cheque

            - Mailed check: Customer that handle payment by mail
            - Bank transfer (automatic):  Customers that pay automatically via bank transfer
            - Credit card (automatic): Customers that pay automatically via their credit cards
MonthlyCharges - The monthly charge for each customer (float64)

TotalCharges - The total charge for each customer taking into consideration their contract. (float64)

Churn - Yes for customers that are lost and No for retained customers. Context:The churn rate also known as the rate of attrition or customer churn is the rate at which customers stop doing business with an entity.
