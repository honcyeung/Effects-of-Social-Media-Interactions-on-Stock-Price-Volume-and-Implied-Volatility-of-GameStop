# Effects of Social Media Interactions on Stock Price Volume and Implied Volatility of GameStop

Social media has many functions of previous communication tools and business so that users can perform various activities with one account, from texting, networking, and media sharing to advertisements and financial advice. It becomes the communities of information, and opinion and idea exchanges on specific domains, particularly the stock market. 

<p align = "center">
  <img src = "https://cdn.1min30.com/wp-content/uploads/2010/11/Social-media-marketing.jpg"
       </p>

On one hand, retail investors share their thoughts online; on the other hand, they also play a role similar to the aforementioned financial companies – offering in-depth analysis on stock markets that they have learned from education, books, websites, and experience. Because of the abundant resources available on social media, the general public no longer rely on financial institutions for knowledge and advice as much as they did when the internet didn’t exist. These users are active on Twitter and Reddit to discuss the stock market.

<p align = "center">
    <img src = "https://media.gqmagazine.fr/photos/6013e2ad07b639fcdd147b9a/16:9/w_1600,c_limit/1227730798"
         </p>
  
Since December 2020, some Reddit users on r/wallstreetbets were abnormally bullish on the company GameStop (NYSE ticker: GME). They shared lots of analysis on this stock and persuaded their fellows to buy and hold the stock and the call options. They believed the stock was significantly undervalued. The short interest was bizarrely high compared to other stocks, a special environment that can easily cause a short squeeze. Since 11th January, GME stock price surged from 19.94 to the peak price of 347.51 on 27th January because of the pump from users on r/wallstreetbets and the squeezes. It was an increase of more than 17 times. As the stock price went higher, owing to a lack of available stocks for short covering, short sellers were not able to cover their short positions of GME, leading to millions of dollars’ worth of failure to deliver. 
  
The unique phenomenon in the stock market is worth investigating. This research analyzes data scraped from Twitter and Reddit to study the correlations of user interactions and sentiment and each of GME stock price, volume, and implied volatility.
  
Around 130,000 tweets from 21 January to 29 May 2021 are scraped with the python library Twint. Around 90,000 Reddit comments are scraped with Reddit API and the python library pmaw. Linear regression is used to study the correlations. Results have found that although some of the variables are significant, the relationships between dependent and independent variables cannot be established due to some unsatisfied assumptions of regression. 





