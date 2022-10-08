# data_visualization OF FOOD exported data
a task project <br />
 The dataset used here is a Market Food export dataset. This was in the form of xlsx format.<br />
# Prerequisites
 jupyter notebook 
# Installations
 import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import datetime as dt
import openpyxl
# Procedure followed 
2. I have uploaded the dataset successfully in my notebook <br />
3. After that I 've checked if Data has null values using .isnull() . Since it has null values so, i've used .dropna() .<br />
4. Now the columns in dataset are - DATE , DESCRIPTION , UNIT & PLACE.<br />
5. The DATE column has datatype ('<M8[ns')  . So, I can easily extract the day,month and year details individually.<br />
6. By applying countplot on 'month' column of data , I  got that only 3 month data is given .<br />
7. By applying countplot on 'DESCRIPTION' , I got that 10 types of food items have been demanded out of which BEEF is highly demanded and Kadumanga is least demanded.<br />
8. BY applying scatterplot on column -(DESCRIPTION and day ) we got to know that NO relaton exists among these .<br />
9. By applying Box plot on (UNIT ,month)together and (DESCRIPTION ,month) together we get that , there are no outliers.and kadumanga was only ordered for start of month april. and dates were also last ordered in May .<br />
10. Now i thought of applying one-hot ecoding technique to see the patterns . but it didnt change anything because truth tables of dummies were ambiguous.<br />
so, the dataset was very small<br />
11. it had missing values<br />
12. each feature columns are least related with other columns .<br />
13. Data should have to be of large size and correlation should have to be present <br />
14. This data needs to be updated with more columns and rows which can impact the correation between them and hence giving useful insights <br />
15. new columns might be : unique id of member who orders ,2021 purchase data, 2020 purchese data or any other feature.<br />
