<<<<<<< HEAD
## Description of project
In a sizzling Real Estate market, what fuels property transactions? In this project, Ammar, Bich, Simon, and I looked at a few factors that influence median suburban house prices. We sought to find the possible impacts of location, weather, age, and lifestyle factors on median house prices in Victoria. We used APIs, available CSVs, and Python Jupyter Notebooks to source our data, analyze it, and present it using matplotlib, conducting t-tests as well. <br>
First, we analyzed the impact of the suburb, region, and distance to the Melbourne CBD on median property prices and found a slight correlation between the two in that the closer the suburb was to the CBD, the higher the median house price was (with a few outliers). We then found that there was no significant correlation between suburban temperature and house price, nor was there a significant correlation between the age of the building and the median house price. There was a slight correlation between the number of facilities in a given suburb and its house price but we found that some facilities had stronger correlations than others. For example, the number of natural facilities had a significant negative correlation with house prices, indicating that people perhaps prefer more urban and less natural environments. <br>
We did come across a few limitations while conducting our study as the files that we used to compare price to distance and year built in Melbourne were for properties sold in 2016 and 2017, making the data slightly dated. We also only looked at houses and not apartments and units, which are more popular in urbanized areas. Furthermore, with our current Geoapify membership, we were limited to only 20 responses per facility per suburb. In actual fact, there could have been a lot more facilities for certain suburbs that could have had a major impact on the final correlation between the number of facilities in a given suburb and house prices. These limitations open the opportunity for future analysis. <br>

## Description of files and folders
Resources - storage of CSV files <br>
Graphs - output of graphs coded and saved <br>
config.py - storage of API keys <br>

Age_and_distance_to_CBD.ipynb - Bich's and Ammar's code. Looks at property age and distance from CBD, and their effects on suburban house prices. <br>
Project 1 Presentation - pdf file of the class presentation. <br>
Temp_Median_Price - Simon's code looks at the effect of varying temperatures on suburban house prices. <br>
Total_num_facilities_for_suburb - Oormi's first code. Generates csv of the total number of facilities for various categories for every available Victorian suburb as well as the total number of facilities overall. WARNING: due to the large amount of data, cell 6 takes about an hour to run. <br>
Num_facilities_v_houseprices - Oormi's second code. Statistical analysis for the total number of facilities for various categories. A separate notebook is used because the previously coded CSV takes an hour to run. <br>

## References
https://www.geeksforgeeks.org/reading-excel-file-using-python/ <br>
https://www.land.vic.gov.au/valuations/resources-and-reports/property-sales-statistics <br>
https://www.geeksforgeeks.org/string-capitalize-python/ <br>
https://cms.qut.edu.au/__data/assets/pdf_file/0012/927957/Laurie_Buys_SmartCities.pdf <br>
=======
Property Sales for Melbourne City source: ​​https://www.kaggle.com/datasets/amalab182/property-salesmelbourne-city?select=Property+Sales+of+Melbourne+City.csv 
>>>>>>> c1df632a09739096775672b1aca0e77f85ffa5aa
