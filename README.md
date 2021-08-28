# Auto_Colourise_Image

How NASA Auto Colourise Images 

RGB to LAB

As we have color image, so we will be first converting to LAB L - Lightness (Black and White) A, B - Color

We will pass L to autoencoder which will predict A', and B'. To get full RGB image we will convert LA'B' to RGB
