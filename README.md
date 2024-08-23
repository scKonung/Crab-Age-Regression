# Crab Age Prediction Model

This project marks my debut in Kaggle competitions, where I developed a straightforward model to predict the age of crabs.

## Dataset Overview

The dataset I utilized for this model is sourced from [this dataset](https://www.kaggle.com/datasets/sidhus/crab-age-prediction). To enhance the model's input, I applied One Hot Encoding to the 'Sex' column, creating individual columns for each sex category.<br>

**Original Data Snapshot:**<br>
![Original Data](https://github.com/user-attachments/assets/b5f722de-80a5-4a35-b1ac-31a017afa7f8)<br>

**Encoded Data Snapshot:**<br>
![Encoded Data](https://github.com/user-attachments/assets/3bbf0b97-d16f-4999-add3-3eb5dc1d91ef)<br>

## Model Overview

The model architecture I employed consists of three Dense layers, with the first two layers having 32 output units each, and the final layer outputting a single value for age prediction. I utilized ReLU activation functions throughout.

## Model Training and Optimization

For training optimization, I chose the RMSprop optimizer and Mean Squared Error (MSE) as the loss function. During the competition phase, I trained the model over 100 epochs with a batch size of 32.

This approach allowed me to create an effective baseline model for predicting crab ages, leveraging straightforward yet powerful techniques to tackle the problem at hand.

