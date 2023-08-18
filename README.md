# Texture Classification of Leather Defects

A very basic project to binary classify image samples of leather texture into defective or non-defective. 

A little about the main concept of convolutional layers used in image processing, that I have employed as a layer while training the model.
The main purpose to pass the image through multiple layers is to identify the defects clearly, which are recognised as pixel deviations from its surroundings.

![IMG_1629](https://github.com/lahiripratik/Texture-Classification-of-Leather-Defects/assets/84749230/d29083e4-70fa-462b-a859-9feac04d8224)
![IMG_1630](https://github.com/lahiripratik/Texture-Classification-of-Leather-Defects/assets/84749230/f67707af-bd8f-4c69-9a7e-8a7845b680a2)

## A broad outline of the layers used in the model and their working

![image](https://github.com/lahiripratik/Texture-Classification-of-Leather-Defects/assets/84749230/95427fdf-c1b3-46c2-b46e-d92091cbb428)

The sequential model consisted of the following layers
### Dropout Layer
![image](https://github.com/lahiripratik/Texture-Classification-of-Leather-Defects/assets/84749230/f35c1e6b-2358-446d-9402-894c96b57890)

### Conv2D Layer (as explained above)
### MaxPooling2D Layer
This layer is placed on the convulated image after applying the convulution layer.
Picks up the maximum intensity values, hence the word 'Max'.

![image](https://github.com/lahiripratik/Texture-Classification-of-Leather-Defects/assets/84749230/6c207471-0748-4348-8678-bc38a70e673b)



