# **Datathon Cajamar UniversityHack 2021**

The competition consists of performing a data analysis and feature extraction in order to obtain a model able to **estimate the sales for each product and date.**

The **data** with which we work is provided by the Spanish company PcComponentes that sells technological products.

This notebook is the final work done and summarized in the most important parts.

---


## **Evaluation**

Projects are evaluated following two rules:


1.   The quality of the code, the analytical techniques used and the description of the project presented.
2.   Metric of the error made with respect to the real values and avoid stock outs (when the prediction of units sold is lower than the real demand).

This will be the metric to minimize:
(0.7 * rRMSE) + (0.3 * (1 - CF)),
- CF is the % of favorable cases, defined as those in which there has been no lack of stock, that is, the demand has been equal to or less than the forecast.
- rRMSE is defined as 

>![](https://www.cajamardatalab.com/datathon-cajamar-universityhack-2021/retos/predictivo/formula.jpg)

Being:
* "n" the number of cases
* "Yi" the real value
* "Ŷ" the estimated value
* "Ӯ" the mean of the real values

## **Authors**

1. **Anton Chernysh**: anton_chernysh@outlook.es &  https://github.com/Visn0
2. **Arismendi Sánchez, Carlos Eduardo**: carlos.arismendisanchez@gmail.com & https://github.com/carlosarismendi


