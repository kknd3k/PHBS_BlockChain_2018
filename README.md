# PHBS_BlockChain_2018
ID：1701212941 Name: 陈思豪（Sihao Chen）

# 1.Introduction
For each fiat currency, there is a central authority behind it. The currency value is related to factors like the economic power of one country and domestic capital return. But bitcoin is a different thing. Van Wijk (2013) thinks that bitcoin is actually a string of code. It's worth intrinsically nothing. Can we still apply some classic economic model on bitcoin price formation? Or should we found new determinants or models to explain it?

<br>I collected some literatures focus on bitcoin price formation. Actually this is a tough problem. Bitcoin price is extremely volatile no matter you denote in which currency. This huge fluctuation will produces noise which makes meaningful analysis difficult. Most of papers didn't provide a feasible model that can be used for prediction. Eventually, I still found some factors related to bitcoin price.

# 2.Potential Determinants 
There are many factors mentioned by literatures. I did a brief summary of factors widely used. They can be fundamental factors or technical factors.
<br>
## (1)The investors’ attractiveness
Kristoufek(2013) use times of Google search on key word 'Bitcoin' to denote attractiveness. In Kristoufek(2015),he also added wikipedia search of Bitcoin in to consideration. Bouoiyour&Selmi(2015) found that TTR has a positive impact on bitcoin price.
<br>
## (2)The exchange-trade ratio
When we try to measure the value of one currency, if trade and exchange on this currency is frequant, we can say this currency is valuable. This idea can apply on Bitcoin. The exchange-trade ratio is measured as a ratio between volumes on the currency exchange market and trade (Kristoufek 2015).
<br>
## (3)The monetary velocity
By definition, the money velocity can be considered as in a certain time space, how many times one unit of bitcoin is used to purchase products.(Bouoiyour&Selmi 2015)

## (4)The Hash rate
Hash rate is an indicator for power of  calculation in the Bitcoin network. Kristoufek(2015) the hash rate is associated positively to Bitcoin price. Hayes(2017) found that this positive relation is still hold even in cross-section level.  

## (6)The gold price
Compared with goods like gold, Bitcoin does not have an intrinsic value（Van Wijk, 2013). Kristoufek(2015) mentioned it in his paper. But from the graph, the correlation is not stationary in different time points.

## (7)Dow Jones index
Van Wijk(2013) found that Dow Jones index is a significant factor to bitcoin/US dollar exchange rate.

## (8)Bitcoin supply and demand
There are different method to measure the bitcoin supply and demand. Instead of the number of bitcoin supply, Ciaian et al.(2016) use the value in dollar of bitcoin supply in their regression.

# 3.Literatures
## 3.1 The Economics of BitCoin Price Formation(Ciaian et al. 2016)
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
<br>(3)The estimates do not support Van Wijk (2013) that macro-financial indicators are driving BitCoin price. My understanding is probabily the model in Van Wijk (2013) didn't set properly.
<br>
 ## 3.2 What can be expected from the bitcoin(Van Wijk 2013)
 This is an early paper whose model is relatively simple. But it gave some ideas to later research. I also listed it here. The author tried to find the role of global financial development e.g. stock exchange indices, exchange rates, and oil price measures, in determining BitCoin price. 
 <br>
 ### The conclusion
 After properly processed data from 19th July 2010 until 13th June 2013, the author did an OLS based on value of bitcoin and some macro level dependent variables. The dependent variables include several stock exchange indices, exchange rates, and oil prices measures. This paper found evidence that the Dow Jones index, the euro-dollar exchange rate, and oil price have a significant impact on the value of BitCoin in the long-run.
  
 ## 3.3 What Are the Main Drivers of the Bitcoin Price? Evidence from Wavelet Coherence Analysis(Kristoufek 2015)
 The paper focus on various possible sources of price movements, ranging from fundamental sources to speculative and technical sources. The sample period is from 2010 to April 2014. This paper used utilized wavelets methodology, which is rarely used in normal economic thesis. The author spent long pages to illustrate it. In my understanding, this method is used in signal analysis.If you have interest, you can see file folder called paper. I put all my reference paper here.
<br>
<br>The author said that the relationship between bitcoin price and a certain factor should not be permanent. Therefore, this paper provided several graphs to illustrate the relation in different time period, which also mean this paper didn’t provide a model that can help us to predict the bitcoin price.
![result 1](/images/图3.png)
<br>
<br>Here I put a graph as an example. The graph shows the squared wavelet coherence between the Bitcoin price and the supply. The hotter the color is, the higher the correlation. Statistically significant correlations are highlighted by a thick black curve around the significant regions. We can see that the bitcoin price is significantly related to bitcoin supply in long term (256 days). This relationship is robust in whole sample periods.

### The conclusion
(1)In the long term, Bitcoin supply, ratio between trade and exchange transaction volume (trade-exchange ratio), hash rate, difficulty, the times of Google/Wikipedia searches on key word “bitcoin” and Financial Stress Index is significantly correlated with bitcoin price. 
<br>(2)In the short term, the relationship in different time period change a lot.

## 3.4 Cryptocurrency value formation: An empirical study leading to a cost of production model for valuing bitcoin(Hayes 2017)
<br>There are lot of cryptocurrencies in the market. What is factor make the price of cryptocurrencies different. The first part of his paper did a cross-sectional analysis to define the causes of relative value formation among cryptocurrencies. 
<br>
<br>In the second part, The author created a model to estimate the cost of produce for one coin. But This cost of productition model may contribute little if we want to predict the coin price because there are lots of speculators and noise in the market.
### The methodology
This is a OLS model. The author used cross-sectional data from 66 of the most widely used on September 18, 2014
![model 1](/images/图4.png)
<br>
<br>The result shows that:
<br>(1)The amount of mining (computational) power devoted to finding a ’coin’ is positively correlated to altcoin value
<br>(2)The rate of ’coins’ found per minute is negatively correlated to altcoin value.
<br>(3)The percentage of coins mined thus far compared to that which is left to be mined is positively correlated to altcoin value but not significant.

## 3.5 What does bitcoin looks like(Bouoiyour & Selmi,2015)
This is a comprehensive paper. It not only used factors mentioned in former literature, but also found some new factors. Besides, the author considered the closing of silkroad, which is taken as a dummy variable in estimation.

### The methodology
The dependent variables include investors' attractiveness, exchange-trade volume, monetary velocity, estimated output volume,hash rate, gold price and Shangai market index. The author used an ARDL Bounds Testing method with daily data from December 2010 to June 2014.
![Q5 1](/images/图5.png)

<br>LBPI is the log of bitcoin price. LTTR is the log of investors’ attractiveness. LETR is the log of exchange-trade ratio, LMBV is the log of monetary velocity, LEOV is the log of estimated output volume. LHASH is the log of hash rate. LGP is the log of gold price. LSI is the log of Shangai market index (SI). DV is dummy variable denote the closing of silkroad by FBI.

<br>Since we need the variables become stationary, some variables will take first order difference. The variables begin with ‘D’ means it took first order difference.
![Q5 2](/images/图6.png)

### The Conclusion
#### (A)Short term
<br>(1)the investors’ attractiveness plays a significant role in explaining Bitcoin price formation. 
The exchange-trade ratio affects positively and significantly the price of Bitcoin. 

<br>(2)Shangai market index contributes positively and significantly to BPI

<br>(3)Bitcoin velocity, estimated output volume and gold price have no significant impact on Bitcoin price

#### (B)Long term
The TTR, the EOV and the SI which play the major role in the short term, have little effect on BPI in the long-run.

# Reference
Balcilar, M., Bouri, E., Gupta, R., & Roubaud, D. (2017). Can volume predict Bitcoin returns and volatility? A quantiles-based approach. Economic Modelling, 64, 74-81.
<br>Bouoiyour, J., Selmi, R., & Tiwari, A. K. (2015). Is Bitcoin business income or speculative foolery? New ideas through an improved frequency domain analysis. Annals of Financial Economics, 10(01), 1550002.
<br>Bouoiyour, J., & Selmi, R. (2015). What does Bitcoin look like?. Annals of Economics & Finance, 16(2).

<br>Bouoiyour, J., Selmi, R., Tiwari, A. K., & Olayeni, O. R. (2016). What drives Bitcoin price. Economics Bulletin, 36(2), 843-850.

<br>Ciaian, P., Rajcaniova, M., & Kancs, D. A. (2016). The economics of BitCoin price formation. Applied Economics, 48(19), 1799-1815.

<br>Hayes, A. S. (2017). Cryptocurrency value formation: An empirical study leading to a cost of production model for valuing bitcoin. Telematics and Informatics, 34(7), 1308-1321.

<br>Kristoufek, L. (2013). BitCoin meets Google Trends and Wikipedia: Quantifying the relationship between phenomena of the Internet era. Scientific reports, 3, 3415.

<br>Kristoufek, L. (2015). What are the main drivers of the Bitcoin price? Evidence from wavelet coherence analysis. PloS one, 10(4), e0123923.

<br>Piskorec, M., Antulov-Fantulin, N., Novak, P. K., Mozetic, I., Grcar, M., Vodenska, I., & Smuc, T. (2014). Cohesiveness in financial news and its relation to market volatility. Scientific reports, 4, 5038.

<br>van Wijk, D. (2013). What can be expected from the BitCoin. Erasmus Universiteit Rotterdam.


