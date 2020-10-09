# handwritten_digit_recognizer
Using Tensorflow creating a handwritten digit recognizer 
So using the tensorflow  and the keras API installed in i have created this handwritten digit recognizer
it consists of creating the sets of data from the data set being downloaded into it
then the next step involves creating the layers

## The layers are as follows
1)Flatten layer- i have added this layer because here in this model the whole image is being sent as one unit into the input of 28*28 units
2)Dense layer is for the operation of input and ouput 
3)Dropout layer is used for solving the problem of overfitting as my model was facing that issue
4)Dense layer is using the softmax function here which gives us the probability here 



## the next step was compiling
1)the model using the adam compiler and the loss function as sparse_categorical_crossentropy



## training the model had some parameters:
1)Epoch= number of repetitions on the set of data
2)Validation split= to validate the training a fractional amount of data is specified for validation
3)batchsize=to divide the data in a significant amount of batches
4)verbose= to define the representation of training
5)data and its labels were the first two ones

  
## Testing the data on the testing set
