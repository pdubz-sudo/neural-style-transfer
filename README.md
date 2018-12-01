This was a deep learning assignment doing neural style transfer in TensorFlow. I coded the algorithms formulas and 
finished building the model.
This assignment uses transfer learning as we load in a VGG 19 layer neural network.
The algorithm I code pulls the middle layer activations of the deep NN. The NN and has inputs of 2 pictures: 1 picture has a certain 
artistic style while the other picture is a picture that will be converted to contain the original image but look similar to the art 
style. This is done by reducing the cost functions of a similarity matrix called gram matrix from a middle layer of the NN.

- Unfortunately, the pre-trained VGG 19 Deep NN model is too large to upload on github. It can be downloaded here 
https://github.com/onnx/models/tree/master/vgg19
