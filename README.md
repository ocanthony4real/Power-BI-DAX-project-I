This project is aimed at analyzing the sales made by a company for the fiscal year, 2019. The data were stored by month and in CSV format. For the sake of showing the efficiency of this report, the 12 files for the 12 months will be divided into two. The analysis will be done on the first six files, after which the remaining six file will be added to the initial folder. The report will then be refreshed. The report will automatically update to include the latter files. 

Step 1:

![Project_B1](https://user-images.githubusercontent.com/101093568/159160633-5637553f-9b12-425f-b2d3-c995ccedd5c7.png)

I imported the files through Power Query.

Step 2:

![Project_B2](https://user-images.githubusercontent.com/101093568/159160699-8ec2c4be-8079-4052-819e-c1b5beca0241.png)

I proceeded to clean the files by reordering the columns, changing the data types, removing empty rows, and also removing columns that won’t be useful in the analysis. I employed an easier and more efficient method by simply working on a sample file and then invoking it as a custom function over other files (since the files were similar).

Step 3:

![Projec_B3](https://user-images.githubusercontent.com/101093568/159160768-f48cb5aa-3029-4bae-8f40-7d96226df595.png)

I wrote DAX formulas to calculate the number of items sold, total revenue, percentage of total sales (by each month), and cumulative total sales.

Step 4:

![Projec_B4](https://user-images.githubusercontent.com/101093568/159160795-7777fe61-65c5-4e1b-9c4b-658d8095bb4b.png)

I made simple charts showing the revenue generated by each product and the number of items sold each month. The slicer at the upper right helps to filter the total revenue of each product by the selected months.

Step 5:


![Project_B5](https://user-images.githubusercontent.com/101093568/159160825-b77c64b0-78eb-4343-91fd-27de4624b4f9.png)

I included the files of the remaining six months in the folder the report is pointing at and refreshed it. It automatically updated.
With these charts, the business owner can be able to see which product(s) generated the highest revenue in the fiscal year. The business owner may decide to use such product as the strength of the business. Conversely, the business owner may decide to put more effort in marketing other products with low sales in order to improve sales in the next fiscal year.

Also, the business owner will be able to detect the months with high number of sales and subsequently make provisions to maximize such period in subsequent years to make better sales.
