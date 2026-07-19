**Bank Marketing Campaign Analysis**



**Overview**



This project analyzes data from a bank marketing campaign to understand customer characteristics, campaign performance, and the factors influencing term deposit subscriptions.



Using Python for data cleaning, exploratory data analysis (EDA), and visualization, the project uncovers meaningful patterns that can help banks optimize future marketing campaigns and improve customer conversion rates.





**Business Problem**



Banks invest significant resources in direct marketing campaigns to promote financial products such as term deposits. However, not every campaign results in successful customer conversions.



The objective of this project is to analyze historical campaign data and answer key business questions such as:



\* Which customer segments are most likely to subscribe to a term deposit?

\* Which demographic and financial characteristics influence customer decisions?

\* How effective are current marketing campaigns?

\* What insights can improve future campaign performance?





**Tools \& Technologies**



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Jupyter Notebook





**Project Workflow**



\* Data Loading

\* Data Inspection

\* Data Cleaning

\* Exploratory Data Analysis (EDA)

\* Data Visualization

\* Business Insights

\* Recommendations





**Analysis Performed**



The analysis explores:



\* Customer demographic distribution



\* Subscription trends

\* Campaign performance

\* Financial characteristics

\* Contact methods

\* Previous campaign outcomes

\* Relationships between customer attributes and subscription decisions





**Business Value**



This analysis helps marketing teams:



\* Identify high-potential customer segments

\* Improve campaign targeting

\* Increase subscription conversion rates

\* Optimize marketing strategies using historical customer behavior





Business Recommendations







\*Target by profile, not by volume - Subscription rates vary noticeably by job and education (see section 3) - management customers subscribe at roughly 14% vs. blue-collar at roughly 10%. Prioritize these segments for outbound calls instead of calling everyone equally.



\*Cap the number of contact attempts - The campaign-frequency data shows subscription rate drops steadily after the first contact - 14.6% (1 attempt) → 11.2% (2-3) → 8.3% (4-6) → 5.3% (7+) - so calling the same person repeatedly past about 3 attempts mostly wastes agent time.



\*Loan status is a useful filter - Customers without an existing housing loan subscribe at a higher rate (16.7% vs. 7.7% for those with one); the same holds for personal loans (12.7% vs. 6.7%) - worth factoring into who gets called first.



\*Use the model as a rough prioritization tool, not a hard decision-maker - The baseline logistic regression correctly flags only 5% of actual subscribers in the test set; the class-weighted version catches 63% at the cost of more false positives - good enough to help rank who to call first, not to replace judgment on borderline cases.





**Author**



Muskan Verma

