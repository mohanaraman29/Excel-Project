# Excel-Project

## Bank Loan Report Dashboard

## Objective 

#### Bank loans are a crucial financial tool that enables individuals and businesses to achieve their goals and manage financial needs. However, it's essential for borrowers to understand the terms, costs, and responsibilities associated with loans to make informed financial decisions.

## Tools and Techniques used 

- #### Excel :  Used to create interactive dashboards and present data insights.
- #### Pivot Table :  Applied for creating custom Formula calculations to analyze business performance.
- #### Data Visualization:  Employed various chart types (bar, line, and pie charts) to make the insights easy to understand.

## Process of Granting a Loan

- #### Loan Application
- #### Application Review
- #### Identity Verification
- #### Credit Check
- #### Income Verification
- #### Debt-to-Income Ratio 
- #### Employment Verification
- #### Collateral Assessment 
- #### Risk Assessment
- #### Loan Agreement 
- #### Repayment
- #### Ongoing Monitoring

## Reasons for Analysing Bank Loan Data

### Risk Assessment :
#### One of the primary purposes of analysing loan data is to assess the risk associated with lending to a particular individual or business. Banks use data to evaluate the creditworthiness of borrowers, predict default probabilities, and determine interest rates and lending terms.

### Decision-making :
#### Loan data analysis supports the decision-making process when evaluating loan applications. Banks use data-driven models and algorithms to make informed lending decisions, such as approving or denying loan requests.

### Portfolio Management :
#### Banks manage portfolios of loans, including mortgages, personal loans, and business loans. Data analysis helps banks monitor the health of these portfolios, identify underperforming loans, and optimize loan terms and pricing.

### Fraud Detection : 
#### Banks use data analysis to detect fraudulent loan applications and activities. Unusual patterns, inconsistencies, or discrepancies in loan data can trigger fraud alerts.

### Regulatory Compliance :
#### Banks are subject to regulatory requirements that mandate the collection and reporting of loan data. Compliance with regulations such as the Home Mortgage Disclosure Act (HMDA) and the Know Your Customer (KYC) regulations requires data analysis and reporting.

### Customer Insights :
#### Analysing loan data provides insights into customer behaviour, preferences, and needs. Banks can use these insights to tailor loan products and marketing strategies to specific customer segments.

### Profitability Analysis :  
#### Banks assess the profitability of their loan portfolios by analysing data related to interest income, loan origination costs, default rates, and collection efforts.

### Market Research :
#### Data analysis helps banks understand market trends, competitive landscape, and customer demand. This information guides product development and market expansion strategies.

### Credit Risk Management :
#### Banks continuously monitor and manage credit risk associated with their loans. Data analysis helps in setting risk management strategies, provisioning for potential losses, and stress testing loan portfolios.

### Customer Retention :
#### Banks use data analysis to identify opportunities for retaining existing customers, such as offering loan refinancing options or additional financial products.

## Field used in Pivot Table 

- #### Loan ID
- #### Address State
- #### Employee Length
- #### Employee Title
- #### Grade
- #### Sub Grade
- #### Home Ownership
- #### Issue Date
- #### Last Credit Pull Date
- #### Last Payment Date
- #### Loan Status
- #### Next Payment Date
- #### Purpose
- #### Verification Status
- #### Annual Income
- #### Instalment
- #### Interest Rate
- #### Loan Amount
  

# BANK LOAN REPORT ( PROBLEM STATEMENT )

![summary dashboard](https://github.com/user-attachments/assets/281b5751-03d0-42a8-a9f3-b90de939349e)


# DASHBOARD 1: SUMMARY


#### In order to monitor and assess our bank's lending activities and performance, we need to create a comprehensive Bank Loan Report. This report aims to provide insights into key loan-related metrics and their changes over time. The report will help us make data-driven decisions, track our loan portfolio's health, and identify trends that can inform our lending strategies.


### Key Performance Indicators (KPIs) Requirements:


### Total Loan Applications: 
#### We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).

### Total Funded Amount: 
#### Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.

### Total Amount Received: 
#### Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.

### Average Interest Rate:
#### Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.

### Average Debt-to-Income Ratio (DTI): 
#### Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, MTD, and track Month-over-Month (MoM) fluctuations.


# Good Loan v Bad Loan KPI’s

#### In order to evaluate the performance of our lending activities and assess the quality of our loan portfolio, we need to create a comprehensive report that distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria


# Good Loan KPIs:


### Good Loan Application Percentage:
#### We need to calculate the percentage of loan applications classified as 'Good Loans.' This category includes loans with a loan status of 'Fully Paid' and 'Current.'

### Good Loan Applications: 
#### Identifying the total number of loan applications falling under the 'Good Loan' category, which consists of loans with a loan status of 'Fully Paid' and 'Current.'

### Good Loan Funded Amount:
#### Determining the total amount of funds disbursed as 'Good Loans.' This includes the principal amounts of loans with a loan status of 'Fully Paid' and 'Current.'

### Good Loan Total Received Amount: 
#### Tracking the total amount received from borrowers for 'Good Loans,' which encompasses all payments made on loans with a loan status of 'Fully Paid' and 'Current.'


# Bad Loan KPIs:


### Bad Loan Application Percentage:
#### Calculating the percentage of loan applications categorized as 'Bad Loans.' This category specifically includes loans with a loan status of 'Charged Off.'

### Bad Loan Applications:
#### Identifying the total number of loan applications categorized as 'Bad Loans,' which consists of loans with a loan status of 'Charged Off.'

### Bad Loan Funded Amount: 
#### Determining the total amount of funds disbursed as 'Bad Loans.' This comprises the principal amounts of loans with a loan status of 'Charged Off.'

### Bad Loan Total Received Amount:
#### Tracking the total amount received from borrowers for 'Bad Loans,' which includes all payments made on loans with a loan status of 'Charged Off.'

![overview dashboard](https://github.com/user-attachments/assets/89a68cc0-ade6-4946-a8e4-8ce0bb0d6d5d)


# DASHBOARD 2: OVERVIEW

#### In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using a variety of chart types. These charts will provide a clear and insightful view of our lending operations, facilitating data-driven decision-making and enabling us to gain valuable insights into various loan parameters. Below are the specific chart requirements:


### 1. Monthly Trends by Issue Date (Line Chart):

#### Chart Type: Line Chart
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### X-Axis: Month (based on 'Issue Date')
#### Y-Axis: Metrics' Values

#### Objective: This line chart will showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, allowing us to identify seasonality and long-term trends in lending activities.


### 2. Regional Analysis by State (Filled Map):

#### Chart Type: Filled Map
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### Geographic Regions: States

#### Objective: This filled map will visually represent lending metrics categorized by state, enabling us to identify regions with significant lending activity and assess regional disparities.


### 3. Loan Term Analysis (Donut Chart):

#### Chart Type: Donut Chart
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### Segments: Loan Terms (e.g., 36 months, 60 months)

#### Objective: This donut chart will depict loan statistics based on different loan terms, allowing us to understand the distribution of loans across various term lengths.


### 4. Employee Length Analysis (Bar Chart):

#### Chart Type: Bar Chart
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### X-Axis: Employee Length Categories (e.g., 1 year, 5 years, 10+ years)
#### Y-Axis: Metrics' Values

#### Objective: This bar chart will illustrate how lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.


### 5. Loan Purpose Breakdown (Bar Chart):

#### Chart Type: Bar Chart
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### X-Axis: Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)
#### Y-Axis: Metrics' Values

#### Objective: This bar chart will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.


### 6. Home Ownership Analysis (Pie Chart):

#### Chart Type:Pie Chart
#### Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
#### Hierarchy: Home Ownership Categories (e.g., own, rent, mortgage)

#### Objective: This tree map will display loan metrics categorized by different home ownership statuses, allowing for a hierarchical view of how home ownership impacts loan applications and disbursements.

# Conclusion 
#### The dashboard helped the business make strategic decisions related to the Good Loan Application, Bad Loan Applications and Overall Toatal Loan Application by the Customers.


