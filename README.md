Flatiron Data Science Program

Module 2 Project

October 9, 2020

---

# *King County Real Estate*

*An analysis of the King County, Washington housing market.*

![Seattle Skyline](./images/seattle_orange.png)

---

### Overview

My client is an emerging real estate brokerage firm in King County. They are looking to expand and maximize their potential commissions. They want to know where in the county they should attempt to scout clients to maximize gross house sale prices. I will also build a linear regression model to predict housing price to help accurately price the homes they represent.


### Data

A modified version of publicly available King County housing data was provided by Flatiron. The sales records range from 05/02/2014 to 05/27/2015. There were 21,597 records. Data preprocessing involved: correcting data types, checking for duplicates,
replacing null values as appropriate, cropped outliers, and dropping or engineering new columns.

Please see my [cleaning notebook](./notebooks/Data_Cleaning.ipynb) for methodology and cleaning process.

### Questions/EDA

#### 1) Where are the most largest and expensive homes?

Full analysis: [Question 1 Notebook](./notebooks/Question_1_Where?.ipynb)

The most expensive homes are on average on the east bank of Lake Washington in the Bellevue area. This area also contains the largest homes in the data set. Bellevue spans six zipcodes, 98004-98009.

![Price Chloropleth](./images/price_mean_map.png)


![Living Area Chloropleth](./images/sqft_liv_map.png)




#### 2) Does home age have an effect on price?

Full analysis: [Question 2 Notebook](./notebooks/Question_2_Age?.ipynb)

Individually, age of home does not seem to be a good predictor of home price. No correlation observed. When age is grouped by decade, some age ranges show statistically different *average* prices. Using tukey testing, in 44 cases (of 66 comparisons) we reject the null - that the decade price means are the same.

![Difference in mean price by decade](./images/mean_age.png)




#### 3) How do renovations effect home price?

Full analysis: [Question 3 Notebook](./notebooks/Question_3_Conditions?.ipynb)

Relationship between home age, condition, and grade were explored. Grade had the most notable correlation with price. Renovations were shown to on average, improve grade and thus increase price. Renovations completed more recently showed biggest potential for price increase. See notebook for condition and grade ranking scale (as established by King County).

![Age grade price](./images/age_grade.png)

![Reno on price](./images/reno.png)




#### Model

Model aims to predict the sale price based on known features.


Solve problem:
- What business problems will this solve?
- Build model to predict sale price based on input of selected features.


Define the predictors:
- What are at least three features that exibit a linear relationship with sale price?

Validate model performance:



---
### Conclusions

My client, an emerging real estate brokerage firm, may consider advertising their business in the Bellevue area in the hopes of scooping up clients in this area. Grade has the most significantt effect on price observed. Renovations are a good way to improve housing grade.

- - - - - - - -  TODO: model results


### Future Work

- Investigate the return on investment for flipping houses compared to standard sales.
- How to maximize features into grade score?
- Get data for appartments and condos in Seattle in addition to the stand houses in this data set.


### Thank you for viewing my project!

Please review the full analysis in my [Jupyter Notebooks](./notebooks) or view my presentation as [slides](./presentation.pdf) or [video]().

![TGIF](./images/tgif.jpg)

