Project done as part of the course DATA200 (Foundations of Data Analytics), Fall 2022, Tufts University.

Collaborators: Vanessa Venkataraman and Hanzhen Wang

Abstract of the project:
<br>
Gentrification is a widely studied topic to help policymakers design inclusive policies to minimize the adverse effects of gentrification, like displacement of poor communities and people of color. We hypothesize that the factors leading to the gentrification of a region can be broadly classified into three categories – people, place, and policy. We test this in two metropolitan areas – New York and Los Angeles. We use classification machine learning algorithms to predict the likelihood of each census tract in the two mentioned metropolitan regions getting gentrified in the period of ten years. Under the people category, we found the following predictors helpful – race, age demographics, and median family income. Under the place category, we found the following predictors to be beneficial – the proportion of people living in the same metro area where they are working, the proportion of people under the poverty level only for Los Angeles, and the proportion of nonfamily, rented, and vacant households only for New York. We found none of the policy variables to be statistically significant.

<br>

The dataset used: Neighborhood Change Database (NCDB), https://geolytics.com/products/normalized-data/neighborhood-change-database

<br>

Guide to navigate the RMD scripts:

* X_Data_Preprocessing - To clean and process the input data for the classification algorithm
* Y_Data_Preprocessing - To create Y labels for the classification algorithm
* Creating_Training_Data - To combine the X data and Y labels to create the final training dataset
* Model_Buliding_NY - Modeling process for the New York Metropolitan area
* Model_Buliding_LA - Modeling process for the Los Angeles Metropolitan area
<br>
Note:
(i) For more details on the project, refer to the [Presentation Deck](https://github.com/VishweshS/Gentrification-Study/blob/main/Presentation%20Deck.pptx) and [Report](https://github.com/VishweshS/Gentrification-Study/blob/main/Report.pdf)
(ii) All the RMD scripts mention the input data files required and the output data files generated, which are also uploaded.
