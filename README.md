# Macroeconomy and Confidence 

## Overview 

Behavorial finance has been a hot topic explored by academia. Does herd mentality impact global markets? Can there be potential warning signs for future corrections? Many of these answers are ambiguous, however we know for certain that no individual can tell the future with certainty. Our group has presented our findings to key questions that we have listed below. 

We have obtained data for our findings using API's from Quandl, and Yahoo Finance. In addition, we have also utilized the Federal Reserve Economic Data (FRED). We have obtained confidence indicators utilizing Yale's School of Management stock market indicies. The confidence indicators are results of surveys given to individual and institutional investors. 

The one year confidence index illustrates the percent of the population expecting an increase in the Dow in the coming year. The valuation confidence index illustrates the percent of the population who think that the market is not too high. The crash confidence index illustrates the percent of the population who attach little probability to a stock market crash in the next six months.


## What is the general confidence level of the market?

  1. The mean individual confidence level is 76.5 and the mean institutional is 77.6. This tells us that the outlook on the market is generally positive. Over time, the confidence of the stock market for both institutions and individuals has been in a downtrend.
  2. Institutional Investors tend to remain more confident over time with a major crossover showing this reality in 2007. Prior to 2007, individual confidence was consistently greater. Our team speculates that this can potentially be due to individuals having a negative sentiment towards the market after the dot.com bubble and Great Recession. 
  3. Institutional value confidence has reached the same low levels witnessed in 2000, which indicates a stronger beleif in market prices being high. Individual value confidence is reaching these levels. Both are clearly making lower lows.
  4. Institutional and individual crash confidences reached levels similar to 2000, 2001, 2009, & 2011, indicating that they believe a crash is more likely. This bounced and rose quickly as in previous instances, but neither the institutional or individual confidence levels have reached the mean levels of confidence, 35 and 32 respectively, yet.
  5. Confidence levels were all negatively correlated, although with different strengths of negative correlation, to the DJI. We made a heatmap to represent this as well as performed a covariance of the DJI and confidence indexes and all resulted in a negative covariance once again indicating a negatice correlation between the DJI performance and confidence levels over time. Those values were: Institutional One Year Confidence covariance -19824.09, Individual One year Confidence covariance-36680.06, Institutional Value Confidence covariance -40478.91, Individual Value covariance -56502.27, Institutional Crash Confidence covariance -3264.86, Individual Crash Confidence covariance -13859.16.

## Do confidence levels in the upper quartile and lower quartile indicate a coming market reversal?

![Upper and Lower Quartile](images/bokeh_plot (1).png)

  1. While doing our analysis, we found that the upper quartile of confidence data was all concentrated in the years 2001-2006 and the lower quartile of confidence data was all concentrated in the years 2014-2020. The mean confidence level for institutions in the upper quartile was 86.26, the min was 81.11 and the max was 92.52. The mean confidence level for individuals in the upper quartile was 89.38, the min was 83.93 and the max was 95.62. The mean confidence level for institutions in the lower quartile was 69.49, the min was 61.54 and the max was 74.02. The mean confidence level for individuals in the lower quartile was 65.80, the min was 59.75 and the max was 70.71. 
  2. When we compared these confidence levels to the DOW jones, it becomes clear that there is a negative correlation between the DJI and the confidence of institutional and individual investors. This could be due to greater market volatility in recent years, or painful memories of prior market instability. Therefore rather than using the one year confidence index as an indicator for a market reversal, the one year confidence levels better serve to help us understand the effects of historical market performance on individual and instituitonal confidence over time and they reflect overall sentiment of the investor.


## What is the performance of the Dow when confidence indicators shift? 

  1. If you were only to invest in the Dow Jones Industrial Average when institutional confidence levels exceed 70%, you would have a performance of roughly 185% your initial investment. However, if you were only to invest when insitutional confidence was below 70%, you would only have roughly a 15% return on your investment. We can reasonably expect that the Dow performs better when insitutional confidence is greater. Currently, institutional confidence is roughly 61%.
  2. If you were only to invest in the Dow when individual confidence exceeds 70%, your return would be roughly 160%. This metric is slighly below the instutional figure meaning that individual investors are not as likely to predict market performance as well. An interesting statistic we found was if you invested only when institutional confidence was below 70%, you would still generate a return of roughly 41%. This indicates that individual investors are less likely to predict market performance as institutional investors. 

## What do macroeconomic measures tell us about the market's performance, and how do they compare to confidence levels?

  1. In recent years the volatility in macroeconomic indicators associated with market events has increased each cycle. This is evident in the unemployment level and in GDP. We plotted them together to show how the increase in volatility in these indicators coincide with certain market events. When we compared this to the confidence indexes we noticed moves towards lower levels of confidence associated with the periods of volatility in the macroeconomic indicators.

## Is there a dislocation between market sentiment and the realiity of the economy?

  1. In our analysis we discovered that the confidence indexes have been in a downtrend since 2002, at times consolidating and moving sideways, but then further moving lower. The confidence indexes are negatively correlated with the DJI. In addition to these relationships with the market, increasing macroeconomic volatility coincides with further moves lower in confidence levels. In summary, we discovered a divergence in confidence levels and market performance, as well as a relationship between macroeconomic volatility and confidence levels. It is difficult to say whether confidence levels impact the market's performance, or whether the market's performance impacts confidence levels, however in the wake of financial events since the early 2000s, along with greater volatility in macroeconomic indicators, we have witnessed an aggregate decline in confidence levels, indicating that fewer people beleive we will see an increase in the DOW 1 year from now, more people believe there is a greater probability for a market crash six months from now, and more people beleieve the market is too high.




## Economic Analysis 

1. Are there relationships with the SP500 and the GDP? 

  Berkshire Hathaway has used Corporate Equities / GDP to analyze market conditions to make investment decisions. For the most part, this ratio has been telling in determining when the market is "overvalued." In our analysis, our group had used the SP500 / GDP to make a similar analysis regarding current market condidions. We believe the SP500 is the most representitive indicator os the United States market as a whole. We have currently surpassed levels that we have seen during the Dot.com bubble and Great Recession. This coupled with low institutional confidence should give a negative sentiment indicator for the future. 

2. What relationships are there with the SP500 P/E with the overall economy? 

  Given our analysis, we have seen spikes in the SP500 P/E ratio in 2000, and 2008. Although we have not reached those levels, we are seeing upward trends similar to market corrections of the past. 

3. Does over extention of the SP500 PE ratio indicate a potential correction? 

  The SP500 P/E ratio can provide valuable analysis when determining if a possible market correction is plausable. In our group's analysis we had used the SP500 P/E ratio againt the SP500 / GDP and have found compelling trends. Currently we are on an upward trend similar to the Dot.com bubble upward trend. 



