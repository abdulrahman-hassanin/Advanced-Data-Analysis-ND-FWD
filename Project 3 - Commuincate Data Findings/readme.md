# (Propser_Loan_Data_Exploration)

## Dataset

> The dataset contains peer to peer loan information of more than 113k people with 81 features. You can find it <a href='https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000'>here</a> and this <a href='https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0'>link</a> explains the dataset vaibles.

## Summary of Findings

During the exploration, I choose the BorrowerAPR and the Estimated Return to be the features of interest to invistigate. 

The <b>bivariate</b> exploration explores the relationship between varibles, the numeric varibles have no correlation unless a quite positive correlation between the estimated return and borrower APR. 

<b>BorrowerAPR</b>
<ul>
    <li>The higher prosper rating cause a higher APR.</li>
    <li>Not employment people has the higher APR median.</li>
    <li>The APR median is almost the same for different duration terms.</li>
</ul>

<b>Estimated Return</b>
<ul>
    <li>the median estimated return decreases with the increaing in the income range.</li>
    <li>The higher prosper rating cause a higher estimed return.</li>
    <li>Long term duration has a high estimated return.</li>
</ul>

The <b>multivariate</b> shows that the rating from AA to E increases the Borrower APR and reduces the amount term duration. the rating from AA to E increases the Estimated Return and increases the counts of 12 months term duration.

## Key Insights for Presentation

> I begin with introducing the features of interest one by one, followed by how they relate to one another using bivriate and multivariate visualizations.