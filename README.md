# Data-Analytics---Power-Bi-Data-Pros-Survey-Breakdown

This Power BI project consists of analysing the data of the data field professionals survey breakdown to the new domain.

We will be analysing the gathered data in an excel sheet. 


- We will begin importing the dataset and begin cleaning it.
- First of all we will remove the columns without values (Browser, OS, CITY, Country, Referrer).
- Then we will be removing the unuseful columns (Unique ID(because we can add out own ID to diffentitate each value), Email(Anonymous) so there's no need to keep it, Date when the survey was taken will not affect our analysis, also the time spent will not be much relevant.
- As we saw in the dataset the columns ("What Industry do you work in", "Q1 - Which Title Best Fits your Current Role?" and "Country", there's values containing Specify Other part that we can remove from the values).
- Concerning the column "Favorite Programming Language", we will replace the "other:sql" and "other:SQL" by SQL in a nutshell.
- Regarding the country column we've done some renaming.
- As regards the salary column, what we will be is that we'll keep the original column and we will create a copy of that column:
      - First of all, we will split the columns by a delimiter so that we can calculate the avg between the Min and Max of each salary interval.
      - Then we'll create a Custom column to calculate that avg value.
      
      
