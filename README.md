# DIP_Assingment03

This assingmenmt implements the Otsu thresholding segmentation method and manual morphological operations (erosion, dilation, opening, and closing) from scratch using Python. It compares the segmentation result with the results after applying morphological processing to demonstrate how these operations improve image clarity and remove noise. In this code the library that i only use is Numpy for matrix operations on the images, PIL for image loading and grayscale conversion, Matplotlib for visualizing the image results, and Google Colab / io for uplod file.

Otsu's Method: Automatically finds the optimal threshold to separate the foreground and background by maximizing the variance between the two classes of pixels.
Erosion: Removes small white noise and shrinks the boundaries of white objects.
Dilation: Expands the boundaries of white objects and fills small black gaps (pepper).
Opening: It is used to remove noise (small white speckles) from the background.
Closing: It is used to fill noise (small black holes) in the foreground.

The result shows that applying morphological operations leads to a much cleaner, more refined, and more accurate segmentation outcome.

#  References
1. https://medium.com/@ami25480/morphological-image-processing-operations-dilation-erosion-opening-and-closing-with-and-without-c95475468fca
2. https://stackoverflow.com/questions/48213278/implementing-otsu-binarization-from-scratch-python
3. https://www.geeksforgeeks.org/python/python-pillow-tutorial/
