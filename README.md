# cryptocurrency
## Purpose

A prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, we create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. It will need to be processed to fit the machine learning models. To group the cryptocurrencies, we decided on a clustering algorithm. Using data visualizations to share our findings with the board.

## Result

I started by cleaning up the data to only have cryptocurrencies that are actively trading, have a defined algorithm, and have a complete set of data. This left me with 532 different cryptocurrrencies. From there I created a three dimisional graph to show how the different cryptocurrencies are grouped together. Each point includes its name as well as the algorithm used to create the currency.

![newplot](https://user-images.githubusercontent.com/71739110/108197305-2a411800-7155-11eb-94b6-37691175d85f.png)

After that, I created a two dimisional graph to show the relationship between total coin supply and total coins mined to show how each currency compares to the rest. Each point includes its currency name.

![bokeh_plot](https://user-images.githubusercontent.com/71739110/108197214-07166880-7155-11eb-8575-200060e088af.png)

## Summary

From the three dimisional graph, You can see that there are four different groups. Two groups are clumped very closely together with most currencies falling into one of these two groups. One group has a few different currencies that are farther away from the others and then there is the last group that only have one currency. This shows that there are lot of currencies that perform similarly while there are a few that are outliers. These outliers could be over performers or under performers, but I would need to perform more analysis to figure that out. One thing that I can connect is by looking at the total coin supply vs total coins mined graph. The two main groups have most of there data points scattered between 0% and 20% of the largest currency based on volume. The group with a few currencies are are very close to 0% of the largest currency, while the group with just one currency is at 100% as it is the largest currency.
