# IBM_Predicting_Customer_Churn
Final project for I310D: Introduction to Human-Centered Data Science. \
Affiliated Members: Itzhak Estrella, Avery Gilbert, Vanessa Medrano & Lucy Schilling.

### Data Feature Table
| Feature           | Description                                                                                                           | Data Type |
|-------------------|-----------------------------------------------------------------------------------------------------------------------|-----------|
| CustomerID        | A unique ID that identifies each customer.                                                                            | string    |
| Count             | A value used in reporting/dashboarding to sum up the number of customers in a filtered set.                           | int64     |
| Country           | The country of the customer’s primary residence.                                                                      | string    |
| State             | The state of the customer’s primary residence.                                                                        | string    |
| City              | The city of the customer’s primary residence.                                                                         | string    |
| Zip Code          | The zip code of the customer’s primary residence.                                                                     | int64     |
| Lat Long          | The combined latitude and longitude of the customer’s primary residence.                                              | string    |
| Latitude          | The latitude of the customer’s primary residence.                                                                     | float64   |
| Longitude         | The longitude of the customer’s primary residence.                                                                    | float64   |
| Gender            | The customer’s gender: Male, Female.                                                                                  | string    |
| Senior Citizen    | Indicates if the customer is 65 or older: Yes, No.                                                                    | string    |
| Partner           | Indicates if the customer has a partner: Yes, No.                                                                     | string    |
| Dependents        | Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.| string    |
| Tenure Months     | Indicates the total number of months that the customer has been with the company by the end of the specified quarter.  | int64     |
| Phone Service     | Indicates if the customer subscribes to home phone service with the company: Yes, No.                                  | string    |
| Multiple Lines    | Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No.                           | string    |
| Internet Service  | Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.                | string    |
| Online Security   | Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No.        | string    |
| Online Backup     | Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No.          | string    |
| Device Protection | Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No. | string |
| Tech Support      | Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No. | string |
| Streaming TV      | Indicates if the customer uses their Internet service to stream television programming from a third party provider: Yes, No. The company does not charge an additional fee for this service. | string |
| Streaming Movies  | Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service. | string |
| Contract          | Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.                                    | string    |
| Paperless Billing | Indicates if the customer has chosen paperless billing: Yes, No.                                                      | string    |
| Payment Method    | Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check.                               | string    |
| Monthly Charges   | Indicates the customer’s current total monthly charge for all their services from the company.                        | float64   |
| Total Charges     | Indicates the customer’s total charges, calculated to the end of the quarter specified above.                         | float64    |
| Churn Label       | Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value. | string |
| Churn Value       | 1 = the customer left the company this quarter. 0 = the customer remained with the company. Directly related to Churn Label. | int64 |
| Churn Score       | A score from 0-100 calculated using the predictive tool IBM SPSS Modeler, incorporating factors known to cause churn. The higher the score, the more likely the customer will churn. | int64 |
| CLTV              | Customer Lifetime Value. A predicted CLTV is calculated using corporate formulas and existing data. The higher the value, the more valuable the customer. High-value customers should be monitored for churn. | int64 |
| Churn Reason      | A customer’s specific reason for leaving the company. Directly related to Churn Category.                              | string    |
