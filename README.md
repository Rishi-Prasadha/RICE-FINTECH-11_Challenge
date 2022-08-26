# Prophet Predicting for MercadoLibre

This application was written to experiment the broad usage of Facebook's Prophet library. Multiple analyses were run to determine relationships between search trends and stock price, as well as predicting the short term effect on MercadoLibre's popularity. 

---

## Technologies 

This application runs on Python 3.7, work was done on Google Colab

---

## Libraries

Work was done on Google Colab. Prior to running import statements below, multiple libraries have to be installed: 

```python
!pip install pystan~=2.14
!pip install fbprophet
!pip install hvplot
!pip install holoviews
```
Import statements already present in program, refer to them below:

```python
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```

---

## Database

This program couldn't run without the CSV data:

* google_hourly_search_trends.csv
* mercado_daily_revenue.csv
* mercado_stock_price.csv

---

## Contributors

Thank you for Eric Cardena for teaching Rice's FinTech Boot Camp. He was instrumental in teaching and helping us understand this material. Thank you for Rice for preparing this curriculum and the corresponding data sets that are required to be used. 

**Rishi Prasadha**

**LinkedIn**: https://www.linkedin.com/in/rishi-prasadha-912212133/

**Instagram**: @therishiprasadha

**Twitter**: @RishiPrasadha

---

## Licenses 

MIT