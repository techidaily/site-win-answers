---
title: Innovative Data Compiling Tools Unveiled in Recent Microsoft Excel Enhancement
date: 2024-08-27T23:57:37.111Z
updated: 2024-08-28T23:57:37.111Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/microsoft-excel-logo-1.jpg
---

## Innovative Data Compiling Tools Unveiled in Recent Microsoft Excel Enhancement

Microsoft Excel now offers GROUPBY and PIVOTBY aggregation functions, which make it easier to collect and organize data into compact summaries or tables. Plus, a new PERCENTOF function allows you to quickly return percentages from raw data. These functions are still in beta and are currently limited to Microsoft 365 Insider builds.

 The [GROUPBY](https://support.microsoft.com/en-us/office/groupby-function-5e08ae8c-6800-4b72-b623-c41773611505) function is extremely simple and requires just three arguments—what to group by, the values that you want to aggregate, and the function that you'd like to use for aggregation. In an example provided by Microsoft, the function **\=GROUPBY(tbl\[Category\],tbl\[Sales\],SUM)** reduces some complicated sales information into a two-column table. The left side of the table lists product categories, while the right side contains sales numbers aggregated by the SUM function.

 Microsoft's demonstration of the GROUPBY function is shown below.

![Using the GROUPBY function in Microsoft Excel to split item sales into product categories with corresponding sales figures.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-5.png) 

Microsoft

 Excel's new [PIVOTBY](https://support.microsoft.com/en-us/office/pivotby-function-de86516a-90ad-4ced-8522-3a25fac389cf) function is extremely similar to GROUPBY, but it takes four arguments instead of three. Using the same dataset from the previous example, Microsoft uses the function **\=PIVOTBY(tbl\[Category\],tbl\[Year\],tbl\[Sales,MAX)** to show the largest sales by product category and year. Total sales for each product category are also included.

 Notice the use of the MAX function in this example. GROUPBY and PIVOTBY allow you to select from a list of Excel's lambda functions, which can remove some of the guesswork when aggregating data. Microsoft plans to expand etc lambda support to all functions that support lambda, meaning that some large functions will become more streamlined and legible.

![Using the PIVOTBY function in Microsoft Excel to split item sales into categories, with each year of sales separated into columns.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-2.png) 

Microsoft

 The GROUPBY and PIVOTBY functions aren't groundbreaking, but they're simple, tidy, and automatically updated by changes to your data. Also, you can pull some pretty interesting tricks by fooling around with the new functions' full arguments. Microsoft seems especially proud of text aggregation, which can be performed by using the GROUPBY function with the addition of a sorting argument and ARRAYTOTEXT.

 There's also the new PERCENTOF function. Microsoft says that [PERCENTOF](https://support.microsoft.com/en-us/office/percentof-function-7c66da0a-ac30-45d0-bfc7-834a8bd7c962) is "particularly useful" when paired with GROUPBY or PIVOTBY, as it can spit out complex percentage values with relatively few steps. (Technically speaking, PERCENTOF is logically equivalent to **\=SUM(data\_subset)/SUM(data\_all)**.)

 Microsoft Excel's new functions are currently limited to Microsoft 365 Insider builds. Do not use these functions in important spreadsheets, as they are still in beta and may be modified in a stable release.

 Source: [Microsoft](https://insider.microsoft365.com/en-us/blog/new-aggregation-functions-in-excel-groupby-and-pivotby)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->