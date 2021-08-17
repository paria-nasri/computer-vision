# computer-vision
It contains 70,000 items of clothing in 10 different categories. Each item of clothing is in a 28x28 greyscale image.
The Fashion MNIST data is available directly in the tf.keras datasets API.
Calling load_data on this object will give two sets of two lists, these will be the training and testing values for the graphics that contain the clothing items and their labels.
print a training image, and a training label to see
after this step ,all of the values in the number are between 0 and 255.
normalizing is implemmented to have  values between 0 and 1.
 activation function layer 2 is Relu
 activation function layer 3 is softmax that takes a set of values, and effectively picks the biggest one.
 build model by calling model.fit to fit training data to your training labels
 epochs is 7 
