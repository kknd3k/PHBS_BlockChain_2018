# PHBS_BlockChain_2018
ID：1701212941 Name: 陈思豪（Sihao Chen）

# Introduction
For a common currency, their is a central authority and the currency value is related to factors like the economic power of one country and domestic capital return. But bitcoin is a different thing. Van Wijk (2013) thinks that bitcoin is actually a string of code. It's worth intrinsically nothing. Can we still apply some classic economic model on bitcoin price formation? Or should we found new determinants or models to explain it?
<br>
<br>I collected some literatures focus on bitcoin price formation. Actually this is a tough problem. Bitcoin price is extremely volatile no matter you denote in which currency like US dollar or CNY. This huge fluctuation will produces noise which makes meaningful analysis difficult. Most of papers didn't provide a feasible model that can be used for prediction. It seems that bitcoin price is more efficient than I expect. Eventually, I still found some factors related to bitcoin price.

# Potential Determinants 
There are some factors mentioned by different literature. I did a brief summary:
<br>
## (1)The investors’ attractiveness (TTR)
As a proxy of investors’ attractiveness to Bitcoin, he use daily Bitcoin views from Google as it able to properly depict the speculative character of users (Kristoufek 2013). This indicator is determined via the frequency of the online Google search queries related to the new digital money generally and Bitcoin particularly. Arguably, Piskorec et al. (2014) highlight the effectiveness of this proxy to accurately describe the behavior of investors.
<br>
## (2)The exchange-trade ratio (ETR)
The trade and exchange transactions expand the utility of holding the currency, leading to an increase in Bitcoin price. The exchange-trade ratio is measured as a ratio between volumes on the currency exchange market and trade (Bouoiyour et al. 2015).
<br>
## (3)The monetary velocity (MBV)
By definition, the velocity of money is the frequency at which one unit of each currency is used to purchase tradable or non-tradable products for a given period. Because of the large daily fluctuations of Bitcoin, the velocity of the economy of this new currency has stayed relatively stable (Kristoufek 2014)

## (4)The estimated output volume (EOV)
It is similar to the total output volume with the addition of an algorithm which tries to remove change from the total value. This may reflect more accurately the true transaction volume. Basically, there is a negative relationship between the estimated
output volume and Bitcoin price. Accordingly, Kristoufek (2014) shows that an increase in the estimated output volume leads to a drop in Bitcoin price in the long-run.

## (5)The Hash rate (HASH)
The emergence of Bitcoin has provided new approaches concerning payments. Hence, some new words have emerged such as the hash rate. It represents an indicator of the processing power of the Bitcoin network. For security goal, the latter must make intensive mathematical operations, prompting an increase in the hash rate. This may affect widely Bitcoin purchasers and increases substantially the demand of this new currency and in turn their prices. Generally speaking, the hash
rate is associated positively to Bitcoin price (Kristoufek 2014).

## (6)The gold price (GP)
Bitcoin does not have an underlying value derived from consumption or production process such as gold. In that context, Ciaian et al. (2014) and Yermack (2014) provide evidence that there is any sign of Bitcoin being a safe haven.

## (7)The Shangai market index/Dow Jones index
The Shangai market is considered as the biggest player in Bitcoin economy and as a result may be perceived as a potential source of Bitcoin price volatility. Arguably, the announcement that Baidu (potential determinant of the Chinese online shopping) is accepting Bitcoin has affected considerably the price of the focal virtual currency. Recently, Bouoiyour et al. (2015), using an improved frequency domain approach-based on unconditional vs. conditional data analysis, find that Bitcoin is likely to be a speculative trap rather than business income, conditioning upon the performance of the Shangai market. Van Wijk(2013) also found that Dow Jones index is a significant factor to bitcoin/US dollar exchange rate.

## (8)Bitcoin supply and demand
There are different method to measure the bitcoin supply and demand. Instead of the number of bitcoin supply, Ciaian et al.(2016) use the value in dollar of bitcoin supply in their regression.

# Literatures
## 1.The Economics of BitCoin Price Formation(Ciaian et al. 2016)
This is a widely used paper following the main idea of Van Wijk (2013). It researched on bitcoin price formation by combining three types of bitcoin price determinants identified in the previous literature: market forces of supply and demand, investors' behavior and global financial development, and to account for their interactions.
<br>
### The methodology
B represents the total stock of BitCoins in circulation and EX is the exchange rate of BitCoin. The total BitCoin supply, MS, is given by:<space>**MS=EX*B**
<br>
<br>And the demand of bitcoin MD is given by:<space>**MD=P*Y/V**
<br>
<br>P is the general price level of goods and services.Y is the size of BitCoin economy, and V is the velocity of BitCoin circulation. The BitCoin’s velocity, V, measures the frequency at which one unit of BitCoin is used for purchase of goods and services, and it depends on the opportunity cost for holding it (inflation, opportunity interest rate).
<br>
<br>Under market equilibrim condition:<space>**MS=MD**
<br>
<br>So we have:<space>**EX= P*Y/(V*B)**
<br>
<br>This equation under logarithmic transformation is:
![equation 1](/images/图1.png)
<br>But this is no the final model since this paper will consider three types of factors, not only money supply and demand.
![equation 2](/images/图2.png)
 <br>Factor a captures BitCoin’s attractiveness for investors. And factor m captures macroeconomic and financial indicators.
<br>This model will be used in empirical part. The author choose VAR model.
<br>
### The conclusion
(1)This paper found that BitCoin supply and demand have an important impact on BitCoin price. 
<br>(2)We cannot reject the hypothesis that short-run investor speculations also affect BitCoin price.
<br>(3)The estimates do not support previous findings that macro-financial indicators are driving BitCoin price
<br>
 ## 2.What can be expected from the bitcoin(Van Wijk 2013)
 This is an early paper whose model is relatively simple. But it gave some ideas to later research. I also listed it here. The author tried to find the role of global financial development e.g. stock exchange indices, exchange rates, and oil price measures, in determining BitCoin price. 
 <br>
 ### The conclusion
 After properly processed data from 19th July 2010 until 13th June 2013, the author did an OLS based on value of bitcoin and some macro level dependent variables. After the regression, the value of the Bitcoin consists of several stock exchange indices, exchange rates, and oil prices measures. This paper found evidence that the Dow Jones index, the euro-dollar exchange rate, and oil price have a significant impact on the value of BitCoin in the long-run.
  
 ## 3.What Are the Main Drivers of the Bitcoin Price? Evidence from Wavelet Coherence Analysis(Kristoufek 2015)
 The paper focus on various possible sources of price movements, ranging from fundamental sources to speculative and technical sources. The sample period is from 2010 to April 2014. This paper used utilized wavelets methodology, which is rarely used in normal economic thesis. The author spent long pages to illustrate it. In my understanding, this method is used in signal analysis.If you have interest, you can see file folder called paper. I put all my reference paper here.
<br>
<br>The author said that the relationship between bitcoin price and a certain factor should not be permanent. Therefore, this paper provided several graphs to illustrate the relation in different time period, which also mean this paper didn’t provide a model that can help us to predict the bitcoin price.
![result 1](/images/图3.png)
<br>
<br>Here I put a graph as an example. The graph shows the squared wavelet coherence between the Bitcoin price and the supply. The hotter the color is, the higher the correlation. Statistically significant correlations are highlighted by a thick black curve around the significant regions. We can see that the bitcoin price is significantly related to bitcoin supply in long term (256 days). This relationship is robust in whole sample periods.

### The conclusion
(1)In the long term, Bitcoin supply, ratio between trade and exchange transaction volume (trade-exchange ratio), hash rate, difficulty, the times of Google/Wikipedia searches on key word “bitcoin” and Financial Stress Index is significantly correlated with bitcoin price. 
<br>(2)In the short term, the relationship in different time period change a lot.

## 4.Cryptocurrency value formation: An empirical study leading to a cost of production model for valuing bitcoin(Hayes 2017)
<br>There are lot of cryptocurrencies in the market. What is factor make the price of cryptocurrencies different. The first part of his paper did a cross-sectional analysis to define the causes of relative value formation among cryptocurrencies. 
<br>
<br>In the second part, The author created a model to estimate the cost of produce one coin. But I doubt that cost of productition model may contribute little if we want to predict the coin price because there are lots of speculators and noise in the market.
### The methodology
#### Part one
This is a OLS model. The author used cross-sectional data from 66 of the most widely used on September 18, 2014
![model 1](/images/图4.png)
<br>
<br>The result shows that:
<br>(1)The amount of mining (computational) power devoted to finding a ’coin’ is positively correlated to altcoin value
<br>(2)The rate of ’coins’ found per minute is negatively correlated to altcoin value.
<br>(3)The percentage of coins mined thus far compared to that which is left to be mined is positively correlated to altcoin value but not significant.




