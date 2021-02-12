# Trader

### I want a tool that allows me to select buy and sell points in a instruments(stocks, futures, forex, crypto) chart and then the tool determines the best indicators to product buy and sell signals at those points. I then want to optimize these strategies over varies time periods.
- Using UI, displays a chart for the instrument for a selected time period, the user selects their choosen buy and sell points and tolerance that buy/sell signals can occur before or after the selected bars
- Using data analysis and a library of available strategies, the backend searches for any indicators that meet the requested criteria and displays these back to the user with a graphical representation of the bars where the indicators were triggered
- Using optimization algorithums, the backend determines which indicator would produce the most accurate results and then attempts to optimize the indicator by adjusting parameters like lookback period or which type of price is used for analysis








# Maintenance / Load Balancing

### We must analyze and control the intensiveness of user's requested analysis and optimizations to ensure a user doesn't tie up system resources with a complicated analysis request
- Find a computational load estimatation tool and force the user to spend 'tokens' for the amount of systems resources a request will use to prevent overuse
