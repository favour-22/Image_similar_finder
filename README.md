# Image_similar_finder

``The script accepts command-line arguments for the input folder, the output folder, the hash size, and the threshold for detecting similar images. The hash size specifies the size of the hash value that will be calculated for each image. The threshold is a percentage value that determines the maximum number of different bits allowed between two images before they are considered similar.

The script calculates the hash value for each image using a process called "perceptual hashing." This involves converting each image to grayscale, calculating the mean color value of the pixels in the image, and then setting each pixel in the image to either black or white depending on whether its color value is above or below the mean. The resulting black-and-white image is then used to generate a hash value.

To identify similar images, the script compares the hash values of each pair of images in the input folder. If the number of different bits between the hash values is below the specified threshold, the images are considered similar, and the second image is moved to the output folder.

Note: The script also includes a function to generate a video animation showing the effect of different hash sizes on an image``
