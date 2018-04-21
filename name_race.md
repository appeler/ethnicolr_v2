## Predicting Race and Ethnicity From Sequence of Characters in Names

To answer questions about racial inequality, we often need the ability to reliably infer the race of a person based on their name. The census bureau provides common last names and proportion of people belonging to different races who have the last name. But there is more information in the first names. To estimate the relationship between full names and race, we exploit the Florida voting registration data, and the Wikipedia data collected by Skiena and colleagues, to predict race and ethnicity using Long Short Term Memory Networks. Our out of sample precision and recall is .83 and .84 respectively. This compares to OOS recall of .78 and .79 for last name only models. We also provide a Python package to easily predict the race and ethnicity of names. We apply our method to the campaign finance data to estimate the share of donations made by people of various racial groups and investigate whether people are more likely to contribute to co-ethnics conditional on ideology.

If you picked a random individual with last name 'Smith' from the US in 2010 and asked us to guess this person's race (measured as crudely as by the census), the best guess would be based on what is available from the aggregated Census file. It is the Bayes Optimal Solution. So what good are last name only predictive models for? A few things---if you want to impute ethnicity at a more granular level, guess the race of people in different years (than when the census was conducted if some assumptions hold), guess the race of people in different countries (again if some assumptions hold), when names are slightly different (again with some assumptions), etc. The big benefit comes from when both the first name and last name is known.

### Data and Methods

We exploit the US census data, the Florida voting registration data, and the Wikipedia data collected by Skiena and colleagues, to predict race and ethnicity based on first and last name or just the last name. The granularity at which we predict the race depends on the dataset. For instance, Skiena et al.' Wikipedia data is at the ethnic group level, while the census data we use in the model (the raw data has additional categories of Native Americans and Bi-racial) merely categorizes between Non-Hispanic Whites, Non-Hispanic Blacks, Asians, and Hispanics.

### Validation

### Application

### Discussion

