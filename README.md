# Credit-Risk-Optimizer
Problem Statement: Optimizing Credit Card Approvals: A Machine Learning method to Minimize Risks and Boost Revenue.
Link to the dataset 📂: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction
Financial institutions tend to struggle with how to approach approving credit card applications. Most face an overwhelming number of applicants, and the outdated methods that many banks use, consisting of manual checks and simple logic-based systems, only makes it worse.

However, this can result in the two major problems:

Firstly, even good candidates might be rejected, if the criteria are too narrow. This means that the banks not only lose potential revenue due to the rejected good candidates, but they also don't give enough credit to those who might be good.
On the other hand, the institutions may inadvertently give a green light to those applicants who are the most likely to default.
Business Importance 🖥️:
Addressing this issue can get a lot of benefits.

Lower Risk: By proactively identifying and flagging high-risk applicants early on, predictive modelling may be able to reduce defaults by 25–40%.
Increase Revenue: A mid-size bank could capture approximately 8-12 million dollars in additional yearly revenue by accepting just 5 percent more credible applicants.
Streamlined Operations: The costs associated with manual underwriting could be reduced by 60-70percent through automating decisions.
Enhanced Market Position: Gaining new customers in the 12 trillion dollar global payments market will be easier with fast approval times.
Data Collection Strategy 🔍:
🔸Application Data: This basically means the demographical information about the job, and the assets which are retrieved from online applications.
🔸Credit Bureau Data: Given we work together with organizations that perform these services such as Equifax and Experian, we can gain insight from the history of repayment behavior, the existing debts, and how much credit is used.
🔸Behavioral Data: We can study the behavior of current customers on how they spend, and how they pay their bills, but we have to have their permission.
🔸Alternative Data: A check of rent payments and utility bills serves as an indicator to help judges applicants who have little credit history, still doing so privacy regulation compliance.All these data collecting will be in accordance with the laws that protect personal information.

Machine Learning Approach:
We can formulate this problem as a binary classification problem:
✅ Goal: Use more than 25 features to predict if an applicant will be in good standing.
✅ Main goal: Accept more applications with a lower chance of defaults.
✅ Anticipated Result: Achieve excellent performance with a low default rate and a good AUC-ROC score.
