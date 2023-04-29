# ae-img-clas
Few-Shot Learning With Autoencoders

In this experiment, a Few-Shot image classification method consisting of the number of categories of single-layer neural networks is introduced based on the training of image classifier on MNIST. The main idea of this method is to use a single layer neural network and train the "drawing" of the number based on a small sample set of each number, so that the neural network learns to redraw the image as close as possible to the original training image. Finally, each of these $10$ numbers redraw the same input handwritten digit image with the learned drawing method for handwritten digits of different $10$ categories. The similarity of the redrawn image from the original image is calculated for the reshaped result of each drawing method model. The network model with the greatest similarity is the corresponding classification result.
![image](https://user-images.githubusercontent.com/126972674/235288460-a935ca57-48a1-4fd3-b7a1-944002e5274e.png)
![image](https://user-images.githubusercontent.com/126972674/235288469-5fcae5e1-e16d-447d-b8bd-babdc996fcb4.png)
