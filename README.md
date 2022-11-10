# Determining the Association of Various Factors with Prosper Loan Rating


The Prosper Loan Data which is used in this project has information 
about 113,937 prosper loans listed over a period of 6 years(2009 - 2014).
These information include prosper score, prosper rating (alpha), prosper rating (num),
loan status, loan term, loan original amount, borrower's occupation, employment status,
stated monthly income, available bank card credit, listing category, loan date, etc.<br>


## Summary of Findings


In the data exploration, while checking out the terms of loans listed,
I found out that 12 months, 60 months and 36 months loan terms were ranked 
in this order according their average prosper ratings.<br>

I found that there is a strong negative association
between the prosper rating of loans and borrower rates.
Higher borrower rates were associated with lower prosper rating,
while lower borrower rates were found to be associated with higher prosper rating.
This relationship persisted across the six years covered in this study.<br>

Loan original amount, stated monthly income and available bank card credit 
were found to have a positive, though not strong, association with prosper rating. 
Higher prosper ratings were associated with higher amounts of these variables and vice versa.
The relationship proved same over the years.<br>

I also found that on average, loans given to the employed have a higher prosper
rating compared to loans given to the unemployed and other workers. 
The employed had the highest average prosper rating, while the unemployed had the least.<br>

The highest borrowing occupations didn't necessarily have the better average prosper rating.
Loans given to students of technical schools had the highest average prosper rating, 
despite being the least borrowing occupation. Loans given to judges, doctors, pharmacists 
and chemical engineers also had high average prosper ratings.
Other low rated occupations had average ratings above 3, except college sophomore students,
whose loans had the least average prosper rating of below 3.
