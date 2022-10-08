# data_visualization 
a task project \n
The dataset used here is a Market Food export dataset. This was in the form of xlsx format.//
I have uploaded the dataset successfully in my notebook
After that I 've checked if Data has null values using .isnull() . Since it has null values so, i've used .dropna() .
Now the columns in dataset are - DATE , DESCRIPTION , UNIT & PLACE.
The DATE column has datatype ('<M8[ns')  . So, I can easily extract the day,month and year details individually.
By applying countplot on 'month' column of data , I  got that only 3 month data is given .
By applying countplot on 'DESCRIPTION' , I got that 10 types of food items have been demanded out of which BEEF is highly demanded and Kadumanga is least demanded.
BY applying scatterplot on column -(DESCRIPTION and day ) we got to know that NO relaton exists among these .
By applying Box plot on (UNIT ,month)together and (DESCRIPTION ,month) together we get that , there are no outliers.and kadumanga was only ordered for start of month april. and dates were also last ordered in May .
Now i thought of applying one-hot ecoding technique to see the patterns . but it didnt change anything because truth tables of dummies were ambiguous.
so, the dataset was very small
it had missing values
each feature columns are least related with other columns .
Data should have to be of large size and correlation should have to be present 
This data needs to be updated with more columns and rows which can impact the correation between them and hence giving useful insights 
new columns might be : unique id of member who orders ,2021 purchase data, 2020 purchese data.
or any other feature.
