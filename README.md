# Bankruptcy_prediction

Early detection of a company's financial distress is critical. Recall the financial crisis of 2008; many stakeholders were caught unprepared. A select few experts were able to recognize the early warning signs of an approaching calamity, but the majority did not have the tools to systematically identify these signals or the ability to decipher intricate and complex patterns in data. Thanks to developments in data analytics, we now have the chance to alter this narrative.
 
This project focuses on predicting Chapter 7 type of Bankruptcy where the company ceases all operations and completely goes out of business. A trustee is appointed to liquidate the company's assets, and the proceeds are used to pay off debts.
 
The financial variables which could be used for this predictions are as follows:
 
# Variables:
The final variables we selected from the total 974 variables in the original data are as follows:
 
• Current Assets: Represents company's assets that are expected to be used up or converted into cash in the next year.
 
• COGS: Denotes company's total sum of expenses that are directly incurred due to sale of products and services.
 
• Depreciation and Amortization: Cumulative reduction in value of company’s tangible and intangible assets over time.
 
• Earnings Before Interest, Taxes, Depreciation, and Amortization (EBITDA): Denotes a company's earnings before subtracting interest, taxes, amortization, and depreciation.
 
• Inventory: Total value of raw material and final goods in the inventory. This is a snapshot of a point in time.
 
• Net Income: Represents a company's final profit after deducting all its expenses from its revenue.
 
• Total Receivables: The total amount owed to a business for availed goods or services that customers have yet to pay.
 
• Market Value: Total market value of shares of publicly listed companies at the time of valuation.
 
• Net Sales: The resulting sum after subtracting returns, allowances, and discounts from a company's gross sales.
 
• Total Assets: Represents all of the company’s valuable assets.
 
• Total Long-term Debt: Pertains to all loans and debts owed by a company that have a maturity date beyond one year.
 
• EBIT: Represents a company’s earnings before interest and taxes deduction.
 
• Gross Profit: The residual profit after subtracting the costs related directly to the production and sale of goods or services.
 
• Total Current Liabilities: the sum of all debts that must be paid before the end of the fiscal year. This includes accounts payable, bonds due, unpaid wages and salaries, and other similar obligations.
 
• Retained Earnings: Profit remaining after deducting all operating expenses, taxes, and shareholder dividends.
 
• Total Revenue: The sum of all sales before any costs are deducted. Investment income like interest and dividends on investments could be included.
 
• Total Liabilities: All of a company's debts and financial obligations to third parties.
 
• Total Operating Expenses: The total costs incurred during regular business activities.
 
# Proposed methods:
 
• Using Lagged Values: By analyzing the data in its original form, we can observe how each company's metrics evolve over time, thus maintaining the integrity of the temporal information.
 
• Handling as Panel Data: It leverages the data's longitudinal structure to examine temporal trends and the evolution of financial health over time.
 
• Cross-sectional Snapshots: We take a specific time slice of data for each company, effectively treating each company's selected observation as independent. Simplifying the data to one year observation per company allows us to focus on specific years, particularly important in contrasting the conditions between companies that failed and those that did not at a particular time.
 
# Models used:
 
i. Model selected for data without panel structure:
  a. Logistic Regression (LR)
  b. Random Forest (RF)
  c. K-Nearest Neighbor Classifier (KNN)
  d. Support Vector Machines (SVM)
  e. Generalized Estimating Equations (GEE)
 
ii. Model for Panel Data Structure:
  a. Generalized Estimating Equation:
  b. Long Short-Term Memory networks:
  c. Gradient Boosting Machines:

 
