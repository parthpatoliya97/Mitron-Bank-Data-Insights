# Mitron Bank Credit Card Launch Strategy
## Problem Statement :-
- Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market. 

- AtliQ Data Services came to know about this through an internal link and approached Mitron Bank with a proposal to implement this project. However, the strategy director of Mitron Bank, Mr. Bashnir Rover is skeptical and asked them to do a pilot project with the sample data before handing over them the full project. They provided a sample dataset of 4000 customers across five cities on their online spending and other details.

----------------------------
### Dataset Tables Quick Overview :-

#### dim_customers :
- customer_id: This column represents the Unique ID assigned to each customer.
- gender: This column represents the gender of the customer. (Male, Female)
- age_group: This column categorizes the customer into different age groups. (21-24, 25-34, 35-45, 45+)
- marital_status: This column indicates the marital status of the customer (single, married).
- city: This column represents the city of residence for the customer. (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru)
- occupation: This column denotes the occupation or profession of the customer. (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees)
- average_income: This column indicates the monthly average income of the customer, in INR currency.

#### fact_spends :
- customer_id: This column represents the Unique ID of each customer, linking to the dim_customer table.
- month: This column indicates the month in which the spending was recorded. (May, June, July, August, September, October)
- category: This column describes the category of spending (Entertainment, Apparel, Electronics, etc).
- payment_type: This column specifies the type of payment used by the customer (Debit Card, Credit Card, UPI, Net Banking).
- spends: This column shows the total amount spent by the customer in the specified month, category and payment_type.

-------------------------

### What is Income Utilization ?

- Income Utilization measures how much of a customer’s income is being spent or utilized through credit card transactions. 
- higher income utilization percentage indicates that customers rely more on credit card for daily spending
- while lower utilization suggests conservative spending or the presence of multiple income sources/payment modes.

### Formula :-
Income Utilization (%) = (Total Annual Card Spending / Annual Income) * 100

### 🔹Which Is Better — High or Low Income Utilization?

#### For Banks :
- Moderate utilization is ideal.

   - Too High → Higher revenue but higher credit risk

   - Too Low → Low engagement and low revenue

#### For Customers:
- Lower utilization is generally better, as it indicates healthy spending habits and reduces credit risk.

----------------------------------------------------------------

## Key Insights :

## 1️⃣ Demographics View 

### Customer Distribution

- Total customers: 4,000

- Male: 2,597 (65%)

- Female: 1,403 (35%)

### Marital Status

- 79% married
- 21% single

### Age Group

- 25–45 years: 2,771 customers (highest segment)

- 21–24 years: 691 customers

- 45+ years: 538 customers
  
- → The bank’s customer base is dominated by working-age professionals.

### City Distribution

- Mumbai → highest number of customers

- Followed by: Chennai, Bengaluru, Delhi NCR, Hyderabad
  
- → Strong urban presence with highest penetration in Tier-1 metros.

### Occupation Insights

- Salaried IT employees are the largest segment.

- smaller share of government employees.

### Conclusion :

Mitron Bank’s customer base is urban, working-age, and dominated by salaried IT and married customers—reflecting a financially stable and digitally active audience with predictable cash flow.

----------------------------------------------------------------

## 2️⃣ Income View & Key Insights

- Total Income Generated :- ₹1,240M

### Income by Gender

- Male: ₹805M (65%)

- Female: ₹435M (35%)
  
- → Income contribution mirrors gender distribution.

### Income by Marital Status

- Married: ₹1,003M (80%)

- Single: ₹237M (20%)
  
- → Married customers generate the majority of bank income.

### Income by Age Group

- 25–45 yrs: ₹874M (70%) → highest earning bracket

- 21–24 yrs: lowest at ₹169M
  
- → Income strongly correlates with career maturity.

### Income by City

- Mumbai contributes the highest income

- Hyderabad at Bottom

### Income by Occupation

Highest Avg Income:

- Business Owners → ₹70K

- Salaried IT Employees → ₹61K
  
- Lowest: Freelancerss → ₹35k

### Highest Total Income Contribution:

- Salaried IT Employees → ₹477M

- Business Owners → ₹265M

- Lowest: Government Employees → ₹125M

### Conclusion :

Majority of the bank's income comes from mid-career professionals, especially salaried IT employees and business owners residing in major metros like Mumbai and Chennai.

-----------------------------------------------------------------------------

## 3️⃣ Spending View & Key Insights
- Total Spend :- ₹531M 

- Average Spend per Customer: ₹22.12K

### Spend by Gender

- Male: ₹357M (67%)

- Female: ₹174M (33%)
- → Males spend almost double compared to females.

### Spend by Marital Status

- Married: ₹429M (80%)

- Single: ₹102M (20%)

### Spend by Payment Mode

- Credit Card: ₹216M (40%)

- UPI: ₹141M (27%)

- Debit Card: ₹119M (23%)

- Net Banking: ₹55M (11%)
- → Strong preference for credit cards and digital payments.

### Spend by City

- Mumbai → highest spender

- Hyderabad contributes the least.

### Spend by Month

- Spending increases in August and September, indicating seasonal behavior or festival-driven purchases.

### Spend by Occupation

- Salaried IT Employees: ₹244M (48%) – dominant spenders

- Business Owners: ₹88M

- Lowest: Government Employees → ₹36M

### Spend by Category

- Major spend categories (65% of total spend) : Bills, Groceries, Electronics, Health & Wellness

### Spend by Age Group

- 25–34: ₹203M

- 35–44: ₹191M

- 21–24: ₹69M

- 45+: ₹68M

Conclusion :

Spending is driven by digitally active, middle-aged salaried professionals using credit cards for essential and lifestyle categories.

-------------------------------------------------------------

## 4️⃣ Income Utilization View & Key Insights

- Average Utilization: 42.82%

- Male: 44.39%

- Female: 39.92%

### Utilization by Marital Status

- Married: 42.77%

- Single: 43.06%
→ Nearly identical utilization behavior.

### Utilization by Age Group

- 35–45 yrs: 46.72% → Highest

- 25–34 yrs: 43.66%

- 21–24 yrs: 40.59%

- 45+ yrs: 34.70% → Lowest
→ Peak financial engagement is among 35–45 age bracket.

### Utilization by City

- Mumbai: 51.43% → Highest

- Delhi NCR: 48.03%

- Bengaluru: 43.46%

- Hyderabad: 36.25%

- Chennai: 31.10% → Lowest

### Utilization by Occupation

Highest:

- Salaried IT Employees → 51.04%

- Freelancers → 45.80%

Lowest:

- Government Employees → 29%

- Business Owners → 33.22%

### Conclusion :

Financial engagement is strongest among Mumbai customers, IT employees, and mid-career professionals, while government employees and Chennai customers show lower utilization levels.

------------------

## Dashboard View 

Live Dashboard View : - [Click Here](https://app.powerbi.com/view?r=eyJrIjoiNTQ1MzlkOTUtMjhlYS00N2ZlLTkzOTUtMTgzMmUyNGE3YTNjIiwidCI6IjJhYmVkYTA4LTMyOGEtNGFlMy1iYTg1LThiNzIxZmE1Mzg3OSJ9)

### Home Page View
![home page](https://github.com/parthpatoliya97/Mitron-Bank-Data-Insights/blob/main/Images/Home%20View.png?raw=true)

-------------------

### Demographics & Income View
![demographics view](https://github.com/parthpatoliya97/Mitron-Bank-Data-Insights/blob/main/Images/Demographics%20&%20Income%20View.png?raw=true)

--------------

### Spending View
![income view](https://github.com/parthpatoliya97/Mitron-Bank-Data-Insights/blob/main/Images/Spending%20View.png?raw=true)

----------------

### Income Utilization View
![spending view](https://github.com/parthpatoliya97/Mitron-Bank-Data-Insights/blob/main/Images/Income%20Utilization%20View.png?raw=true)

-----------------------


