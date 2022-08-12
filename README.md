![Electronics Sales Analysis Picture](https://user-images.githubusercontent.com/78387629/184169202-c2157cc1-09dc-43b1-99e3-50acd53a494e.jpg)
# ELECTRONICS_SALES_ANALYSIS
 A virtual Electronics Company Analysis. The Electronics company operates in the 36 States of Nigeria and has been in operation for four (4) years.
___
## PROJECT DESCRIPTION

___
## DATA SOURCE
The Data used for this analysis was downloaded from Github. Link below:
- https://github.com/Fabulousnani/Data-Developer-Bootcamp/blob/main/Electronic%20Sales.xlsx
___
## PROBLEM STATEMENT

___
## DATA/DESIGN METHODOLOGY
I downloaded the raw file dataset to my PC from Github, hence creating a folder to serve as my Datalake.
I then created a Power BI file to consolidate the data. I used Power BI to Explore, Transform and Load (ETL) the data. I also used the tool to carryout my Exploratory Data Analysis (EDA) and Data Visualization.

After connecting the Excel Workbook to the Power BI in the Model Page, I opened the Data Page where I carried out some DAX (Data Analysis Expressions) to ascertain variables that will help my analysis namely: the Sales, Total Cost, Profit and Status. Afterwards I built the Data Visualizations in the Report Page. There also I did some formatting to the visuals, choosing the most suitable visual to present the Data such as the Filled Map to ascertain the top 10 States by Profit. I also introduced slicers to enhance my visuals.
I also created a bookmark with the button to enable readers load or close some information on the Cost and Profit Report Page, this was done to enhance the loading time of the page.

I also used basic PowerPoint knowledge to provide a few design elements to my visuals.
All this were used to dig deep into the data and arrive at insightful results.

**DAX Reference:**
- Sales = [Unit Price] * [Order Qty]
- Total Cost = [Order Qty] * [Unit Cost]
- Profit = [Sales] – [Total Cost]
- Status = If ([Profit] <=0, “Loss”, “Gain”)
- BG Transparent = “rgba(255,255,255,0)”
___
## FINDINGS AND DATA ANALYSIS
![UPDATED SALES REPORT](https://user-images.githubusercontent.com/78387629/184326689-e0b70b04-d35c-4f91-bed2-3906b14d3f0f.jpg)
![Cost and Profit Report](https://user-images.githubusercontent.com/78387629/184326729-a794e903-acc4-4392-8604-1759e5775aea.jpg)
1. Throughout the business lifetime the customers transacted via different channels. In FCT, North East and North West customers transacted through the Store channel only; In the North Central, customers explored three different channels in their transactions namely: Online, Reseller and Store; In the South East, customers explored three different channels in their transactions namely: Store, Catalog and Online; whereas In the South South and South West, customers used just two channels namely: Store and Reseller.
2.	The business has scaled her sales in the Category of Products with Computers, Camera and Camcorders making the most Sales everywhere, unlike Audio making the least of sales. 
3.	No Discount Promotion Name has the highest generated Profit everywhere.
4.	Ebonyi has the most generated Profit.
5.	I discovered that as of November 2014 Total Cost dropped from 
___
## RECOMMENDATION

___
### CONCLUSION

___
#### ATTRIBUTION
1. The plus and minus button icon I used in my visuals is attributed to Repopng.
2. The color schemes are attributed Adobe and Coolors.
3. The dataset I used for the work is attributed to Mr Fabulousnani.

[@githubFabulousnani](https://github.com/Fabulousnani/Fabulousnani) for putting up the Data Developer bootcamp 1st edition; providing us with Datasets to practice and equipping us from his wealth of Knowledge. Thank you so much Sir.
___
