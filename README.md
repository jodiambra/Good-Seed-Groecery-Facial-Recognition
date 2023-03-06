# Good-Seed-Supermarket-Facial-Recognition
![N3GUPH5IMRGP5LDZEQ4OFMAE44](https://user-images.githubusercontent.com/115895428/223218577-c5caf041-919e-43ed-8da8-892c453a7de1.jpg)


## Skills Used 
    Plotly Express
    Matplotlib
    Tensorflow
    Keras
    ResNet50
    Adam
    Neural Network

## Purpose
Good Seed Supermarket is looking for a data science solution to help them stay compliant with alcohol laws. They want to ensure that they are not selling alcohol to individuals under the legal limit. Good seed is equipped with cameras in the checkout area  which are triggered ehn a customer purchases alcohol. Given this information, our goal is to use computer vision to determine the age of a person from a picture. The target for the model is an MAE lower than 8.0. However, an MAE of 8 could mean that someone who is 13 years old could be incorrectly predicted to be 21. Therefore, our goal would be to minimize the MAE as much as possible to reduce the model's error. 


## Conclusions
We effectively trained a model to verify the age of a customer from a photo. Our target metric was an MAE of 8, and were able to reduce it to 6.822 with our neural network. That represents nearly a 15% reduction in error from our target. This means our model is on average, off by 6.8 years when predicting a customer's age. Therefore, Good Seed can implement this model to enforce the alcohol purchasing laws and refrain from allowing minors to purchase alcohol.  
