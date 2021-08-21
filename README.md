# **Datathon Cajamar UniversityHack 2021**

The competition consists of performing a data analysis and feature extraction in order to obtain a model capable of **estimating sales for each product and date.**

The **data** we work with is provided by the Spanish company PcComponentes that sells technological products.

This notebook is the final work done and summarized in the most important parts.

---


## **Evaluation**

Projects are evaluated following two rules:


1.   The quality of the code, the analytical techniques used and the description of the project presented.
2. Error metric between real values and stock outs (this is, when predicted sales are lower than real demand.

This is  the metric to minimize:
(0.7 * rRMSE) + (0.3 * (1 - CF)),
- CF is the % of favorable cases, defined as those in which there has been no lack of stock, that is, the demand has been equal or less than forecasts.
- rRMSE is defined as 

>![](https://www.cajamardatalab.com/datathon-cajamar-universityhack-2021/retos/predictivo/formula.jpg)

Being:
* "n": number of cases
* "Y<sub>i</sub>": real value
* "Ŷ<sub>i</sub>": estimated value
* "Ӯ": mean of the real values

## **Authors**

1. **Anton Chernysh**: anton_chernysh@outlook.es &  https://github.com/Visn0
2. **Arismendi Sánchez, Carlos Eduardo**: carlos.arismendisanchez@gmail.com & https://github.com/carlosarismendi
