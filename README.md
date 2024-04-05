# Demo-Repository
To learn different techniques to encode the categorical features to numeric quantities
# Introduction
The aim of this is to explore various techniques for converting categorical features into numeric values. To keep things uncomplicated, we'll apply these encoding methods to just one column. Nevertheless, the same methodology can be extended to all columns if needed.
# Replacing Values
We can begin with a straightforward approach by substituting the categories with specific numbers. This can be done using the replace() function within the pandas library. The concept here is that you're free to select any numerical values that align with the business requirements for each category.
# Label Encoding
Another method involves using "label encoding" to encode categorical values. With this technique, each value in a column is converted into a numerical label. These numerical labels typically range from 0 to n_categories-1, where n_categories represents the total number of unique categories in the column.
# One-Hot encoding
This Python code snippet utilizes One-Hot encoding to convert categorical "fuel-type" data into binary columns. Dummy variables are created, merged with the original DataFrame, and displayed without the original column.
# Author
https://github.com/DeepKotadiya144
# Licence
open source
#Acknowledgement
This file is taken from the one of the lab that was given to us from the professor.
Template for README.md obtained from PurpleBooth
