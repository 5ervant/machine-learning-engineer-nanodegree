You can import all of the required libraries using the following code:

    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns

    import os
    import datetime

    import sklearn
    from sklearn.model_selection import train_test_split
    from sklearn.kernel_approximation import Nystroem
    from sklearn.calibration import CalibratedClassifierCV
    from sklearn.metrics import accuracy_score
    from sklearn.metrics import roc_auc_score
    from sklearn.metrics import roc_curve
    from sklearn.base import clone
    from sklearn import ensemble

    from sklearn.cluster import KMeans
    from sklearn.metrics import silhouette_score

    import plotly as py
    import plotly.graph_objs as go

    from sklearn.externals import joblib

In case there's still a missing library which is not yet installed, considered checking the *"Arvato Project Workbook.ipynb"* notebook.

All the codes of the project are written on the *"Arvato Project Workbook.ipynb"* notebook and mentioned on the *"Report.pdf"* document. The *"Arvato Project Workbook-Copy1.ipynb"* is just a copy of the original workbook with just a little modification for testing purposes.
