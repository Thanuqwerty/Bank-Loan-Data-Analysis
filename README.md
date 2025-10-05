**BANK LOAN DATA ANALYSIS**

**PROJECT OVERVIEW**

This project provides a comprehensive analysis of bank loan data. The primary goal is to perform exploratory data analysis (EDA), extract key performance indicators (KPIs), and create an interactive dashboard to visualize the insights. The analysis covers various aspects of the loan data, including applicant demographics, loan status, financial metrics, and trends over time, to help stakeholders understand loan performance and risk.

The project utilizes a combination of SQL for data querying, Python for exploratory analysis, and Power BI for creating a dynamic and insightful dashboard.

**TOOLS AND TECHNOLOGIES USED**

  - **Database:** SQL (for data extraction, transformation, and calculation of KPIs) 
  - **Programming Language:** Python (for data cleaning and exploratory data analysis)
  - **Libraries:** Pandas, NumPy, Matplotlib
  - **Business Intelligence:** Microsoft Power BI (To Create dashboards and Perform Visualization  ) 

**KEY PERFORMANCE INDICATORS (KPIs)**

The analysis focuses on several key metrics to evaluate the loan portfolio's performance:

  - **Total Loan Applications:** 38.6K applicants.
  - **Month-to-Date (MTD) Loan Applications:** 4.3K with a 6.9% Month-over-Month (MoM) growth.
  - **Total Funded Amount:** $436M issued to applicants.
  - **MTD Funded Amount:** $54.0M, showing a 13.0% MoM increase.
  - **Total Amount Received:** $473M collected from borrowers.
  - **MTD Amount Received:** $58.1M, a 15.8% MoM increase.
  - **Average Interest Rate:** 12.0% across all loans.
  - **Average Debt-to-Income (DTI) Ratio:** 13.3% for all applicants.

**GOOD LOAN VS. BAD LOAN ANALYSIS**

The project categorizes loans into "Good Loans" (Fully Paid, Current) and "Bad Loans" (Charged Off) to assess portfolio risk.

  - **Good Loan Metrics:**

      - **Percentage:** 86.2% of loans are classified as Good Loans.
      - **Applications:** 33K applications.
      - **Funded Amount:** $370.2M.
      - **Amount Received:** $435.8M.

  - **Bad Loan Metrics:**

      - **Percentage:** 13.8% of loans are classified as Bad Loans.
      - **Applications:** 5.3K applications.
      - **Funded Amount:** $65.5M.
      - **Amount Received:** $37.3M.

**POWER BI DASHBOARD**

An interactive, multi-page dashboard was created in Power BI to present the findings

**1. Summary Page**

This page provides a high-level overview of the most critical KPIs and a breakdown of loan status.

<img width="1920" height="1080" alt="Summary of Bank Loan Data Analysis" src="https://github.com/user-attachments/assets/02404c43-3121-42d3-82b4-4ea3d0877958" />

(A screenshot showing the summary page with KPIs like Total Loan Applicants, Total Funded Amount, and Good vs. Bad Loan pie charts)


**2. Overview Page**

This page offers deeper insights through various visualizations, breaking down the total loan applications by different categories

  - **Charts Include:**
      - Total Loan Applications by Month 
      - Total Loan Applications by State 
      - Total Loan Applications by Purpose 
      - Total Loan Applications by Home Ownership (Rent, Mortgage, Own)
        
<img width="1920" height="1080" alt="Overview of Bank Loan Data Analysis" src="https://github.com/user-attachments/assets/eeb76cd8-8969-4de2-a166-0eb54f02ef88" />

(A screenshot showing the overview page with maps, bar charts, and line graphs for different loan application metrics)

**3. Details Page**

This page provides a granular, table-level view of each loan, allowing for detailed inspection of individual records.

<img width="1920" height="1080" alt="Details of Bank Loan Data Analysis" src="https://github.com/user-attachments/assets/6525d127-87d8-4f45-ad2f-df2a04e4883f" />

(A screenshot showing the details page with a data table of individual loans)



 
