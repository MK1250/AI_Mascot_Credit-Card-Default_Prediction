# AI_Mascot_Credit-Card-Default_Prediction
Keras model to predict credit card default risk using Taiwan Credit Default dataset. 
    Training Method: Activation diversity with layers:
        2 neuron tanh
        8 neuron relu
        2 neuron softmax;

    Training model:
      history = model.fit(X_train, y_train, epochs = 60, validation_data = (X_valid, y_valid), batch_size = 1000)
