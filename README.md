This is an attempt to Neural Style Transfer
Neural style transfer is a technique in AI amd Computer Vision that allows the artistic style of one image to be transferred onto another image while preserving the content. It leverages deep neural networks to analyze and extract both the style and content features of two input images, then synthesizes a new image that combines the content of one image with the style of another. This process results in visually appealing images that exhibit the content of one image rendered in the artistic style of another.
Pre-trained VGG-19 model was used for the same to extract the features from the cotnent and the style and the input images. 
Started with the content image itself, we back propagate with a weighted sum of the content loss and the style loss (using the gram matrix) to obtain the final styled image.
