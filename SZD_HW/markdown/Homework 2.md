# HOMEWORK II

## Imports and stuff


```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.optimize import curve_fit

#gauss distribution
def carl_friedrich(x,a,mu,sig):
    return a * np.exp(-(x - mu)**2/(2*sig**2))
```


```python
params = {
      'text.latex.preamble': r"\usepackage{mlmodern}",
      'legend.fontsize': 9,
      'axes.labelsize': 9,
      'axes.titlesize': 11,
      'xtick.labelsize' :9,
      'ytick.labelsize' : 9,
      #'mathtext.fontset': 'cm',
      #'mathtext.rm': 'stixsans',
      'font.family' : 'mlmodern', 
      #'font.family' : 'sans-serif',
      'text.usetex' : True,
      }
plt.rcParams.update(params)
```
