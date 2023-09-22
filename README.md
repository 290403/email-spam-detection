# Email-Spam-Detection
In this project we can detect the ham and spam files . we find the percentages of spam emails by using dataset of kaggle.
import numpy as np 
import pandas as pd 

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
