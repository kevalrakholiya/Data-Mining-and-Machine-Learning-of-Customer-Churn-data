# Data-Mining-and-Machine-Learning-of-Customer-Churn-data
This project focuses on analyzing customer churn, a critical metric for businesses, using data mining techniques—specifically classification with decision trees. Customer churn refers to the phenomenon where customers discontinue their relationship with a company, which can significantly impact a business's profitability. Understanding the factors driving churn allows companies to take preemptive measures to retain customers, improve satisfaction, and ultimately reduce attrition.

In this Project, we will apply the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze a dataset of customer attributes. The goal is to develop a decision tree classifier to predict whether a customer is likely to churn (Y for yes, N for no). We will evaluate the model’s performance through metrics such as accuracy, precision, recall, and f-measure. Additionally, the project aims to explore which factors are most influential in predicting churn, enabling businesses to identify potential churners and devise strategies to retain them.

We will use this file to pinpoint potential churners for Business.

VARIABLE DESCRIPTIONS:
cust_id: Customer ID
<br>
region: Customer's region

tenure: How long the customer has been with the company

age: Customer's age

marital: Marital status

address: Address longevity (how many years at the current address)

income: Customer's income level

ed: Education level

employ: Employment years

retire: Retired or not (Y/N)

gender: Gender of the customer

reside: Number of residents at the same address

tollfree: Toll-free service subscription (Y/N)

equip: Equipment purchase (Y/N)

callcard: Call card usage (Y/N)

wireless: Wireless service (Y/N)

longmon, tollmon, equipmon, cardmon, wiremon: Monthly charges for long distance, toll-free, equipment, calling card, and wireless services

longten, tollten, equipten, cardten, wireten: Total tenure charges for the respective services

multline: Multi-line service (Y/N)

voice, pager, internet, callid, callwait, forward, confer: Usage of voice, pager, internet, caller ID, call waiting, call forwarding, and conference calls

ebill: Electronic billing (Y/N)

loglong: Log of long-term monthly charge

lninc: Log of income

custcat: Customer category (C1, C2, etc.)

churn: Whether the customer churned (Y/N)


Target variable: Churn (churn: Y (yes), churn: N(no))
