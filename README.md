# Bank-Marketing

Original dataset and link:
https://www.kaggle.com/janiobachmann/bank-marketing-dataset

Objective:
Marketing team has a target, in which they need to make the client or new client to deposit their money at the end of campaign. From the campign result, this could be use as a future analysis for the next campaign.

Term deposit:
Citing from investopdia (https://www.investopedia.com/terms/t/termdeposit.asp)
"A term deposit is a fixed-term investment that includes the deposit of money into an account at a financial institution. Term deposit investments usually carry short-term maturities ranging from one month to a few years and will have varying levels of required minimum deposits"

Variables:
1. age (numeric)
2. job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3. marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4. education: (categorical: primary, secondary, tertiary and unknown)
5. default: has credit in default? (categorical: 'no','yes','unknown')
6. housing: has housing loan? (categorical: 'no','yes','unknown')
7. loan: has personal loan? (categorical: 'no','yes','unknown')
8. balance: Balance of the individual.
9. contact: contact communication type (categorical: 'cellular','telephone')
10. month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
11. day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
12. duration: last contact duration, in seconds (numeric)
13. campaign: number of contacts performed during this campaign and for this client (numeric)
14. days: number of days that passed by after the client was last contacted from a previous campaign (numeric)
15. revious: number of contacts performed before this campaign and for this client (numeric)
16. outcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

Target
17. deposit: has the client subscribed a term deposit? (binary: 'yes','no')
