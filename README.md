# Analysis-for-New-Credit-Card-Launch

# Table of Content

1. About Mitron Bank
2. Objective of the Project
3. Problem Statment
4. Demographic Classification
5. Income Utilization & Spending Analysis
6. Table Grid View Page
7. Recomendation

**About Mitron Bank**

Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

**Objective of the Project**

The objective is to analyze this data and provide actionable, data-driven recommendations to guide Mitron Bank in tailoring the new credit cards to customer needs and market trends.

**Problem Statment**

* Demographic classification: Classify the customers based on available demography such as age group, gender, occupation etc. and provide insights based on them.

* Avg income utilisation %: Find the average income utilisation % of customers (avg_spends/avg_income). This will be your key metric. The higher the average income utilisation %, the more is their likelihood to use credit cards.

* Spending Insights: Where do people spend money the most? Does it have any impact due to occupation, gender, city, age etc.? This can help you to add relevant credit card features for specific target groups.

* Key Customer Segments: By doing above, you should be able to identify and profile key customer segments that are likely to be the highest-value users of the new credit cards. This includes understanding their demographics, spending behaviours, and financial preferences.

* Credit Card Feature Recommendations: Provide recommendations on what key features should be included in the credit card which will improve the likelihood of credit card usage. This should be backed by the insights from data provided and also some secondary research on the internet for this.

# Demographic Classification:

For demographic classification, I have conducted a thorough customer demographic analysis using Power BI, and here are the key findings presented in a visually engaging manner:

<img width="868" height="635" alt="image" src="https://github.com/user-attachments/assets/af7cc2a1-1a30-4989-b95b-b9aac424eb8f" />

The dataset encompasses a substantial pool of 4000 customers, forming the foundation of our analysis.

<img width="774" height="281" alt="image" src="https://github.com/user-attachments/assets/b6244a59-cd08-4770-8db4-ee0c643f1a87" />

* The majority of our customer base comprises males, accounting for 64.93%, indicating a slightly male-dominated demographic.
* However, the substantial presence of females (35.08%) highlights a diverse customer landscape.

**Age Group Profiling:**

<img width="498" height="288" alt="image" src="https://github.com/user-attachments/assets/4fdc3295-81f7-45bf-bc5c-f0c114fd737d" />

* The age group 25-35 emerges as the most significant segment, with 1498 customers. This group, especially males, exhibits a strong presence.
* Customers aged 35-45 also form a substantial portion (1273), demonstrating a balanced distribution between genders.
* The 45+ age group, while smaller, remains a noteworthy segment that shouldn't be overlooked.

**City-wise Distribution:**

<img width="510" height="403" alt="image" src="https://github.com/user-attachments/assets/b1cb17bb-daa4-4554-bc05-0d3e0f3fedbb" />

* Mumbai takes the lead in terms of customer concentration, with 1078 customers, predominantly males.
* Other major cities like Chennai, Bangalore, and Delhi NCR also contribute significantly to our customer base.

**Occupational Insight:**

<img width="509" height="289" alt="image" src="https://github.com/user-attachments/assets/878ae575-e706-4639-bb53-7b91ddaf3445" />

* Salaried IT Employees represent a large portion of our customers (1294), showcasing a tech-centric demographic.
* The diversity in occupations, including freelancers and business owners, presents an opportunity to tailor services for varied professional needs.

**Marital Status Overview:**

<img width="250" height="276" alt="image" src="https://github.com/user-attachments/assets/0548b917-5599-45f7-871d-315c5cb2f29c" />

* A significant majority of our customers are married (78.41%), emphasizing the importance of considering family-centric financial solutions.
* Unmarried customers, though a smaller segment, still constitute a substantial 21.6% of our customer base.

# Income Utilization & Spending Analysis

In pursuit of illuminating critical insights into customer spending patterns and understanding the average income utilization across diverse segments, a dedicated analytical exploration has been undertaken. To facilitate a comprehensive understanding, a bespoke "Customers Spend Analysis" page has been meticulously crafted within Power BI. This page serves as the epicenter for unraveling intricate details, housing a plethora of Key Performance Indicators (KPIs) and insightful charts and graphs.

<img width="772" height="687" alt="image" src="https://github.com/user-attachments/assets/86c6d47d-2939-49c2-aa1e-b2027b522ee5" />

**Average Income Utilization:**

<img width="260" height="100" alt="image" src="https://github.com/user-attachments/assets/d0a75714-8c00-4af7-b031-3ebe4a226e00" />

* Average Income Utilization stands at 42.82%

**Key Metrics:**

<img width="372" height="98" alt="image" src="https://github.com/user-attachments/assets/6a493e9d-0913-4d13-8176-28941545174b" />

* Total Income in 6 months: $1240M
* Total Spends in 6 months: $531M

**Income, Spend, Utilization by Age Group:**

<img width="476" height="299" alt="image" src="https://github.com/user-attachments/assets/78ae5eb2-3d62-4cf4-b74e-711adff06831" />

* Age group 25-34 exhibits the highest income, spend, and utilization (43.66%).
* Second-highest is the 35-45 age group with a utilization rate of 46.52%.

**Total Spends by Category:**

<img width="570" height="308" alt="image" src="https://github.com/user-attachments/assets/d2b4bbbc-77c2-4166-96bb-d59c9e793cc1" />

* Highest spending in bills category ($105M) with an average utilization of 46%.
* Other significant categories: Grocery ($86M), Electronics ($80M), and the least in Others category ($16M).

**Income, Spend, Utilization by Occupation:**

<img width="492" height="314" alt="image" src="https://github.com/user-attachments/assets/e9132984-0a55-4176-88dc-8f796f58b876" />

* Salaried IT employees lead in income ($477M), spend ($244M), and utilization (51.04%).
* Business Owners show an income of $265M, spend of $88M, and a utilization rate of 33.22%.
* Government employees have the lowest utilization at 29%.

**Income, Spend, Income Utilization by City:**

<img width="567" height="292" alt="image" src="https://github.com/user-attachments/assets/79c83743-4aa8-44cd-9031-fc5879c9b7c7" />

* Mumbai outshines with the highest income and spend, resulting in a utilization rate of 51.43%.
* Chennai, Delhi NCR, Bengaluru, and Hyderabad follow with varying utilization rates.

**Total Spend by Payment Type:**

<img width="369" height="260" alt="image" src="https://github.com/user-attachments/assets/6d3ecdbe-b574-453f-b4c6-17c2b4652a5d" />

* Credit cards dominate spending, accounting for $216M with a utilization rate of 17.45%.
* Other payment types include UPI, debit cards, and net banking.

**Total Spend by Gender:**

<img width="304" height="265" alt="image" src="https://github.com/user-attachments/assets/8899d180-13aa-4c9a-8302-da91b3279e39" />

* Males lead in spending with $357M, while females contribute $154M.

**Spend by Marital Status:**

<img width="303" height="250" alt="image" src="https://github.com/user-attachments/assets/591ea165-2f63-4c8f-9c4d-5ae20cc53c45" />

* Married individuals top the spending charts with $429M, surpassing unmarried individuals at $102M.

**Total Spend by Month:**

<img width="454" height="273" alt="image" src="https://github.com/user-attachments/assets/5152ee4e-9548-4e20-a758-43ace062cf83" />

* September emerges as the highest spending month, accounting for $116M, constituting 21.84% of the total spend.

**Income Utilization by Gender:**

<img width="408" height="271" alt="image" src="https://github.com/user-attachments/assets/a63f9a72-0ee3-483a-b8be-7d225c164249" />

* Males exhibit a higher income utilization rate at 44.39%, compared to females at 39.92%.

**Income Utilization by Marital Status:**

<img width="407" height="281" alt="image" src="https://github.com/user-attachments/assets/7b948f94-6e22-41cd-8a82-dca38f1cc43c" />

* Singles show a utilization rate of 43.06%, slightly surpassing married individuals at 42.77%.

# Table Grid View Page:

<img width="825" height="453" alt="image" src="https://github.com/user-attachments/assets/a7ac2316-9862-4202-8e0c-5a2a0d15e3ed" />

# Recomendation for Next Credit Card

To improve the likelihood of credit card usage among the identified target customers (salaried employees, self-employed individuals, and freelancers), consider incorporating the following key features in the credit card:

**Tailored Rewards Program:**

Create a rewards program that aligns with the spending patterns of salaried employees, self-employed individuals, and freelancers. This could include cash back on common categories of spending such as groceries, dining, and business-related expenses.

**Flexible Payment Options:**

Offer flexible payment plans to accommodate different income structures. This could include customizable monthly payment options, allowing users to adjust their payment schedule based on their cash flow.

**Expense Tracking and Budgeting Tools:**

Provide built-in tools or partner with budgeting apps to help users track their expenses, categorize spending, and set budget goals. This can be particularly beneficial for freelancers and self-employed individuals managing variable income.

**Low Annual Fees and Interest Rates:**

Keep annual fees competitive and offer reasonable interest rates to attract and retain customers. Consider providing introductory offers, lower rates for loyal customers, or special promotions for specific spending categories.

**Contactless and Mobile Payments:**

Ensure the credit card supports contactless payments and integrates with popular mobile payment platforms. This adds convenience for users who prefer digital and contactless transactions.

**Security Features:**

Implement advanced security features such as fraud alerts, biometric authentication, and virtual card numbers to enhance the safety of transactions. Communicate these security measures to build trust among users.





























