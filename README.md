# pose3d
The goal: estimate a 3D human pose in realtime with a combination of hardware + software

Expected features:
1) Frames per second - 80
2) Low power consumtion, small size
3) Does all the needed processing on the edge without being connected to the network

Hardware to do DL work: https://coral.withgoogle.com/

For the debugging purposes USB stick version might be used.

## Existing DL networks:
Uses TF based DL network to do 2D pose estimation separately and then converts it to 3D: https://github.com/SrikanthVelpuri/tf-pose

The pytorch based DL model produces 2D and a depth information at the same time: https://github.com/LlamaSi/pytorch-pose-hg-3d

## Useful links

Image sensor
https://openmv.io/products/global-shutter-camera-module

Converters between different  DL network models: https://github.com/ysh329/deep-learning-model-convertor

DL network viewer: https://github.com/lutzroeder/netron