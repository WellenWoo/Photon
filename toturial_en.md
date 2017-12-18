# **Photon**

 1.  Overview 
    Photon is a simplle image operation tool which base on PIL and OpenCv.

 2. Usage 使用

New:New a window.

Open: open a image.

Save:save a image.

Info get the infomation of a image.include the ImageWidth,ImageLength,MinSampleValue,SceneType
and so on.


Flip: Flip the image vertically (top to bottom).

Mirror: Flip image horizontally (left to right).

Resize：Resize the image. You nedd to input the length and width with pixel and separate by dot.

Rotote rotota the image.

Equalize Adjust image color balance.

    Equalize the image histogram. This function applies a non-linear
    mapping to the input image, in order to create a uniform
    distribution of grayscale values in the output image.

Invert：Invert (negate) the image.

Colorize Colorize grayscale image.  
    
    The **black** and **white**
    arguments should be RGB tuples; this function calculates a color
    wedge mapping all black pixels in the source image to the first
    color, and all white pixels to the second color.

Add Border: You need to input the width and color of border.

Reduce Border: Reduce border from the image.You need to input the width of the border.

Add Text: Draw text.You need to input the positon and content. The text wouldn't show  If the positon outside the image.

GrayScale: Convert the image to grayscale.(only for colorful image.)

Split Channel:Split this image into individual bands. This function returns a
        tuple of individual image bands from an image. For example,
        splitting an "RGB" image creates three new images each
        containing a copy of one of the original bands (red, green,
        blue).

Brightness: Adjust image brightness.

    This class can be used to control the brighntess of an image.  An
    enhancement factor of 0.0 gives a black image. A factor of 1.0 gives the
    original image.

Contrast: Adjust image contrast.

    This function can be used to control the contrast of an image, similar
    to the contrast control on a TV set. An enhancement factor of 0.0
    gives a solid grey image. A factor of 1.0 gives the original image.

Sharpness: Adjust image sharpness.

    This class can be used to adjust the sharpness of an image. An
    enhancement factor of 0.0 gives a blurred image, a factor of 1.0 gives the
    original image, and a factor of 2.0 gives a sharpened image.

Color Enhance: Adjust image color balance.

    This function can be used to adjust the colour balance of an image, in
    a manner similar to the controls on a colour TV set. An enhancement
    factor of 0.0 gives a black and white image. A factor of 1.0 gives
    the original image

posterize:Reduce the number of bits for each color channel.

solarize:Invert all pixel values above a threshold.


Filter: Image filter.

Grab: screen grabber.

Add : Adds two images, dividing the result by scale and adding the
    offset. If omitted, scale defaults to 1.0, and offset to 0.0.

Blend :Blend images using constant transparency weight. 

Difference: Returns the absolute value of the pixel-by-pixel difference between the two images.

Multiply: Superimposes two images on top of each other.

    If you multiply an image with a solid black image, the result is black. If
    you multiply with a solid white image, the image is unaffected.

Subtract: Subtracts two images, dividing the result by scale and adding the
    offset. If omitted, scale defaults to 1.0, and offset to 0.0.

Screen : Superimposes two inverted images on top of each other.

Darker : Compares the two images, pixel by pixel, and returns a new image
    containing the darker values.

Lighter : Compares the two images, pixel by pixel, and returns a new image containing the lighter values.

Paste : Copy the selected region from the source image and paste it to the distination.

 3. Notice
   You nedd to open an image before operate it. And colse the dialog when 
   you finish it or it maybe occur an error.
