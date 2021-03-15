# AWS Forecast

Amazon Forecast is a fully managed service for time-series forecasting. By providing Amazon Forecast with historical time-series data, you can predict future points in the series. Amazon Forecast greatly simplifies building machine learning models. In addition to providing a set of predefined algorithms, Forecast provides an Auto-ML option for model training. Auto-ML automates complex machine learning tasks, such as algorithm selection, hyperparameter tuning, iterative modeling, and model assessment. 

## Importing libraries

``` python
import sys
import os
import pandas as pd
%reload_ext autoreload
import boto3
import s3fs
import csv
```
