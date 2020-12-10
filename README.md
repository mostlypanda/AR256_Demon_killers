# AR256_Demon_Killers(Cotton future market trend prediction)

## Available live at https://wocn-demon.web.app 
![Languages](https://img.shields.io/github/languages/count/mostlypanda/AR256_Demon_killers?style=plastic)
![Issues](https://img.shields.io/github/issues/mostlypanda/AR256_Demon_killers?style=plastic)
![Code-Size](https://img.shields.io/github/languages/code-size/mostlypanda/AR256_Demon_killers?style=plastic)
![License](https://img.shields.io/badge/license-MIT-purple?style=plastic)
![Completion](https://img.shields.io/badge/Project%20Phase-Updating%20Past%20Price%20data-blue?style=plastic)


# SIH-2020(Software Edition)

This is the problem given by Ministry of Textiles in SIH-2020 software edition in Grand finale, here the problem is to
* Artificial Intelligence based solution for predicting future price trend of cotton

* Suggesting a suitable pricing model.

* Maintaining the bridge between buyers and sellers.

# Solution-

* Developing a highly interactive Bi-lingual user’s interface for showing the future market price trend of cotton.

* Predicting day-wise and month-wise price trend for next one year of major market places (both tabular and in the form of graph) of cotton in India.

* Best price of cotton in your city from all market places of cotton in your desirable month.

### Technology Stack

* **For client side**
    -React.js with bootstrap and axios for data transfer

* **For server side**
    -Django (a framework of python) and MongoDB as our database

* **Machine Learning Models**
    * Non-Linear Random Forest Regression model for day wise future trend.
    * Arima model for full year trend

**Factors considered in ML Model:**

* In Non-Linear Random Forest Regression Model
    * Yield 
    * Area Sown
    * Inflation Rate
    * Date 
    * Month

* In Arima Model
    * Time based analysis done here on available past year data.

# Our End Users

**Farmers:**
   
   * They can easily get an idea when to sell their surplus at what rate.
   
   * What would be their net price including all taxes and transportation cost in some other city or state 

**Industrialists:**
   
   * Easily compute their net profit 
   
   * Develop their marketing strategy for the next commercial year i.e. when and from where to buy their raw materials.

# How our model is working

 * Our Random forest model is able to discover more complex dependencies. 

 * It is the sum of piecewise function and has regularization inbuilt.

 * In our time-series analysis model(arima), we are minimizing irregularity by implementing operations like logscale and exponential weighted moving average.

 * Our model is giving RSS value around 0.32 and p value around 0.002 which is quite appreciable.

 * We are getting an order of (1,1,1) for our arima model

# Conclusion

* This with the help of our web-application one can see the future trend of cotton in major market places of cotton in the nation, both day-wise and month-wise trend for the    next one year.

* For both buyers and for sellers we are increasing market place area by getting them know about the future cost of cotton at their door-step.

* Our interaction user-interface will fascinate the user as well.



