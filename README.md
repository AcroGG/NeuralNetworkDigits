# NeuralNetworkDigits
    #Creating a machine learning neural network from scratch without methods. Using the digit mnist data set.
    #create and apply the activation functions from scratch

    #Variables:
    Weight1: used with the first layer takes in the number of nodes(10 for the number of digits to be recognized) and the number of pixels per image
    bias1: used with the first layer takes in nodes and a bias value of 1
    Weight2: used with the second layer takes 10 nodes for digits and 10 nodes for layer nodes
    Unactivated_layer{num value}: layers with weights and biases before applying the activation functions
    Input_layer{num value}: layers with different activation functions applied to them technically Input_layer_2 is the final output layer prediction
    encode_y: labels (y) the actual digit is encoded into a matrix
    dU{num value}:
    dWeight2:
    dbias2:
        derivative of Unactivated function and derivative of weights and biases basically measuring how far off the guess was from the correct digit(label)
    alpha: a predetermined learning rate for the learning model 
    x == train_x  train_x: is the pixel values at each pixel for the corresponding actual digit(y)
    y == train_y  train_y: is the first row of data which holds the actual corresponding digit of the row of pixel values. 
    dev_x, dev_y: are the values reserved for crosschecking vs the training model.
    m: the amount of rows
    n: Actual digit value of image
