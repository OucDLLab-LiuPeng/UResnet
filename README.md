# UResnet
A method to to underwater image enhancement.  
CycleGan is used to generate paired images to train UResnet.  
[[paper](https://ieeexplore.ieee.org/document/8763933)] 
# Samples of Training Set
!['traing set'](./images/trainingset.jpg)  
# Samples of Model Outputs
!['results'](./images/results.jpg)  
here is a video clip to show the results of our model  
[https://www.bilibili.com/video/av75799712/](https://www.bilibili.com/video/av75799712/)

the original videos we used are from Youtube  
[https://www.youtube.com/watch?v=VTmLIzz7jUU](https://www.youtube.com/watch?v=VTmLIzz7jUU)  
[https://www.youtube.com/watch?v=E4ZxR1C0xmc](https://www.youtube.com/watch?v=E4ZxR1C0xmc)
# Requirements
- Linux (code have not been tested on Windows or OSX)
- NVIDIA GPU + CUDA CuDNN
- pytorch >= 0.4.1
# Train model
use python train.py --input_images_path xxx/path/to/input/ --label_images_path xxx/path/to/label --snapshots_folder xxx/path/to/save/snapshot  
use python train.py -h to choose more usable options
# Dataset
The training set should be organized like  
Input image: xxx/path/input/abcd.jpg Label image: xxx/path/label/abcd_label.jpg



