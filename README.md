# Neural-Style-Transfer

This idea is implemented after reading the paper by Leon A. Gatys, Alexander S. Ecker, Matthias Bethge <a href="http://arxiv.org/abs/1508.06576">A Neural Algorithm of Artistic Style</a>

I have used Tensorflow 2.0 and VGG19 pretrained model to implement the Deep Neural ConvNet. <a href="https://keras.io/api/applications/vgg/#vgg19-function">VGG19 Model</a>

Used Transfer learning (VGG19 model) to apply style transfer on a given image. Provided an Image (Content Image), the algorithm will apply a ‘Style Image’ onto it using the Neural net and produce the Styled Image as Output. The output image looks like the content image, but “painted” in the style of the style reference image. This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network. 

<h2>Examples<h2>

<img src="https://github.com/protyayofficial/Neural-Style-Transfer/blob/main/New%20York.png">
<br><br>
<img src="https://github.com/protyayofficial/Neural-Style-Transfer/blob/main/Content/dog.jpg" width=49% height=300>
<img src ="https://github.com/protyayofficial/Neural-Style-Transfer/blob/main/Style/cubist.jpg" width=33% height=300>
<img src="https://github.com/protyayofficial/Neural-Style-Transfer/blob/main/Doggo.png" width=49% height=300>
