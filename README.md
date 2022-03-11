# vehicle price analysis
Alec H | Andrew P | British G | Vilma D


# Intro

The purpose of this project was to gather and detail how a data set could be used to display the valuation of a class of vehicle across it's lifetime. 

# Data Set 
<https://www.kaggle.com/cisautomotiveapi/large-car-dataset?>

The data set was massive and contained so much awesome information that would be important for any prospective vehicle owner. Having a data set of this size allowed us to split it into 3 parts equalling to 200K-500K entries after filtering/processing.

**Issues with the data set:**
* There were so many columns including aspects about the vehicles, with some pertaining to only one body class, that many entries contained Null/NaN values.
* After filtering aspects of the dataset, it was common to find outliers where someone entered incorrect information into a field. E.g. A phone number was used as mileage for a few hundred Sedans. With outrageous ask prices of $200K for cars worth only $12K being recorded as well, which was almost certainly an error.


# Method
 After deciding to split up the vehicles per person per body class we used a IPYNB file to separate the files, sort based on criteria and combine to a dirty dataset pertaining to only Body Class we wanted to analyze (Trucks, SUVs, and Sedans).

Once the datasets were made, each set was cleaned of outliers and columns that would not pertain to the information we wanted to compare.

The clean data was then graphed to display correlations between aspects we considered most import -Cost & Mileage- the two most asked about details of a vehicle when a person looks to acquire one. Final data results were then calculated and included in the PowerPoint for explanatory purposes.

# Analysis
**Sedans** 

 The Sedans held the most entries, but the data was almost too generic and to avoid making just generic assumptions based on the Correlation outputs of the analysis in trends we used the Sedan information as an opening into the concept of vehicle presence in the marketplace.
- Since Sedans are the simplest vehicle in our data set they have the lowest cost and lowest utility meaning that Sedans do not tend to hold value as well as Trucks, offering less to describe in a trend of value over time.

 **Trucks**

 This Data set was used to provide the core of individual break downs because they held a special quality of being either Diesel or Gas Powered, offering a new parameter to gauge value over time.

 **SUVs**

 This data offered a challenge in how it could be used. This became apparent after filtering entries and learning that the classification of SUV varies so widely between dealers and manufacturers. Because this data wound up being essentially half Sedan and half Truck, we decided that it would be omitted since we had over 300K entries just between the Sedan and Truck datasets.
- Having the SUV data prove less than useful was important in displaying just how essential detailed data recording is, and how using open datasets can reduce the quality of information available.


# Conclusion
Gathering the data was the initial challenge until it came to filtering out what we needed. Having too much information can lead to false conclusion due to items being compared that would lead to an imbalance of Causation and Correlation; especially when the information contains as errors ( a consequence of the size of the data set).
Having a question, breaking down the items needed, then taking the analysis of the information step by step was the most helpful manner of proceeding.

Consistent communication was a challenge as well when it came to organizing aspects of life to meet outside of class and discuss what we wanted to do and where we would take the project after stepping past hurdles involving the data set as they arose. Overall, it was an exciting dip into the world of data modeling and analysis.





# --------------------------- Slides ---------------------------

![Title](Slide_Images/Slide1.png)

![Layout](Slide_Images/Slide2.png)

![Summary](Slide_Images/Slide3.png)

![Supply_Concept](Slide_Images/Slide4.png)

![Market_Saturation_&_PricevMileage](Slide_Images/Slide5.png)

![Sedan_Mileage](Slide_Images/Slide6.png)

![Ford_Regressions](Slide_Images/Slide7.png)

![Toyota_Regressions](Slide_Images/Slide8.png)

![GMC_Regressions](Slide_Images/Slide9.png)

![Ram_&_Chev_Regressions](Slide_Images/Slide10.png)

![Regressions_ Summary](Slide_Images/Slide11.png)

![Challenges](Slide_Images/Slide12.png)

![Questions](Slide_Images/Slide13.png)




Email: hendersonalec2212@gmail.com
LinkedIn: https://www.linkedin.com/in/alec-henderson-8011b521a/
