Currency Converter Documentation
Introduction
The Currency Converter is a Java program that allows users to convert currencies using real-time exchange rates. It utilizes the ExchangeRateHost API to retrieve the latest exchange rates between various currencies.

Features
Convert Currency: Convert an amount from one currency to another based on the latest exchange rates.

Add to Favorite Currency List: Add a currency to your favorite list for quick access.

View Favorite Currency List: Display the list of currencies that have been added to the favorites.

Update Favorite Currency Rate: Update, replace, or remove a currency from the favorites list.

Quit: Exit the Currency Converter program.

Usage
Access Key: The program requires an access key from ExchangeRateHost to fetch the latest exchange rates. The default access key in the provided code is 2aa10c95325c0e72f3c8f40c380fa6c8. Make sure to replace it with your own key for production use.

Main Menu:

Choose from options 1 to 5 to perform different actions.
Convert Currency:

Enter the amount to convert.
Input the source currency code.
Specify the target currency code.
The program will display the converted amount.
Add to Favorite Currency List:

Enter the currency code to add to the favorites.
The program will add the currency to the favorites with its current exchange rate.
View Favorite Currency List:

Displays the list of currencies in the favorites along with their exchange rates.
Update Favorite Currency Rate:

View the current favorites list.
Choose to delete or replace a currency.
If replacing, enter the new currency code.
The program will update the favorites accordingly.
Quit:

Choose option 5 to exit the program.
Dependencies
The program utilizes the following libraries:

OkHttp: Used for making HTTP requests to the ExchangeRateHost API.
JSON-java: Used for parsing JSON responses.
Installation
Clone the repository: git clone https://github.com/yourusername/yourrepository.git
Open the project in your preferred Java development environment (IDE).
Replace the ACCESS_KEY in the CurrencyConverter class with your ExchangeRateHost API key.
Run the program.
Troubleshooting
If you encounter issues with the ExchangeRateHost API key or network connectivity, check your internet connection and ensure the API key is valid.
Disclaimer
This Currency Converter is provided as-is without any warranty. Use it responsibly and ensure compliance with ExchangeRateHost's terms of use.

Feel free to modify and enhance the documentation based on your specific project requirements and additional features.
