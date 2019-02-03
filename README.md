# maker.ai
AI based 3D printer


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
