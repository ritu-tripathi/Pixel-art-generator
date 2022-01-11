# Pixel-art-generator
This is a fun machine learning project that lets you to convert your images to pixel art!
Here we are converting a 800 by 800 px image. I have used Pillow Library for image manipulation and Matplotlib library for displaying and saving images. 
First we will read our image by  the open function of Image module of Pillow library. Once the image is read, it can be displayed using imshow function of matplotlib. Then we have converted our image to a small image using Bilinear interpolation resampling technique. 
The small image is then resized to the desired output size.
Made use Nearest Neighbour resampling technique which is essentially enlarging each pixel.
Then finally we create a function to convert our image and display it with the original image for comparison.
