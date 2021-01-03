# Exploratory-Data-Analysis-(EDA)
Exploratory Data Analysis (EDA) of "Historical Sales and Active Inventory"

EDA or Exploratory Data Analysis is the brainstorming stage of Machine Learning. It is a very important step which takes place after feature engineering and acquiring data and it should be done before any modeling. It's very important for a data scientist to be able to understand the nature of the data without making assumptions.

The purpose of EDA is to use summary statistics and visualizations to better understand data, and find clues about the tendencies (the patterns and trends in the data) of the data, its quality and to formulate assumptions and the hypothesis of our analysis. At this stage, all the useful insights are drawn and correlations between the variables are understood.

EDA or Exploratory Data Analysis is an approach for summarizing, visualizing, and becoming intimately familiar with the important characteristics of a data set.

# The main objective is to cover how to:
1. Read and examine a dataset and classify variables by their type: Quantitative vs. Categorical
2. Handle categorical variables with numerically coded values
3. Perform univariate and bivariate analysis and derive meaningful insights about the dataset
4. Identify and treat missing values and remove dataset outliers
5. Build a correlation matrix to identify relevant variables

## The dataset contains a detailed set of products in an inventory and the main problem statement here is to determine the products that should continue to sell, and which products to remove from the inventory.

The file contains the observations of both historical sales and active inventory data.

The end solution here is to create a model that will predict which products to keep and which to remove from the inventory.

we’ll perform EDA on this data to understand the data better.

# Content: 

The file contains historical sales data (identified with the column titled File_Type) along with current active inventory that is in need of evaluation (i.e., File Type = "Active").

The historical data shows sales for the past 6 months. The binary target (1 = sale, 0 = no sale in past six months) is likely the primary target that should drive the analysis.

The other columns contain numeric and categorical attributes that we deem relevant to sales.

Note that some of the historical sales SKUs are ALSO included in the active inventory.

A few comments about the attributes included, as we realize we may have some attributes that are unnecessary or may need to be explained.

--> SKU_number: This is the unique identifier for each product.

--> Order: Just a sequential counter. Can be ignored.

--> SoldFlag: 1 = sold in past 6 mos. 0 = Not sold

--> MarketingType = Two categories of how we market the product. This should probably be ignored, or better yet, each type should be considered independently.

--> New_Release_Flag = Any product that has had a future release (i.e., Release Number > 1)

## Data Visualizing

![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/filetype.png)

![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/marketingtype.png)

![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/soldflag.png)

![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/strengthfactor.png)


![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/pairplot.png)


![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/heatmap.png)


![](https://github.com/ShivankUdayawal/Exploratory-Data-Analysis-EDA-/blob/main/itemcount.png)

