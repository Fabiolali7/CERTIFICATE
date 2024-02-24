Hackaton_NISR-Brighter
IN this dashboard we worked on seasonal agricultural survey using data established by national instititute of Statistics of Rwanda .

bellow are main indicators presented

day 1: Agricultural area used (caltuvated area and harvested are etc..) day 2: Agricultural inputs and agricultural practices day 3: sowing date and sources of Agricultural inputs day 4: time series graph of GVA for every crop and national presentation day 5: Model predicting 2023 and 2024 GVA day 6: Agricultural area and yield in my dashboard I used dash a , plotly and pandas as packages

here are packages to be installed while trying to run my dash locally

import warnings from glob import glob import dash import glob import os import numpy as np import plotly.express as px from IPython.display import VimeoVideo from ipywidgets import Dropdown, FloatSlider, IntSlider, interact import pandas as pd from sklearn.model_selection import train_test_split from sklearn.linear_model import LinearRegression from sklearn.metrics import mean_squared_error, r2_score from sklearn.compose import ColumnTransformer from sklearn.pipeline import Pipeline from sklearn.preprocessing import OneHotEncoder from ipywidgets import interactive warnings.simplefilter(action="ignore", category=FutureWarning).

message to be transimited t highlight the main indicators of SAS user can interact with my dash by using dropdown and slider to select one of his/her choice even by hovering on the graph.
