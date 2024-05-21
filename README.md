#  Banking Dynamic Risk Profiling and Performance Analysis in Consumer Lending

## Objective

The objective of this case study is to apply advanced data analysis techniques using Excel to deeply understand and effectively manage a loan portfolio. This involves assessing loan risk profiles, evaluating financial performance metrics, gaining insights into borrower behaviors, and ultimately, developing a comprehensive, interactive Excel dashboard. These efforts aim to provide strategic recommendations for optimizing loan portfolio management, mitigating risks, and enhancing decision-making processes for financial institutions and stakeholders in the consumer lending sector.

## **Data Source:**

The loan dataset provides a detailed snapshot of consumer lending, encompassing a wide array of information about individual loans.

1. **id**: A unique identifier for each loan.
2. **year**: The year when the loan was issued.
3. **issue_d**: The specific date when the loan was issued.
4. **final_d**: A date-related field, possibly indicating the final date of the loan term or the date of final payment.
5. **emp_length_int**: Employment length of the borrower, in years, as an integer.
6. **home_ownership**: The housing status of the borrower, indicating whether they own a home, rent, or have another arrangement.
7. **home_ownership_cat**: Categorical encoding of the home ownership status.
8. **income_category**: A categorical representation of the borrower's income level.
9. **annual_inc**: The annual income of the borrower.
10. **income_cat**: A categorical encoding of the borrower's income.
11. **loan_amount**: The amount of money borrowed.
12. **term**: The term of the loan, typically in months or years.
13. **term_cat**: Categorical encoding of the loan term.
14. **application_type**: Indicates whether the loan application was individual or joint.
15. **application_type_cat**: Categorical encoding of the application type.
16. **purpose**: The purpose of the loan (e.g., debt consolidation, home improvement).
17. **purpose_cat**: Categorical encoding of the loan purpose.
18. **interest_payments**: A descriptor of the interest payments (e.g., high, low).
19. **interest_payment_cat**: Categorical encoding of the interest payments.
20. **loan_condition**: Status of the loan (Good Loan and Bad Loan).
21. **loan_condition_cat**: Categorical encoding of the loan condition.
22. **interest_rate**: The interest rate on the loan.
23. **grade**: The loan grade, which is typically an assessment of the loan's risk.
24. **grade_cat**: Categorical encoding of the loan grade.
25. **dti**: The debt-to-income ratio of the borrower.
26. **total_pymnt**: The total payments made on the loan to date.
27. **total_rec_prncp**: The total principal received to date.
28. **recoveries**: The amount recovered on the loan after default.
29. **installment**: The monthly payment owed by the borrower.
30. **region**: The geographical region of the borrower.

    
## Dashboard Outcome
![image](https://github.com/gunjanjoshi-0798/Banking_Excel_project/assets/155617045/ca7fbcf4-fa8e-459d-97f5-ec11ed897ba4)
![image](https://github.com/gunjanjoshi-0798/Banking_Excel_project/assets/155617045/8ed37143-2b4f-44f2-a0e0-538b8b489635)
![image](https://github.com/gunjanjoshi-0798/Banking_Excel_project/assets/155617045/848c82d2-fb86-40db-b214-b57efed767a5)


## Tasks Performed

1. **Income Category and Loan Amount Correlation:** Investigated if there is a correlation between income categories and loan amounts.
2. **Region-wise Loan Analysis:** Found which region has the highest number of loans. Visualized the distribution of loans across different regions.
3. **Debt-to-Income Ratio Insights:** Calculated and analyzed the average debt-to-income ratio for each loan grade.
4. **Loan Amount vs. Annual Income:** Created a scatter plot to analyze the relationship between loan amounts and borrower's annual income.
5. **Grade-wise Profitability Analysis:** Calculated the profitability of loans (total payments received minus the loan amount) for each grade.
6. **Predictive Analysis for Loan Defaults:** Utilized Excel's advanced functions to predict the likelihood of default based on factors like loan amount, income, and employment length.
7. **Risk Analysis Dashboard:** Created a risk analysis dashboard to show the insights about different loan grades and risks associted.

## Key Insights

- Out of the whole dataset 87% are good loans and 13% are bad loans.
- A is highest grade indicating the least risk and G is the lowest grade indicating the highest risk. G Grade loans are very risky loans with high interest rate and high debt-to-income ratio.
- Debt-consolidation and Credit card has the highest no of defaulters, 5398 and 1492 respecively.
- E and F grade loans have the highest debt-to-income ratio.
- Maximum no. of defaulters are in the low annual income salary group and the interest rate is also high for this income group.
- In Cannught most no. of loans are passed with a count of 11444 and least in munster with 7397.
- In mortgage and rent type of home-ownership there are maximum no. of defaulters.
- The stakeholders or the lenders should provide loans for small businesses as it has the highest Loan Profitability index and less number of defaulters.
