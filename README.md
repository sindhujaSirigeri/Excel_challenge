# Excel_challenge
## Background

Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people have used crowdfunding to launch new products and generate buzz, but not every project have found success.

### Instructions

Using the Excel workbook in the .zip file, I modified and analysed the sample-project data to try to uncover market trends.

1.  **Conditional Formatting**

    -   I applied conditional formatting to fill each cell in the outcome column with a different colour, depending on whether the associated campaign was successful, failed, cancelled, or currently live.

3.  **Percent Funded Column**
    
    -   I created a new column called `Percent Funded` using a formula to find how much money a campaign made relative to its initial funding goal.
    -   I applied conditional formatting to the `Percent Funded` column according to a three-colour scale, starting at 0 with dark red, transitioning to green at 100, and blue at 200.

4.  **Average Donation Column**
    
    -   I created a new column called `Average Donation` using a formula to find how much each project backer paid on average.

5.  **Parent and Sub-Category Columns**
    
    -   I created two new columns, `Parent Category` and `Sub-Category`, using formulas to split the `Category and Sub-Category` column into two separate columns.

6.  **Pivot Tables and Charts**
    
    -   I created a new sheet with a pivot table to count how many campaigns were successful, failed, cancelled, or currently live per category.
    -   I created a stacked-column pivot chart that could be filtered by country based on this table.
    -   I created another pivot table to count how many campaigns were successful, failed, cancelled, or currently live per sub-category.
    -   I created a stacked-column pivot chart that could be filtered by country and parent category based on this table.

7.  **Date Conversion**
    
    -   I created a new column named `Date Created Conversion` to convert the `launched_at` data into Excel's date format using a provided formula.
    -   I created a new column named `Date Ended Conversion` to convert the `deadline` data into Excel's date format using a provided formula.

8.  **Additional Pivot Table and Chart**
    
    -   I created a new sheet with a pivot table that had a column of outcome, rows of `Date Created Conversion`, values based on the count of outcome, and filters based on parent category and years.
    -   I created a pivot-chart line graph to visualise this new table.

9.  **Report**
    
    -   I created a report in Microsoft Word answering the following questions:
        -   Given the provided data, what were three conclusions that I could draw about crowdfunding campaigns?
        -   What were some limitations of this dataset?
        -   What were some other possible tables and/or graphs that I could create, and what additional value would they provide?

### Conclusion

This project provided insights into the trends and patterns in crowdfunding campaigns, helping to identify factors that contribute to their success or failure.

### Skills Acquired

After all of my learning and practice in this module, I have learnt to:

-   Summarise high-level analytic strategies and tools.
-   Explain the benefits of using pivot tables.
-   Generate and interpret pivot tables.
-   Use VLOOKUPs and HLOOKUPs.
-   Implement conditional formatting based on logical rules.
-   Create, modify, and stylise basic charts from start to finish in Microsoft Excel.
-   Create scatter plots and trend lines.
-   Create charts that contain filtered data.
-   Create regressions and calculate moving averages in Excel.
