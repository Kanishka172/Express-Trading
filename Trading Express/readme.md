#Finlearn-Node
##Explain the Functioning

Server-Side technologies->

1)NodeJs-For Server Management basically handing user request and file management. Processing.
Why use??
beacuse i had knowledge about js 

2)Express Js used to efficiently route the user request

3)MySql for database meaning all the user login details as well as details of buy and sell stocks are stored here

4)Xamp is a platform that hosts sql database

Basically it is a financial learning paltform build for people who want to pratice trading. It provides virtual money from which we can trade stocks in real time. It displays various graphs and statistics about the stock of a company in real time. All these data are fetched from APIs.
The platform also has a news section in which it displays latest news related to varios companies stocks

The user can search data about any company stock and the platform can display the data in a very systematic and graphically manner

1)Trading view for all the graphs
2)Alphadvantage for searching stocks and stocks data

search bar hai
I have also added the feature using API which recommends the user whether to buy or sell a particular stock at that point of time 

It also has a holding page which has all the details the profit and loss made by the user while buying or selling stocks

Problems-

multiple api used so to increate them so that they could function in coordationation was a difficult task
trading view api american company ki hai so unka default nasdaq but alphaadvantage indian api hai so uska default bse hai
trading view ko trading comapny code chahiye hota hai warna woh zomato ko nasdaq pe search karega toh usko woh milega 

alphadvantage only returns the stock code(Appl for apple) but does not nasdaq 