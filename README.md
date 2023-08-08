# Module 13: Neural Networks

## Overview of the Analysis

* For this analysis we use neural networks to predict whether any particular startup will be successful.
* The data used for prediction includes financial, legal, and tax information about the startup.
* We first try a normal neural network and then use deep learning techniques.

## Results

* Model 1:
```
Original Model Results
268/268 - 0s - loss: 0.5615 - accuracy: 0.7308 - 326ms/epoch - 1ms/step
Loss: 0.5614610314369202, Accuracy: 0.7308454513549805
```

* Model 2:
```
Alternative Model 1 Results
268/268 - 1s - loss: 5.1647 - accuracy: 0.7297 - 1s/epoch - 5ms/step
Loss: 5.164718151092529, Accuracy: 0.72967928647995
```

* Model 3:
```
Alternative Model 2 Results
268/268 - 1s - loss: 0.5729 - accuracy: 0.7294 - 502ms/epoch - 2ms/step
Loss: 0.5728796124458313, Accuracy: 0.7294460535049438
```

## Summary

Based on the performance of each model against the testing data. The simplest Model, `Model 1` performed the best. I chose to experiment with `Model 2` and `Model 3`, using the input features and units as variables for layer generation. This didn't provide any reasonable improvement.

---

## Technologies

This application uses python 3, please install the necessary packages as described below to recreate the analysis.

---

## Installation Guide

```
pip install -r requirements.txt
```

---

## Usage

Open the file `GC_venture_funding_with_deep_learning.ipynb` in Google Colab. Data sources are located in the `Resources` folder and the models generated during initial analysis are saved with the AlphabetSoup prefix.

---

## Contributors

[rowrowrowrow](https://github.com/rowrowrowrow)

---

## License

No license provided, you may not use the contents of this repo.
