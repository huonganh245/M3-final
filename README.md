# M3-Group-Assignment

### Problem statement 
Identifying a way to predict the stock market return series has been on the agenda of academicians and practitioners for quite a while. Due to this we decided to make an attempt into forecasting the future value of stocks using Random Forest, Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM).
### Exploratory Data Analytics [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-fS-iu3PHhvHNO2kZhvrGeS-6sFyAx8T#scrollTo=t4UAmdOvAaQv)
### Machine learning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TilDy1kdyprlLbIXqU5ifQlOoxmBP0Oq)
### Deep learning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11Loo-3jIjObW91hqmsUfsPsC9L2DdiQv)

### All in one (EDA + Machine learning + Deep learning (1)) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17vfdvdi9BahXkPLq_4hKsSaJOps7xsRg)

### Deep learning (2) with Amazon [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1awU7HwE4mhGMbweepVPG3WVnkCLp5D0T)

### File name explanation
Data source: https://www.kaggle.com/dgawlik/nyse
Dataset consists of following files:

- prices.csv: raw, as-is daily prices. Most of data spans from 2010 to the end 2016, for companies new on stock market date range is shorter. There have been approx. 140 stock splits in that time, this set doesn't account for that.
- prices-split-adjusted.csv: same as prices, but there have been added adjustments for splits.
- securities.csv: general description of each company with division on sectors
- fundamentals.csv: metrics extracted from annual SEC 10K fillings (2012-2016), should be enough to derive most of popular fundamental indicators.
