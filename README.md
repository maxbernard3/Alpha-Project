# Alpha-Project : Implement a Cryptocurrency price tracker and arbitrage application

Your objective is to implement in C# .Net a cryptocurrencies price tracker and arbitrage application. This application will allow the user to add one or multiple cryptos to be followed and specify a datasource (for example : coinmarketcap) and then store the price on a regular basis and pop up notification when arbitrage (or other strategies) are identified.

The application has a graphical interface (web, desktop (WPF or Winform)) that allows to see the cryptocurrencies timeseries (price within a period of time).

The application has to detect arbitrage opportunities, ie different prices of the same crypto pair (ex BTC/USD) on diffrent markets (exchanges).

If this objective is met, it is possible to add a machine learning capability that detects investment opportunities based on historic data.

# Development Rules :

The project has to be implemented in C# .Net following TDD rules. 

Both tests and concrete implementation will be taken into account for the final notes. Methods and Classes have to follow best practice rules and be easy to understand and meaningful.

The framework used for the graphical interface is free. You can use WPF, Winform or web interface or any graphical interface technology within C#.net Framework.

The project has to be in .Net Core 5.

# Project follow up :

Every team has to create a specific branch under this repository named alpha-project-gn where n is the group number (alpha-project-g1, alpha-project-g2 etc).
Commits have to be done on a regular base and be done by all group participants.
