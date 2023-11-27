# **Technical Indicators & Strategies**
## **Momentum Based Indicators**
*Momentum Indicators are a type of technical indicator that measure the capacity of the price trend(slope of the line in layman's word) to sustain itself over a period of time. Momentum here refers to the inertia of the price trend to either continue rising or falling for a particular length of time, taking into account both price and volume information. There are 3 types of momentum indicators:-*<br/>
&emsp; * **Closing price compared to Previous Close**<br/>
&emsp; * **Closing price compared to Range**<br/>
*which I will describe sequentially*.<br/>
### **Closing Price compared to Previous Close**
*Using such indicators, traders can identify momentum trading signals. They sought to see if the market was overbought or oversold at close and if it could change directions. Eg:-* <br/>
#### **RSI(Relative Strength Index)**
*RSI measures the speed and magnitude of a security's recent price changes to evaluate overvalued or undervalued conditions in the price. The RSI is displayed via an oscillator (a line on the graph) on a scale of 0 to 100. It can also indicate securities that may be primed for a trend reversal or corrective pullback in price. It can signal when to buy and sell. Traditionally, an RSI reading of 70 or above indicates an overbought situation. A reading of 30 or below indicates an oversold condition. Lets look at the formula:-*<br/>
&emsp; **RSI=100+100/1+RS**<br/>
*RSI uses 14 periods as default to calculate RS.*<br/>
&emsp; **RS=avg up/avg down=(prev avg up*13 + current up)/(prev avg down*13 +current down)**<br/> 
### **Closing Price compared to Range**
*This type of momentum technical indicator compares the current price action to how the market has behaved over a past period of time. These indicators try to show whether the market is stronger or weaker. Eg:-* <br/>
#### **Stochastic Oscillator**
*A stochastic oscillator is a momentum indicator comparing a particular closing price of a security to a range of its prices over a certain period of time. Stochastic oscillators tend to vary around
some mean price level since they rely on an asset's price history. Similar to RSI, it is used to generate overbought and oversold trading signals, utilizing a 0–100 bounded range of values, with measurements above 80 indicating that an asset is overbought and measurements below 20 indicating that it is oversold.*
* Stochastic oscillator charting generally consists of two lines: one reflecting the actual value of the oscillator for each session, and one reflecting its three-day simple moving average. Because
price is thought to follow momentum, the intersection of these two lines is considered to be a signal that a reversal may be in the works, as it indicates a large shift in momentum from day to
day. The divergence between the stochastic oscillator and trending price action is also seen as an important reversal signal. For example, when a bearish trend reaches a new lower low, but the
oscillator prints a higher low, it may be an indicator that bears are exhausting their momentum and a bullish reversal is brewing. Formula:-<br/>
&emsp; **%K=(C-L14/H14-L14)100** <br/>
#### **Williams%R**
* The Williams %R is a leading momentum indicator(an indicator that takes into account the previous data points to predict future movements) whose values oscillate between 0 to -100. Traders use this indicator to spot potential entry and exit points for trades by constructing two levels of overbought and oversold.
* Williams%R is calculated as follows:<br/>
&emsp; **W%R 14 = [ H.HIGH - C.PRICE ] / [ L.LOW - C.PRICE ] * ( - 100 )** <br/>
&emsp; where,<br/>
&emsp; W%R 14 = 14-day Williams %R of the stock<br/>
&emsp; H.HIGH = 14-day Highest High of the stock<br/>
&emsp; L.LOW = 14-day Lowest Low of the stock<br/>
&emsp; C.PRICE = Closing price of the stock<br/>
*The underlying idea of this indicator is that the stock will keep reaching new highs when it is a strong uptrend and similarly, the stock will reach new lows when it follows a sturdy downtrend.*
*  Now, let’s analyze a chart of Williams%R to build a strong understanding of the indicator.<br/>
![867939_8c36c185642d4abea62d197687bf169d~mv2](https://github.com/adityaaa2511/Technical-Indicators/assets/137895529/a36c3256-4118-4919-8bce-44cec2f3dd89) <br/>
This chart can be utilized in 2 ways:-<br/>
* Use the chart as a tool to identify overbought and oversold states of the market. We can observe that there are two horizontal grey lines plotted above and below the market which is nothing but the overbought and oversold levels plotted at a threshold of -20 and -80 respectively. You can consider that the market is in the state of overbought if the Williams %R has a reading above the upper line or the overbought line. Similarly, you can assume that the market is in the state of oversold if the Williams %R has a reading below the lower line or the oversold line.<br/>
* Use Williams %R to identify false momentum in the market. During a sturdy uptrend, the readings of Williams %R tend to reach above -20 frequently. If the indicator falls and struggles to reach above -20 before the next fall, indicates that the market’s momentum is not authentic and is possible to follow a tremendous downtrend. Likewise, during a healthy downtrend, the readings of Williams %R are bound to go below -80 frequently. If the indicator rises and fails to reach -80 before the next rise, reveals that the market is going to follow a positive trend.
## **Trend Following Indicators**
*Trend-following strategies are strategies where you simply ride the trend, i.e. buy when the price is going up and sell when the price starts going down (both for a prolonged time period). With
trend-following strategies, one does not aim to forecast or predict, but one simply needs to keep an eye on the market for any emerging trend. Trends emerge as a result of human emotion and the desire to follow the crowd since a group of people can base their trading decision on an emotion triggered by an event. And, the others follow! Types of trends:-*
* **Uptrend:-** An uptrend implies that the stock price is rising in value. In case of an uptrend, the traders aim to take advantage by entering the long position in order to sell it later at a high
price. For instance, if the price of a stock increases by $40 and reduces by $20, and then again rises by $25 to reach 45, the stock price is in an upward trend since it shows higher highs (the
increase in price is taking the price line towards upward direction more often) and higher lows (the occasional decrease in price is not taking the price line towards downward direction) in the
price.
* **Downtrend:-** In case of a downtrend, the stock price faces a fall in value. During the downtrend, the trend traders enter a short position. And, when the stock price seems to be
falling below the lowest possible point (which makes the price too less), the trend trader prefers selling the stocks and exiting the market. For instance, if the stock price decreases by $70 and
then increases by $40 and then again falls by $50 to reach $80, a trader will see a formation in a downward trend. It shows through the lower highs (the occasional increase in price is not
taking the price line towards upward direction) and lower lows (the decrease in price is taking the price line towards downward direction more often) in the stock price during a downtrend.
### **Moving Average Convergence Divergence(MACD)**
* MACD stands for Moving Average Convergence Divergence. It is a trend-following lagging indicator that shows the relationship between two moving averages (MAs) of prices. The MACD indicator formula is calculated by subtracting the 26-day Exponential Moving Average (EMA) from the 12-day EMA. A nine-day EMA of the MACD is known as the **Signal Line**, which is plotted on top of the MACD, usually marking triggers for buy and sell signals. 
* When the price is making a lower low, but the MACD is making a higher low – we call it bullish divergence. If the MACD is making a lower high, but the price is making a higher high – we call it a bearish divergence. Divergence will almost always occur right after a sharp price movement higher or lower. Divergence is just a cue that the price might reverse, and it's usually confirmed by a trendline break.
* A simple MACD trading strategy is called the Signal Line Crossover, or MACD crossover trading strategy. A bullish crossover happens when the MACD line turns upwards and crosses beyond the signal line. A bearish crossover happens when the MACD turns downwards and crosses under the signal line. When this happens, we want to be sure both lines move as far apart from each other as they can.
This can signal that the momentum of the price will continue moving in the desired direction.
* **STRATEGY:-** We will be using a trading strategy(for implementation purposes) as follows:-<br/>
&emsp; **PREV.WR > -50 AND CUR.WR < -50 AND MACD.L > SIGNAL.L ==> BUY SIGNAL** <br/>
&emsp; **PREV.WR < -50 AND CUR.WR > -50 AND MACD.L < SIGNAL.L ==> SELL SIGNAL** <br/>
## **Volatility Based Indicators**
* The volatility of the price is the range in which the price can vary in an upward or downward trend. The faster prices change, the higher the volatility. The slower prices change, the lower the volatility. Higher volatility indicates greater price fluctuations and increased market uncertainty. It also typically signals if a market is overbought or oversold (meaning the price is unjustifiably high or unjustifiably low), which can point to a stalling or reversal of the trend. Examples of such indicators are **Average True Range (ATR), Bollinger Bands (BB)** <br/>
### Bollinger Bands(BB)
* Bollinger bands, which are composed of three lines, quantify price volatility through the width of its upper and lower standard deviation bands; standard deviation represents how far prices deviate from the average price. It involves the use of three bands—one for the upper level, another for the lower level, and the third for the moving average. Prices moving toward the upper band are a sign that the market might be overbought. In contrast, if prices eventually drift towards the lower or bottom band, the market can be oversold.
![image](https://github.com/adityaaa2511/Technical-Indicators/assets/137895529/59953c7a-8d03-4179-8dad-ac24aab7dd0a)
![image](https://github.com/adityaaa2511/Technical-Indicators/assets/137895529/6d1ab296-c60e-4f1b-982a-3dd6ff890265)
## **Volume Based Indicators**
