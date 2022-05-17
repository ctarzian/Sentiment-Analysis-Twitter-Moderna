# Utilizing Sentiment Analysis on Twitter to Predict Moderna’s Future Stock Movements

Moderna helped play a major role in curbing Covid-19 in America and around the world. What insights could be drawn from Twitter reaction either before or after major stock price movements and what could be gleaned from that dataset using sentiment analysis?

First, imported Moderna's stock price history from Yahoo. Created a 'Percent Change' column to identify the days with the ten biggest spikes and dips over the course of Moderna's stock history. Used those 20 days as a launching point for Twitter reaction.

Built a web scraper that would scrape tweets both before and after each of the 20 days. Utilized Selenium and Snscrape to compile our dataset of tweets, and saved it into four dataframes: before_pos, after_pos, before_neg and after_neg.

Used both Vader and Textblob sentiment analysis tools to glean insights from the Twitter datset.

Ultimately, the days preceding a spike in Moderna's stock price saw the most positive Twitter sentiment and the days following a dip in the stock price saw the most negative Twitter sentiment.
