# drawerFunctions
A collection of PIL, Numpy and OpenCV functions to manipulate images

Requirements: python3+, pillow, numpy, opencv

I've coded this because I'm lazy, and since I've found myself writing always the same sets of instructions, I've decided to wrap them up in this collection of little functions.

It's filled with common operations, from stroking PNGs to drawing Text, conversions between color spaces, or manipulating images

Should be intuitive but don't forget to read the little docstrings I've provided 

An Image object is required for most common operations of image manipulation, it's a plain matrix of pixels
An ImageDraw object is required for drawing text and polygons. Operating on an ImageDraw object will have effects on Image object

I don't expect to update this very often, but if you find a bug let me know and don't esitate to make pull requests
