This project also includes the support of graphical user interface where the user has
the ability to create a new flexible portfolio, the ability to buy/sell stocks by specifying the
number of shares , and date (with or without commission fees), the ability to query the cost basis
and value of a flexible portfolio at a certain date, the ability to save and retrieve flexible
portfolios from files, the ability to invest a specific amount in an existing flexible portfolio 
on a specific date by specifying the weights of how that money should be invested in each stock
inside that portfolio, and the ability to create a portfolio using dollar-cost averaging as 
specified above, and query cost basis and value of such a portfolio at a specific date.

List of Features

The features of the project are:
1. Creation of flexible or inflexible portfolios with one or more stocks
2. Displays list of all the portfolios that were created with their composition.
3. Displays the composition of a specified portfolio.
4. Displays the total value of the portfolios on a specified date.
5. It can buy or sell stocks in an existing flexible portfolio.
6. It can calculate and display the cost basis (i.e. the total amount of money invested in a portfolio) by a specific date.
7. It can display the performance analysis of a portfolio on a certain date in graph format.
8. It can Invest a fixed amount into an existing portfolio containing multiple stocks, using a specified weight for each stock in the portfolio.
9. It can create a new flexible portfolio and perform Dollar cost averaging.
10. It persists all the portfolioImpl data that was entered in the form of .Json format files and will be used for the data retrieval for user functions.
11. The above features are supported in text based interface.
12. In addition to text based interface, it can also support graphical user interface where the following features are added
    Create flexible portfolio, buying/selling stocks, calculate cost basis, save and retrieve portfolios, invest a fixed amount into an using a specified weight, and  perform dollar cost averaging.

The program can be run in Stocks.jar file under res folder using the command `java -jar Stocks.jar`.
The program by default is set for graphical user interface. So for the user to run the text file
interface,program can be run in Stocks.jar file under res folder using the command 
`java -jar Stocks.jar text`.  
After running the program, you'll be able to find the menu option.
In the text based interface, after running, this would be the menu option
