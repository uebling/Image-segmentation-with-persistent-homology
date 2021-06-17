# Image-segmentation-with-persistent-homology
An interactive notebook/web app to play around with image segmentation using persistent homology.

Click the binder button below to start the web app:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/uebling/Image-segmentation-with-persistent-homology/HEAD?urlpath=voila%2Frender%2Fsegmentation.ipynb)

You won't have to deal with packages, but memory is limited on binder, so the images get scaled down if you upload very large ones.


**How to use the app**
It should be rather clear on how to use it, but importantly:
* Whenever you make a change in the image selection, you must click the "Generate new persistence diagram" button and wait for a new message to appear, before manipulating the threshold below. Otherwise it will use the previous diagram to segment the image and the results won't make much sense.
* The interactive plots only update if you move the sliders/press buttons. So if you swapped the image and generated the diagram, in the thresholding part the new image will only appear after moving the threshold.
