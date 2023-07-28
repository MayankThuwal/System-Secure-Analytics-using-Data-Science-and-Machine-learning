# BreadcrumbsSystem-Secure-Analytics-using-Data-Science-and-Machine-learning
## Downloading the Dataset
You can access the dataset from the given link [Github](https://github.com/defcom17/NSL_KDD) or (https://www.unb.ca/cic/datasets/nsl.html), while appear a Blue color box with "Code" written click on it and select the option Download Zip from the dropdown menu. Then extract the files from the zip folder.

## Adding the Files to Google Drive

After you have the dataset set files, you need open your google drive and create a new folder by right-click or selecting the option to create folder and name the Folder as NSL-KDD, then you need to upload you two files "KDDTrain+.txt" and "KDDTest+.txt" in your folder. This step is needed to mount your drive with google colab.

## Installation

Running the first shell will import all the required libraries, you can run it by using the keys "Shift" + "Enter" or when you click on the cell there will be a grey-column which will have a play button you can click it.

```bash
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import itertools
import random
import time
```

## Connecting to Google Drive

Running this cell will mount your google drive to your Colab file and you will be required to give colab the premission to access your google drive

```
from google.colab import drive
drive.mount('/content/drive')
```

## Running the Code

After you have mounted your drive, you can run the code of cell by clicking on the play button or using the keys "Shift" + "Enter" and the code will run and you will get the results.

OR

You can click on "Runtime" tab in the Toolbar and select "Run all" and the code will run and you will get the results.
