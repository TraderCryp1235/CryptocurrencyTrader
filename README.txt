Thank you for downloading CryptocurrencyTrader.

This tool can only use MEXC API.

Follow these instructions to use CryptocurrencyTrader.

Open the file at the following path in a text editor
\CryptocurrencyTrader\_internal\config.py

Please change your_api_key and your_secret_key below to your key.

API_KEY = "your_api_key"
SECRET_KEY = "your_secret_key"

If you would like to buy or sell virtual currency for a specified amount, please enter the desired amount in Buy Price and Sell Price.

Please be sure to enter the trading currency.
For example, if you want to buy or sell BTC with USDT, enter BTC in the left text box and USDT in the right text box.

If Interval (seconds) is not entered, 30 seconds will be set by default.
Also, it cannot be set to less than 30 seconds.

If you check Specify trade count and enter the number of trades, the trade will be performed for the number of times you entered.
If you don't check Don't use all your balance, all your balance will be used automatically.
If you check Don’t use all your balance and enter the amount, the transaction will be made with the entered amount.
Trade direction's Buy to Sell process involves purchasing virtual currency when the price is low and selling it when the price is high.
Trade direction's Sell to Buy process involves selling the virtual currency you already own when it is high and buying it when it is low.


If you want to change the background image, please save the image file in the following directory.
\CryptocurrencyTrader\_internal

And change the information in the following file
\CryptocurrencyTrader\_internal\config.py

background_image = 'background_image.png'

The creator is not responsible for any disadvantages caused by this tool.