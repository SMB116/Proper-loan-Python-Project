# Prosper-loan-Python-Project

# Introduction
The dataset used in this project contains detailed information about borrowers and their loans from Prosper, America’s first marketplace lending platform. In this project, we explore who these borrowers are and their current loan status.

# Preliminary Wrangling
We start by importing the necessary packages for our project, such as numpy, pandas, matplotlib, and seaborn. Next, we load the dataset and take a brief look at the structure of the data. The dataset is a dataframe containing 81 columns and 113938 rows.

Our main goal is to explore who the borrowers are and understand the types of loans they have acquired. We believe that several features will support this investigation. These features include defining the terms of the loan, the loan status, exploring the borrower's employment status, knowing whether they are homeowners, their credit scores, and income range. We also look at the borrower's annual percentage rate and interest rate.

# Univariate Exploration
In this section, we explore individual variables in our dataset. First, we change the headers to lowercase to facilitate readability. We then investigate the type of loan terms and discover that the majority of the borrowers have a 36-month term. Next, we examine the loan status of the borrowers and find that the majority of the loan statuses are current, with a little under 40,000 being complete.

We investigate the borrower's annual percentage rate and find that it ranges from 5% to a little over 40%, with the largest grouping around 20%. Further investigation is needed, but the data shows that borrower credit scores seem to be fairly good.

We examine the credit score of the borrowers and find that our hypothesis is correct. A good credit score is considered 670 and above, and our borrowers' lower-rated credit scores have ranged from 640 and higher, which is considered fairly to good. Note that credit score values that were zero are replaced to have a score of 300 because you cannot have a credit score of zero, 300 is the lowest credit score you can have.

We then investigate whether the borrowers are homeowners and find that there are more homeowners in our dataset, indicating that there are more secured loans with the lender since homeowners' properties are used as security for the loans.

We also examine the range of income for our borrowers and find that the majority of the borrowers are below or within and slightly above the average salary in the USA. We cleaned the income range that was displayed as 'not displayed' rows, renaming them to "Prefer Not to Say'. We also had some borrowers with an income of $0; we grouped the information to be combined with 'not employed.'

Finally, we look at the borrowers' rate and find that further analysis is needed.

# Bivariate Exploration
In this section, we explore the relationship between two variables in our dataset. We investigate whether homeownership affects the loan term and find that a greater number of homeowners have a 60-month term compared to non-homeowners. Nevertheless, more non-homeowners have a 36-month term, which is slightly above the number of homeowners.

We also examine the relationship between the borrower's annual percentage rate and interest rate and find a strong positive correlation.

# Conclusion
Our exploratory data analysis shows that Prosper's borrowers are generally good credit risks. The majority of borrowers have a 36-month term, and most loans are in the current status. The credit scores of borrowers are considered fairly to good, with a good credit score of 670 and above. The majority of borrowers are below or within and slightly above the average salary in the USA. Homeownership affects the loan term, with a greater number of homeowners having a 60-month term compared to non-homeowners. Finally, we found a strong positive correlation between the borrower's annual percentage rate and interest rate.
