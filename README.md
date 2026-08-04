# DATASCI207: Predicting Next Day Wildfire Spread in the United States

In this project, we aimed to answer the following question: "Can we use machine learning to predict where active wildfires in the United States will spread within the following 24 hours given the current fire perimeter and environmental conditions?"

We used data from [Next Day Wildfire Spread](https://www.kaggle.com/datasets/fantineh/next-day-wildfire-spread), which includes twelve input features, mostly regarding weather and environmental conditions, and a next day fire mask.  

After preprocessing the data and performing EDA, we built the following models:
- 1x1 Convolutional Neural Network (CNN)
- Multilayer CNN
- U-Net Encoder-Decoder CNN

We tested the performance of our models using Area Under the Curve (AUC). Final models and evaluations are in `WildfirePrediction_FinalModel.ipynb`.