# Unit 14 Homework Assignment - LSTM Stock Predictor

## Assignment by Dorothy Doutre 

![image_add](https://github.com/Dottie-Doutre/Unit-14_Dottie-Doutre/blob/main/Images/deep-learning.jpg?raw=true)

## Assigment Summary:

I have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG (Crypto Fear and Greed Index) indicator to provide a better signal for cryptocurrencies than the normal closing price data.

I will be utilising deep learning recurrent nueral networks to model Bitcoin closing prices.

###  Developed by implmenting the following:

```
Preparing the data for training and testing.

Build and train custom LSTM RNNs.

Evaluate the performance of each model (closing and FNG).
```
### Technologies used:
- GitBash
- Python 
- Jupyter lab (algotrading env)
- VS Code
---
## Assignment findings:

**Which model has a lower loss?**

The closing predictor had a lower loss at 0.0092 than the FNG model (0.1131).

***Close*** -

![image_add](https://github.com/Dottie-Doutre/Unit-14_Dottie-Doutre/blob/main/Images/image_closing_loss.PNG?raw=true)

***FNG*** -

![image_add](https://github.com/Dottie-Doutre/Unit-14_Dottie-Doutre/blob/main/Images/image_fng_loss.PNG?raw=true)

**Which model tracks the actual values better over time?**

The closing model tracked better over time than the FNG model.

***Close*** -

![image_add](https://github.com/Dottie-Doutre/Unit-14_Dottie-Doutre/blob/main/Images/image_closing.PNG?raw=true)

***FNG*** -

![image_add](https://github.com/Dottie-Doutre/Unit-14_Dottie-Doutre/blob/main/Images/image_fng.PNG?raw=true)

**Which window size works best for the model?**

At least a window size of 10 works best with the model.
