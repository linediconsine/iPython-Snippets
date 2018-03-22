# iPython-Snippets
Python snippets for the Machine Learning application using iPython


This is my usual imports/load data
```# Import
import seaborn as sb
import pandas as pd
import seaborn as sb
import numpy as np
import re

# VISUAL
from IPython.display import Image, display
#from IPython.core.display import HTML
#from ipywidgets import widgets
from matplotlib import pyplot as plt
plt.figure(figsize=(20,10)) # Big graph because everybody love big graph!

#%config IPCompleter.greedy=True # Autocompletition ON please!
%matplotlib inline

#Load data
raw_df = pd.read_csv("train.csv")
train_mode = True
```

Check shape and show first rows

```
display(df.head())
display(df.shape)
```


Describe the Dataframe

```
display(df.describe())
```

Check if the dataframe has NaN

```
display(raw_df.isnull().sum())
```

Create a Dataframe from 2 arrays
```
df_first_name_repetition = pd.DataFrame.from_dict({ "name_colum_A" : array_name, "name_colum_B" : array_count })
```
