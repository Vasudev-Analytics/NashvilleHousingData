# NashvilleHousingData
In this personal project, the main agenda is cleaning the dataset making it usable for further data analysis and dashboard creation. The data which are scraped from the web or data from the servers, will not be clean. There will be issues like NULL values, empty boxes, vague names and data with understandable format. To tackle this issue, SQL is the best possibible solution.

In this project we take raw housing data and transform it in SQL Server to make it more usable for analysis. The main steps taken care before data analysis are:

Standardize Date Format
Populate Property Address data
Breaking out Address into Individual Columns (Address, City, State)
Change Y and N to Yes and No in "Sold as Vacant" field
Remove Duplicates
Delete Unused Columns
There is an issue in 2023 SQL server i.e. importing the excel file directly using database -> tasks -> import/export wizard. An error pops up. Hence, OPENROW and BULK INSERT can also be used in this process.

Note: Issue will be encountered to import the dataset in .csv format or .xlsx format in SSMS. Instead import can be done using a flatfile. Basically converting the .xlsx file to .csv file. Error encounter can be avoided.
