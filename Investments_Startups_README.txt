The following readme will describe the project, but I want to underline that the aim of this work is to show some of my skills and not to get an accurate result, clarified that point, we can now analyze the content.

The purpose of this analysis is to create a machine learning model that can predict the number of investments that a startup could get on the basis of some independent variables, which are: Country of the company, Year o foundation, and Industry.
I decide to use both Decision Tree Regressor and Random forest regressor for this analysis.

One of the complications that I faced working on this project is that 2 out of 3 variables were qualitative variables, while the model that I wanted to use only Quantitative variables. In order to fix this problem I used a OneHotEncoder to convert each unique qualitative category to a unique quantitative one.

Another feature of the model is that the number of "leaves" (in how many the levels split the data) that minimizes the MAE (Mean average error).