# AtliQ Technologies Revenue Data Analysis :

The purpose of the project was to unlock sales insights which were not visible before the sales team for decision support and automate them to reduce manual time spent in data gathering.

# Problem statement:
The case study was based on a computer hardware business company "AtliQ Technologies" which was facing challenges in dynamically changing market. Sales director decided to invest in data analysis project and he wanted to build Tableau dashboard that could then give him real time sales insights. 

# Project planning and data discovery aspect:

After the sales directory of atliQhardware had decided to invest in data analysis project he did a meeting with IT director, data analytics team to come up with a plan. They used the AIMS grid to define the purpose and success criteria of this project. Once AIMS grid was defined, next step was data discovery. In this step, data analyst team approached IT team (within the organization) who owns the software system that kept the track of sales records. These records were stored in MySQL database. Tableau was then plugged to this database to pull necessary information required for data analysis. We often need separate data warehouse or OLAP system to run our data analytics queries but in this project we directly used MySQL database.
This database had all the sales transactions,customers, products and markets information. We analyzed this database and then tied it up with Tableau. In the Tableau software we performed ETL (extract transform load). This process is also known as data munging or data wrangling. We also performed data cleaning operations like currency normalization, handling invalidvalues etc. to make it ready for our dashboard.

# Dashboard building:
I then finally build the tableau dashboard for our sales insights project and published the dashboard to tableau online.

![Screenshot (387)](https://github.com/Abhisheksudan96/AtliQ_TABLEAU/assets/138653890/57e4ba97-4a78-481e-a105-c92cbc7c470a)

![Screenshot (388)](https://github.com/Abhisheksudan96/AtliQ_TABLEAU/assets/138653890/66c5a0f7-8f7a-4ab2-8abe-d27dccafeeee)

# INSIGHTS ;

- Northern zone contributes in 68.8 % Revenue generation.

- "Electricalsara" store is the top most customer which alone generates 42 % gross revenue.

- Leader is the customer with highest profit margin i.e 7.54 %.

- Trendline is showing a decline in the third quadrant in terms of revenue.

- Delhi, Mumbai and Ahemdabad are contributing to 82 % of revenue and 65 % of  total quantity of sales.

- Bengaluru has a negative impact on gross profits ( -20.78 %) and sales are negligible.


# Business recommendation ;

Build a healthy relationship with states like delhi, mumbai, ahemdabad and customers like Electricalsara store , leader.

Focus on problems within Bengaluru , deploying a well focused field sales team  could be helpful in this case. 
