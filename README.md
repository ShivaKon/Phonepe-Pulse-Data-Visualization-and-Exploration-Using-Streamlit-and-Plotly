**Phonepe Pulse Data Visualization**

**Introduction**
PhonePe has become one of the most popular digital payment platforms in India, with millions of users relying on it for their day-to-day transactions. The app is known for its simplicity, user-friendly interface, and fast and secure payment processing.
We create a web app to analyse the Phonepe transaction and users depending on various Years, Quarters, States, and Types of transaction and give a Geographical and Geo visualization output based on given requirements.

**Developer Guide :**
- Tools install for this project

1.virtual code.
2.Jupyter notebook.
3.Python 3.11.0 or higher.
4.MySQL
5.Git

- **Requirement Libraries to Install :**

pip install pandas

pip install numpy

pip install os

pip install json requests subprocess

pip install mysql.connector

pip install sqlalchemy

pip install pymysql

pip install streamlit

pip install plotly.express


Import these libraries in the terminal before the execution of the project 



**E T L Process:**


a) Extract data
Initially, we Clone the data from the Phonepe GitHub repository by using Python libraries. https://github.com/PhonePe/pulse.git

b) Process and Transform the data
Process the clone data by using Python algorithms and transform the processed data into DataFrame formate.

c) Load data
Finally, create a connection to the MySQL server and create a Database and stored the Transformed data in the MySQL server by using the given method.



**FrameWork Process :**

-Access MySQL DB
Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library

-Filter the data
Filter and process the collected data depending on the given requirements by using SQL queries

-Visualization
Finally, create a Dashboard by using Streamlit and applying selection and dropdown options on the Dashboard and show the output are Geo visualization, bar chart, and Dataframe Table


**Steps to use this UI and analysis :**


Step 1.
Select any one option fron All India or State wise or Top Ten categories

Step 2.
Select any one option fron Transaction or User.

Step 3.
Select any Year, Quarter and additional required option.

Step 4.
Finally, You get the Geo Visualization Analysis or Bar chart Analysis and Table format Analysis






