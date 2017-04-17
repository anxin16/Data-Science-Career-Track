## JSON examples and exercise
. get familiar with packages for dealing with JSON  
. study examples with JSON strings and files  
. work on exercise to be completed and submitted  
. reference: http://pandas.pydata.org/pandas-docs/stable/io.html#io-json-reader  
. data source: http://jsonstudio.com/resources/  
### JSON example, with string
. demonstrates creation of normalized dataframes (tables) from nested json string  
. source: http://pandas.pydata.org/pandas-docs/stable/io.html#normalization  
### JSON example, with file
. demonstrates reading in a json file as a string and as a table  
. uses small sample file containing data about projects funded by the World Bank  
. data source: http://jsonstudio.com/resources/
### JSON exercise
Using data in file 'data/world_bank_projects.json' and the techniques demonstrated above,
1. Find the 10 countries with most projects
2. Find the top 10 major project themes (using column 'mjtheme_namecode')
3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.
