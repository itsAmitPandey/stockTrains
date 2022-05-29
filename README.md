# StockTrains
The Purpose of “StockTrains- Online Stock Market Training” is to train the new stock market investors on this online platform. It is often seen that people lose their money when they start investing in stock market. StockTrains provides real time data of NYSE where you can trade with virtual money.

# To run this Asp.net project on your machine, follow the steps:

1. Use visual studio version 2012 or higher.

2. Upload database backup file(DB_A62DBB_stockdb_7_18_2020.bak) to your database and connect.
-> (Use *Mywindowshosting.com --> mssql version 2017 or higher)
-> (Get credentials for DB connection from MWH* and update the same in project)

3. Get apikey from financialmodellingrep and update this variable --> Session["apikey"]
(Update session variable Session["apikey"] with new key)

4. Add newtonsoft json dll file to the project.
-> (To work on json object obtained from API)

5. For email-notification, turn 2-step-authentication on and get the security code for sending emails from gmail.
