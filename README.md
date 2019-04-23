# maker.ai
AI based 3D printer which takes in a single 2.5 D image as an input and provides a 3D model to be used with the 3D printer


cd marrnet
./download_models.sh

th main.lua -imgname chair_1.png

cd visualization/blender

blender --background --python render.py -- ../../output/chair_1.mat ../result/ chair_1

| Original Sketch | 
| ------------- | 
| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/image/chair_draw.png)| 

3D Reconstructed Model:

![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_draw_0_view_1.png) | ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_draw_0_view_2.png)| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_draw_0_view_3.png)  |



Generative Adversarial Network for 3D object reconstruction from 2D image :

![alt text](https://github.com/srihari2761/maker.ai/blob/master/model.jpg)



| Original Sketch 1| 
| ------------- | 
| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/image/chair_test1.jpg)| 

3D Reconstructed Model:

![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test1_0_view_1.png) | ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test1_0_view_2.png)| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test1_0_view_3.png)  |



| Original Sketch 2 | 
| ------------- | 
| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/image/chair_test2.jpg)| 

3D Reconstructed Model:

![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test2_0_view_1.png) | ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test2_0_view_2.png)| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test2_0_view_3.png)  |


| Original Sketch 3| 
| ------------- | 
| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/image/chair_test3.jpg)| 

3D Reconstructed Model:

![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test3_0_view_1.png) | ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test3_0_view_2.png)| ![alt text](https://github.com/srihari2761/maker.ai/blob/master/visualization/result/chair_test3_0_view_3.png)  |
