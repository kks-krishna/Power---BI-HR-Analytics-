# AEC_Power_BI_July_2025

<hr>

- ✅ **BitBucket Link:** <https://bitbucket.org/toarnabtrainer/aec_power_bi_july_2025/src/main/> or <https://tinyurl.com/mntembe2>
- ✅ **Online Session MS-Teams Link for all sessions:** <https://tinyurl.com/2s3yxjnr>
- ✅ **Notepad.pw Link:** <https://notepad.pw/p5Achs3EAtvkDLsbUxOg>
  
<hr>

## MS-Power BI Resources:

**Power BI Download and Tutorial Links:**<br>
* **PowerBI Download Link:** https://www.microsoft.com/en-us/download/details.aspx?id=58494 <br>
* **Tutorial and Official Documentation on MS-Power BI Link:** https://docs.microsoft.com/en-us/power-bi/desktop-create-and-manage-relationships <br>
* **Learn Power BI:** https://powerbi.microsoft.com/en-us/learning/ <br>
* **Power BI for Absolute Beginners:** https://www.tutorialspoint.com/power_bi/index.htm

**Important Classwork Resources:**<br>
* **HTML Color Codes Web-Link-1:** <https://colorhunt.co/> <br>
* **HTML Color Codes Web-Link-2:** <https://htmlcolorcodes.com/> <br>
* **Dashboard Background Image Lnk:** <https://www.freepik.com/free-photos-vectors/dashboard-background> <br>
* **PDF Link on the Cloud:** <https://www.indiapost.gov.in/VAS/DOP_PDFFiles/Civillistnew.pdf> <br>
* **Web Portal Link:** <https://www.contextures.com/xlsampledata01.html>

**MS-Power BI Data Compresion Capability:**<br>
* **PracticeData1.xlsx ->** Size 705 KB <br>
* **ClassWork.pbix (After all data import) ->** Size 64 KB <br>
* **ClassWork.pbix (After Unpivot) ->** Size 56 KB <br>
* **ClassWork.pbix (After Country_Sales Query creation) ->** Size 61 KB <br>
* **ClassWork.pbix (After Total_Sales_PQEW) ->** Size 65 KB <br>
* **ClassWork.pbix (After Total_Sales_PBIDW) ->** Size 66 KB <br>
* **ClassWork.pbix (After Total_Sales measure creation) ->** Size 66 KB <br>
* **ClassWork.pbix (After Total_Sales_Measure column creation) ->** Size 67 KB

**Table Formats:**<br>
<b>
<pre>
* Wide Format (Unstacked Format) ------------------------> Long Format (Stacked Format)
                                     Unpivot Operation

* Long Format (Stacked Format) ------------------------> Wide Format (Unstacked Format)
                                     Pivot Operation
</pre>
</b>

**Assignment on Merge operations:**<br>
* **Query-1:** List those product details which has no discount. <br>
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/eb4c8b10-b987-4991-904a-d34bc240cca6) <br>
* **Query-2:** List only those discounted product details along with discount amount and discounted price. <br>
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/050f2529-37db-471f-ac10-ff18360a74a5) <br>
* **Query-3:** Against all products, display discount amount and discounted price. Fill with 0 where discount % is null. <br>
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/a5eb2259-e78e-4a1d-94c1-18d2da8c7ffe) <br>
* **Query-4:** List those category details which has no product. <br>
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/6f144d15-1dd3-41e8-828e-574c07f2af75)
  
**Lookup/Dimension Tables and Data/Fact Tables:** <br>
Lookup Tables or Dimension Tables will have Primary Keys, will answer Who, What, Where, When and How <br>
Data Tables or Fact Table will have Foreign Keys, and will contain transactional data <br> <br>
**Lookup/Dimension Tables:** Customer (Who), Product (What), Territories (Where), Calendar (When and How) <br>
**Data/Fact Tables:** Sales, Budget

**Operations on Budget Workbook:** <br>
* Delete the promoted header <br>
* Delete first 3 null rows <br>
* Promote the first row as a header <br>
* Delete last total column <br>
* Filter out rows from the first column containing “Total” <br>
* Unpivot month columns labelled from Jan to Dec <br>
* Rename new created columns to Month and BudgetAmount <br>
* Change the data type of Month column to Date <br>
* Select close and apply <br>

**Data Relationships for the Budget Project:** <br>
* Sales(CustomerKey) -> Customer(CustomerKey) <br>
* Sales(OrderDate) -> Calendar(Date) <br>
* Sales(ProductKey) -> Product(ProductKey) <br>
* Sales(SalesTerritoryKey) -> Territories(SalesTerritoryKey) <br>
* Budget(ProductKey) -> Product(ProductKey) <br>
* Budget(Month) -> Calendar(Date) <br>

**Suggested DAX Formulaes for Creating Measures:** <br>
* MyBudget = SUM(Budget[BudgetAmount]) <br>
* MySales = SUM(Sales[SalesAmount]) <br>
* MyVariance = [MySales] - [MyBudget] <br>
* MyVariance% = DIVIDE([MyVariance], [MyBudget], 0) <br>
* MyComments = IF([MyVariance] < -100000, "Take Care", IF([MyVariance] < 0, "Not OK", "OK"))

**Suggested Tables Summaries (After filtering on Year 2016):** <br>
*	**Table1:** Calendar[Year], Calendar[Month], Sum of Sales[SalesAmount]  <br>
*	**Table2:** Calendar[Year], Calendar[Month], Sum of Budget[BudgetAmount] <br>
*	**Table3:** Territories[Country], Sum of Sales[SalesAmount] <br>
*	**Table4:** Calendar[Year], Calendar[Month], Sum of Sales[SalesAmount], Sum of Budget[BudgetAmount] <br>
*   **Table5:** Calendar[Year], Calendar[Month], Budget[MySales], Budget[MyBudget], Budget[MyVariance], Budget[MyVariance%], Budget[MyComment]

<hr>

# Different Join Operations:

![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/5715ba40-1546-40d7-984f-3002d411cc57)

<hr>

![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/e2a3d88f-e1ab-4459-b1ec-28fce08a21b1)

<hr>

## Towards Growth and Towards Success

![image](https://github.com/user-attachments/assets/078e5be0-8bfb-457b-8864-4c9fc4fcedf9)

<hr>

## 9 Time Management Tools for Leaders

![image](https://github.com/user-attachments/assets/cc9d7325-c4da-42ce-a3fb-f43993766925)

<hr>
