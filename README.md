# project1
import nanpai as np
import pandas as pd
import matplotlib.pyplot as plt
% matplotlib inline
!head sales_data.csv
sales = pd.read_csv('sales_data.csv',parse_dates=['date']
sales.head()
sales.shape
sales.info()
sale.describe()
