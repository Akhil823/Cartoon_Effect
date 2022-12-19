# Cartoon_Effect
Gives Cartoon type effect to an image using OpenCV. 

First, we load an image and then create edge mask. Edge mask helps us in emphasising the edges present in an image. 

Next, we change the colours of the image by reducing the different number of colours and setting it to a value k. K means clustering is used to decide the colour for a point of the image.

After that we remove noise using bilateral filter.

At last, we combine the obtained image and the edges to get our final image with cartoon effect.

#Input Images:

![Car_image](https://user-images.githubusercontent.com/57368125/208422802-9025d81e-f51e-4faf-9c04-f30b90c94581.jpg)
![Nature](https://user-images.githubusercontent.com/57368125/208423025-7767fb4d-ee9d-4461-889b-047c44b56e4a.jpg)

#Output Images:

![car_cartoon](https://user-images.githubusercontent.com/57368125/208422841-9053f2cc-9bf7-427d-a9bb-e8d91b790c05.jpg)
![Nature_cartoon](https://user-images.githubusercontent.com/57368125/208422985-25914c96-6dc4-4fd4-a01d-e9aab3a97362.jpg)

