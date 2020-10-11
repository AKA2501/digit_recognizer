# Handwritten_digit_recognizer
Using Tensorflow creating a handwritten digit recognizer 
So using the tensorflow  and the keras API installed in i have created this handwritten digit recognizer
it consists of creating the sets of data from the data set being downloaded into it
then the next step involves creating the layers

## The layers are as follows
- Flatten layer- i have added this layer because here in this model the whole image is being sent as one unit into the input of 28*28 units
- Dense layer is for the operation of input and ouput 
- Dropout layer is used for solving the problem of overfitting as my model was facing that issue
- Dense layer is using the softmax function here which gives us the probability here 

## The next step was compiling
- The model using the adam compiler and the loss function as sparse_categorical_crossentropy

## Training the data using the parameters:
- Epoch = number of repetitions on the set of data
- Validation split = to validate the training a fractional amount of data is specified for validation
- Batchsize =to divide the data in a significant amount of batches
- Verbose = to define the representation of training
- Data and its labels were the first two ones

## Testing the data using the data given

  
## Build Instructions

Enter this command into terminal/command prompt:
```bash
git clone https://github.com/AKA2501/digit_recognizer.git 
```

## Contributions
Anyone who's intrested can contribute to this project
