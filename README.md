# toy-data-sets
Small to medium datasets for your "learning data science" convenience

# usage 

https://raw.githubusercontent.com/briandemant/toy-data-sets/main/small/xyz.csv


```python
import pandas as pd
import numpy as np
drinks = pd.read_csv('http://bit.ly/drinksbycountry')
movies = pd.read_csv('http://bit.ly/imdbratings')
orders = pd.read_csv('http://bit.ly/chiporders', sep='\t')
orders['item_price'] = orders.item_price.str.replace('$', '').astype('float')
stocks = pd.read_csv('http://bit.ly/smallstocks', parse_dates=['Date'])
titanic = pd.read_csv('http://bit.ly/kaggletrain')
ufo = pd.read_csv('http://bit.ly/uforeports', parse_dates=['Time'])
```

## Ted kaggle set

https://www.kaggle.com/rounakbanik/ted-talks
