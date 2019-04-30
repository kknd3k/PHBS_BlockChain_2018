# PHBS_BlockChain_2018
ID：1701212941 Name: 陈思豪（Sihao Chen）

# Introduction
For a common currency, their is a central authority and the currency value is related to factors like the economic power of one country and domestic capital return. But bitcoin is a different thing. Van Wijk (2013) thinks that bitcoin is actually a string of code. It's worth intrinsically nothing. Can we still apply some classic economic model on bitcoin price formation? Or should we found new determinants or models to explain it?
<br>
<br>I collected some literatures focus on bitcoin price formation. Actually this is a tough problem. Bitcoin price is extremely volatile no matter you denote in which currency like US dollar or CNY. This huge fluctuation will produces noise which makes meaningful analysis difficult. Most of papers didn't provide a feasible model that can be used for prediction. It seems that bitcoin price is more efficient than I expect. Eventually, I still found some factors related to bitcoin price.

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
<br>(2)e cannot reject the hypothesis that short-run investor speculations also affect BitCoin price.
<br>(3)he estimates do not support previous findings that macro-financial indicators are driving BitCoin price
<br>
 ## 2.What can be expected from the bitcoin(Van Wijk 2013)
 This is an early paper whose model is relatively simple. But it gave some ideas to later research. I also listed it here. The author tried to find the role of global financial development e.g. stock exchange indices, exchange rates, and oil price measures, in determining BitCoin price. 
 <br>
 ### The conclusion
 After properly processed data from 19th July 2010 until 13th June 2013, the author did an OLS based on value of bitcoin and some macro level dependent variables. After the regression, the value of the Bitcoin consists of several stock exchange indices, exchange rates, and oil prices measures. This paper found evidence that the Dow Jones index, the euro-dollar exchange rate, and oil price have a significant impact on the value of BitCoin in the long-run.
  
 ## 3.What Are the Main Drivers of the Bitcoin Price? Evidence from Wavelet Coherence Analysis(Kristoufek 2015)
 The paper focus on various possible sources of price movements, ranging from fundamental sources to speculative and technical sources. The sample period is from 2010 to April 2014. This paper used utilized wavelets methodology, which is rarely used in normal economic thesis. The author spent long pages to illustrate it. If you have interest, you can see file folder called paper. I put all my reference paper here.
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




