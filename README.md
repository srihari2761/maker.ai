# maker.ai
AI based 3D printer


cd marrnet
./download_models.sh

th main.lua -imgname chair_1.png

cd visualization/blender
blender --background --python render.py -- ../../output/chair_1.mat ../result/ chair_1
