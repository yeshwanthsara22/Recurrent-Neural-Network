# Recurrent-Neural-Network
using DeepLearning Techniques

You will use the same type of data as provided for homework 2. You will design recurrent neural networks to learn models that can predict based on a sequence of inputs (first three columns) and output one output. You should learn and validate your model with the provided data.
Part 1 GRU (50 pts)
You can start with building 4 layers of 16 GRU cells and train the model with the provided data. You should try different number of layers and cells and find the best GRU architecture. You should also perform data preprocessing and drop out to improve your training performance.
Your submission should include - Training code (40 pts)
- With at least four different data preprocessing and training techniques
- Testing script of the train model. It should include loading a dataset and provide output. (5 pts)
- Training and validation results in figures (5 pts)
Part 2 LSTM (50 pts)
You can start with building 4 layers of 16 LSTM cells and train the model with the provided data. You should try different number of layers and cells and find the best LSTM architecture. You should also try the peephole LSTM. You should also perform data preprocessing and drop out to improve your training performance.
Your submission should include - Training code (30 pts)
- With at least four different data preprocessing and training techniques
- Compare results of using LSTM and peephole LSTM for the dataset (10 pts)
- Testing script of the train model. It should include loading a dataset and provide outputs. (5 pts)
- Training and validation results in figures (5 pts)
