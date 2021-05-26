**Introduction**

We bought our primary home in November 2007 in San Jose. The next year the housing crisis spread cross US cities and many people’s homes went to foreclosure. Our home value also went down 30% and we felt buying home was our biggest mistake. But now when looking back, I feel we were lucky to buy at that time considering how expensive home is right now. Looking forward, we think we might plan to sell our current house during our retirement years and purchase a property in other states to avoid California high living expense. Also, many of my friends often ask my advice about buying houses. This is the reason to inspire me to investigate the US housing data to find the insight to help me and others to make the right decision.

**Libraries**

The following libraries were used: Pandas, Seaborn, matplotlib and numpy

**Data Source**

I found US housing prices(1996 to 2021) related information from [https://www.zillow.com/research/data/](https://www.zillow.com/research/data/)

**Data Exploration**

It’s straight forward to use Zillow housing data to find out answers for the first four questions below. I spent most of my time trying to figure out how to solve the fifth question. Solving question 5 enabled me using visualization to find out US housing trends and patterns.

1.  What are top 10 largest cities' housing prices from 1/31/1996 to 4/30/2021?
2.  Which city has the highest housing price for 4/30/2021?
3.  Which city has the lowest housing price for 4/30/2021?
4.  Which is the average US housing price for 4/30/2021?
5.  What is the average housing price for each US city from 1996 to 2021?

**Findings**

For my future house selling and buying, the cities I am interested are San Francisco, San Jose, New York, Austin, Dalas, Las Vegas and Seattle. Below are what insight I discovered using data manipulation with Python, Panda, matplotlib and Seaborn searching through Zillow housing dataset from 1/31/1996 to 4/30/2021.

New York housing prices experienced about 15% correction during 2008 housing crisis. It went up from 2014 to 2018 and became flat after that. The average price in 1996 is about $200000 and the average price is getting closer to $700000 currently

Austin housing market was flat during 2008 housing crisis but started to jump from 2012. It has a steep jump starting from 2019. The average price in 1996 is about $100000 and the average price is getting closer to $500000 currently

Dallas housing experienced about 15% correction during 2008 housing crisis. It started to move up from 2013; but the price increase was not as dramatically as Austin. The average price in 1996 is about $100000 and the average price is about $250000 currently

San Jose experienced about 30% price drop during 2008 housing crisis. It started to move up after 2012. The average price in 1996 is about $150000 and the average price is about $1200000 currently

San Francisco experienced 2008 price correction but was not as severe as San Jose. Its price started to move up after 2013. The average price in 1996 is about $200000 and the average price is about $1400000 currently

Seattle housing price went down about 30% during 2008. It started to go up from 2013. The average price in 1996 is about $150000 and the average price is about $850000 currently

Las Vegas housing price went to peak in 2007 at average price around $350000 and lost almost 70% during 2008 housing crisis. It went up steady after 2012. The average price in 1996 is about $150000 and the average price is about $320000 currently

**Summary**

Overall, I found the seaborn lineplot() visual display is very useful for me to observe price trends and patterns for US housing market cross all the cities. As I have a few target cities in mind for future house searching, I was able to quickly retrieve the data I desired and got a clear idea about each city I am interested. Of course, users can use my application to find out past and current price information for any US city they want to check to find insight information to make their decisions.
