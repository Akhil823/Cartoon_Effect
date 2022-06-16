# Cartoon_Effect
Gives Cartoon type effect to an image using OpenCV. 

First, we load an image and then create edge mask. Edge mask helps us in emphasising the edges present in an image. 

Next, we change the colours of the image by reducing the different number of colours and setting it to a value k. K means clustering is used to decide the colour for a point of the image.

After that we remove noise using bilateral filter.

At last, we combine the obtained image and the edges to get our final image with cartoon effect.
