# TOOL1_FINAL_PROJECT

This folder is to be used to house all code and description of our Data Science Tool's Final Project. Please refer to the information below along with the jupyter notebook.




## Dataset and motivation:

We will be using the Skims website to gather inventory data of products sold. To gather this data, product inventory, we will have to scrape the following tabs from the Skims website https://skims.com/:

+ Skims Bras - https://skims.com/collections/bras
+ Skims Underwear - https://skims.com/collections/underwear
+ Skims Clothing & Lounge - https://skims.com/collections/clothing / https://skims.com/collections/loungewear
+ Skims Shapewear - https://skims.com/collections/shapewear

From these tabs we were able to scrape metadata that contains the product name, category and collection the product was released under, color, sizes, pricing information, as well as product images. There was additional data that was made available through our scrapes including various options for sorting and filter your product views to what is of most interest to you - including style of clothing, size, color, price (high to low or low to high), as well as the search button. Many of these attributes will not be used within the scope of this project.


## Task definition/research question:

In this project we will be analyzing the various product categories in depth. We will identify which colors, sizes, and products are being sold and what the inventory of these products is currently. For the purposes of this project we will use simulated purchase orders to provide our analysis. With the simulated purchases we can identify popular items that can then be expanded upon, in future analysis, using real world customer data to inform buyers of popular items that are selling out quickly. For the purposes of this assignment customer information, including purchase orders, will be simulated.

## Literature review:

The exploratory analysis that we conducted is common practice in the merchandise/sales world. But without having access to the backend of a website to collect customer information our analysis, at best, an estimate. What is unique about this project is we can start to see how companies plan inventory and stock products based on sales numbers. But this leaves the question of how social norms play into the inventories and purchase orders of the large retailers. In this day and age size inclusivity is a hotbutton issue as more and more underrepresented groups are reclaiming their space in the world. But how does this play into inventory when a company's sole goal is to make a profit? 

There is a fine balance to understand the number of sales that are made at each size as compared to the inventory that is carried by the company and assess how that influences the selling rates. If a product only has 5 pieces available in a size that is subject to sell out quicker but does that give a true and accurate reading of the demand in the market? Additionally, how does this compare to "standard sizes" (i.e., XS-XL) that may have higher inventory and take longer to sell out? These would truly be the more popular items if you consider all factors but initial reports may give a false impression if you are only looking at time to sell out and not a comprehensive comparison against starting inventory and time listed. 

Within this report there are several resources we referenced when analyzing and visualizing our data to understand the current trends that businesses typically want to review for profitability and inventory. These sources include:

+ https://ieeexplore.ieee.org/document/9154038
+ https://www.netsuite.com/portal/resource/articles/inventory-management/inventory-analysis.shtml
+ https://docs.oracle.com/cd/E26228_01/doc.93/e21560/rvw_inv_anal_rpts.htm#WEAIM351
+ https://en.wikipedia.org/wiki/Skims

