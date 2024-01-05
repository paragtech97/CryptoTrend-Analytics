Project Report: Bitcoin and Cryptocurrencies Analysis

Executive Summary:
Since the launch of Bitcoin in 2008, the cryptocurrency market has witnessed significant growth, with hundreds of projects utilizing blockchain technology. The market, however, is highly volatile, and caution is advised due to potential risks such as scams, overvaluation, and technical issues.

This report focuses on analyzing cryptocurrency data from December 6, 2017, using a dataset obtained from the coinmarketcap API. The analysis includes filtering out cryptocurrencies without market capitalization, visualizing the market capitalization of the top 10 coins, exploring volatility through percentage changes in 24 hours and 7 days, and categorizing cryptocurrencies based on market capitalization.

Data Overview:
The initial dataset (coinmarketcap_06122017.csv) was downloaded on December 6, 2017, using the coinmarketcap API, which is no longer publicly available since 2020. The dataset contains information on various cryptocurrencies, including their IDs, market capitalization in USD, and percentage changes in 24 hours and 7 days.

Data Cleaning and Filtering:
The analysis begins with importing the data into a Pandas DataFrame, filtering out cryptocurrencies without a market capitalization, and focusing on relevant columns. The count reveals that some cryptocurrencies have missing market capitalization values, which are subsequently removed.

Market Capitalization Analysis:

Top 10 Cryptocurrencies:
The report visualizes the market capitalization of the top 10 cryptocurrencies using a bar plot. Bitcoin's dominance is evident, but the plot is enhanced by using a log10 scale for better readability. Different colors are assigned to groups of similar coins based on their characteristics.

Volatility Analysis:
The report explores the volatility of cryptocurrencies by analyzing the percentage changes in 24 hours and 7 days. The top 10 gainers and losers in market capitalization are visualized using bar plots, highlighting the extreme fluctuations in the market.

Categorization based on Market Capitalization:
The dataset is classified into three categories based on market capitalization: "biggish," "micro," and "nano." This classification provides insights into the risk and reward associated with different-sized cryptocurrencies.

Conclusion:
Cryptocurrencies present a dynamic and volatile market, where careful analysis is essential for informed decision-making. This report provides a snapshot of the cryptocurrency landscape in 2017, emphasizing the importance of risk assessment and due diligence for investors.
