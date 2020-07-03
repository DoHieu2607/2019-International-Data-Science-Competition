# 2019-International-Data-Science-Competition

The goal of this competition is prediction the Up or Down of the most liquid (most traded) currency pair

# Dataset
Dataset was provided by the Forex Market by Yuan Xie - a DHL Data Scientist ([link competition](https://www.isods.org/news-times/item/1-2019-international-data-science-competition))

# My teammate solutions

## In step preprocessing data:
  1. We use **Random forest algorithm** to find best features in dataset.
  2. We set **time sequence/lag, batch size** - paremetesr for LSTM model.
  
## In step create model:
  1. We use LSTM model with total 6 layers (3 layers LSTM, 2 layer Dense, 1 layer Flatten) with activations: tanh,selu,relu,sigmoid. 
  2. We use binary_crossentropy as loss function and accuracy_binary as evaluation metric in the model.
  

