# Identify plane from pictures 

Classify type of planes from random pictures. 
This would be visible online thanks to an application "Streamlit". 
## Data base 
```
https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/archives/fgvc-air 
```
## Imports 
```
import keras
import pathlib

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import tensorflow as tf

from keras.models import Sequential, load_model
from keras.layers import Conv2D, MaxPool2D, Dense, Flatten, Dropout
#from tensorflow.keras.utils import to_categorical

from sklearn.model_selection import train_test_split

import datetime 
```
