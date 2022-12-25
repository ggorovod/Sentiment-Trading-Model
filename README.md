# **Sentiment Trading Model**
![Screenshot](Screenshot.png)

---

The purpose of this project is to leverage machine learning, more specifically, natural language processing to generate a daily trade signal based on news sentiments. Once a strong positive trade signal is generated, our model will put in an automatic buy trade at end of day. A strong positive trade signal is referred to as a compound score. To ensure the effectiveness of the model, we have layered in correlation analysis between daily historical compound score to its previous closing price and generated a total correlation score for stocks that we decided to trade. Our trading model has returned 30.8% cumulative return when backtesting past 2 years' historical data of COP (ConocoPhillips).We believe by feeding in more data points and continue enhancing this model, we will make the model more effective and achieve our trading target.

---

## **Technologies**
---
#### **Technologies Used**:
- Python Code 
- NewsAPI
- NLTK (Natural Language Toolkit)
- Yahoo Finance 
- Google Colab 

#### **Libraries Used**:
- Pandas
- Nympy
- hvplot.pandas
- yfinance
- pandas_datareader
- datetime
- newsapi
- urllib.request
- matplotlib.pyplot
- nltk
- nltk.sentiment.vader (SentimentIntensityAnalyzer)
- holoviews

---

## **Installation Guide**

---

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install nympy
  pip install plotly
  pip install matplotlib
  pip install yfinance
  pip install newsapi
  pip install datetime
  pip install urllib
  pip install holoviews
  pip install nltk
  pip install hvplot
  conda install pycryptodome pycryptodomex
  conda unintall pandas-datareader
  pip install git+https://github.com/raphi6/pandas-datareader.git@ea66d6b981554f9d0262038aef2106dda7138316
```
---

## **Usage**
---

Review the presentation and code material to understand the set up of the algorithmic trading model and how sentiment analysis was conducted. Further review the code the pulls data from yahoo finance and news API. The 

---

## **Contributors**

---

- Lliang, Yvette (yvette.x.liang@gmail.com)
- Gorovodskiy, German (ggorovod01@gmail.com) 
- Sanchez, Gilberto (bertosanchez97@gmail.com)
- Jiva, Azam (Jivazam@gmail.com)
- Tavarez, Gisell (giselltavarez@gmail.com)

---

## **License**

MIT