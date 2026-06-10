# DATASCI207_WildfirePrediction

## Data Setup

The dataset is 3.5GB and too large for GitHub, so I uploaded it to Google Drive. It is in a folder called `wildfire-prediction-data/data/`. Below is the code I used to mount Google Drive in a notebook:

```
from google.colab import drive
drive.mount('/content/drive')
```

Next, I ran the following to ensure all files have been mounted:

```
import os

DATA_PATH = "/content/drive/MyDrive/wildfire-prediction-data/data/"
files = os.listdir(DATA_PATH)
print(f"Found {len(files)} files:")
for f in files:
    print(f)
```