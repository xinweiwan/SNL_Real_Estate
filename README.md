# A Quick Guide to the SNL Real Estate Database

This is a quick guide to download the property-level information from the SNL real estate database.

## Overview of the Database

https://www.support.marketplace.spglobal.com/en/datasets/snl/snlreproperty/snl-real-estate-property-data-user-guide

## Registration

Sign up an account on S&P Global Market Intelligence Platform (https://www.spglobal.com/marketintelligence/en/). Choose "ProductLogin", and then "S&P Capital IQ Pro". Remember to use the Cambridge Email (or other subscribed institutions).

## Download Data

* Login to the S&P Capital IQ platform.
* Select "Screener" -> "Real Estate Properties"
* Set the filtering fules (e.g., location, company's name, etc.) in the **CRITERIA** panel.
* In the **RESULTS** panel, click on **Display Columns** and select the variables you want to download. The variables definitions can be found from the Data User Guide above.
* Click **Run Screen**.
* Click **Export** to save the query results.
* Remember to save the screen criteria if you would like to update the database in future.
* The screener interface is user-friendly, but there is a limit on the entries shown per page. Alternatively, you can use the XpressAPI to complete the task: https://xpressapi.marketplace.spglobal.com/swagger/swagger.html?urls.primaryName=snlreproperty
