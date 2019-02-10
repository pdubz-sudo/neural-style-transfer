This was a deep learning assignment doing neural style transfer in TensorFlow. I coded the algorithms formulas and 
finished building the model.
This assignment uses transfer learning as we load in a VGG 19 layer neural network.
The algorithm I code pulls the middle layer activations of the deep NN. The NN and has inputs of 2 pictures: 1 picture has a certain 
artistic style while the other picture is a picture that will be converted to contain the original image but look similar to the art 
style. There are several cost functions that are used for this algorithm. 
The cost functions which start blending the 2 pictures use a similarity matrix called gram matrix and a lot
of the ideas of this algorithm come from that middle layers of the NN are used as their neurons are activated by 
not too particularly specific image features but not too low level either of the input that will be converted.

- Unfortunately, the pre-trained VGG 19 Deep NN model is too large to upload on github. It can be downloaded here 
http://www.vlfeat.org/matconvnet/pretrained/ and is called imagenet-vgg-verydeep-19.mat
