This was a deep learning assignment doing neural style transfer in TensorFlow. I coded the algorithms formulas and built the model.
This assignment uses transfer learning as we load in a VGG 19 layer neural network.
This algorithm uses the middle layer of a neural network and has inputs of 2 pictures. 1 picture has a certain artistic style
while the other picture is a picture that will be converted to contain the original image but look similar to the art style. This is 
done by reducing the cost functions of a similarity matrix called gram matrix.