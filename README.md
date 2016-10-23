# Exploring the State of the Internet in Various Economies

The goal of this project is to see how the connectivity relates to the economy 
of a particular nation. And how an economy grows because of better and increased connectivity. We want to argue that in this day and age, economies, and people flourish, in part, as a result of better access to the world wide web, which can facilitate a more efficient exchange, not just of ideas, but of commerce as well.

Economic data are fished from the [WORLD BANK](http://databank.worldbank.org/data/reports.aspx?Code=NY.GDP.PCAP.CD&id=af3ce82b&report_name=Popular_indicators&populartype=series&ispopular=y). Internet data is from [Akamai](https://www.akamai.com/us/en/our-thinking/state-of-the-internet-report/)

![Image](https://github.com/gmsardane/State-of-the-Internet/blob/master/GDP_versus_Depth.png)
In this analysis, we link the per capita GDP to the internet penetration percentage for a given country.
Here, we see that wealthier countries have larger portions of the population that are connected via the Internet. Obviously, this is because richer economies can afford technology infrastructure, as opposed to poorer ones.

![Image](https://github.com/gmsardane/Exploring-the-state-of-the-Internet-in-Various-Economies/blob/master/2016_Avg_Internet_Speeds.png)
We can also see a color map of internet speeds per nation. On average, connection speeds are not spectacular, anywhere in the world. Scandinavian countries top the list. The United States, on average, is typical 10$^{ish}$ Mbps. Whilst, a large portion of the WORLD is towards the red end. Africa is largely dark.

In the future, we hope to see what how the economy evolves with technology. How does the "happiness" of people connect with technology?
What about crime and corruption? How is the internet relevant to improving health? As the exploration continues, perhaps, more questions 
may arise.

## Tools:
This is an iPython notebook and requires:
 
 + Pandas and Numpy
 + Matplotlib

Plotly can be installed via a pip install. But, this also requires an account and a key from the [Plotly](https://plot.ly/python/choropleth-maps/) API to create the maps.


