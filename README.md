# The6ixRoboAdvisor

A robo-advising portfolio generator that filters and selects 12 stocks, one "hero" stock and 11 others that are the most closely correlated with it. The "hero" stocks are based on a most volatile stock (calculated by maximum standard deviation, maximum beta value, and minimum beta value).

To do this, we will be extracting data of all the stocks then calculating for standard deviation, market beta, and correlation. For each "hero" stock, we will generate an associating portfolio and then selecting the best one based on the results of widespread technical analysis, where each potential portfolio is run through multiple simulations with relevant past market data. The roboadvisor will then create a csv file of the desired stocks for the user.

Dependencies: Python, Pandas, NumPy, NumPy_financial, Matplotlib, yfinance
